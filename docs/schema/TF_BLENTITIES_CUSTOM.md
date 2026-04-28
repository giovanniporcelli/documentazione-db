# TF_BLENTITIES_CUSTOM

## Columns

| Name | Type | Default | Nullable | Comment |
| ---- | ---- | ------- | -------- | ------- |
| ID | char |  | false |  |
| PARENT_ID | char |  | true |  |
| TABLE_ID | char |  | true |  |
| CATEGORY_ID | bigint | ((1)) | false |  |
| FUNCTIONAL_AREA_ID | bigint |  | false |  |
| TYPE | nvarchar(100) | (N'Standard') | false |  |
| NAME | nvarchar(100) |  | false |  |
| DESCRIPTION | nvarchar(1000) |  | true |  |
| NAME_TEXT_ID | bigint |  | true |  |
| DESCRIPTION_TEXT_ID | bigint |  | true |  |
| SECURITY_PARENT_NAME | nvarchar(100) |  | true |  |
| SECURITY_TYPE | nvarchar(100) | (N'Standard') | false |  |
| SECURITY_DATA_SOURCE | nvarchar(MAX) |  | true |  |
| SECURITY_DEPENDENCIES | nvarchar(1000) |  | true |  |
| HISTORICAL_PARENT_NAME | nvarchar(100) |  | true |  |
| HAS_BUILT_IN_FILTER | smallint | ((0)) | false |  |
| ALTERN_SEC_PARENTFORSEARCH | nvarchar(100) |  | true |  |
| ALTERN_SEC_CANBEROOT | smallint |  | true |  |
| SERIALIZED_MODEL | nvarchar(MAX) |  | true |  |
| VERSION | nvarchar(100) | (N'1.0.0') | false |  |
| IS_ACTIVE | smallint | ((1)) | false |  |
| IS_ENABLED_CONFIG | smallint | ((0)) | false |  |
| IS_PARAMETERS_TARGET | smallint | ((0)) | false |  |
| IS_MAIN | smallint | ((0)) | false |  |
| IS_SYSTEM | smallint | ((0)) | false |  |
| IS_UNDER_AUDIT | smallint |  | true |  |
| INSERT_TIME | datetime2 | (sysutcdatetime()) | false |  |
| INSERT_USER | nvarchar(100) | (N'MAIN') | false |  |
| INSERT_CLIENT | nvarchar(50) | (N'localhost') | false |  |
| UPDATE_TIME | datetime2 | (sysutcdatetime()) | false |  |
| UPDATE_USER | nvarchar(100) | (N'MAIN') | false |  |
| UPDATE_CLIENT | nvarchar(50) | (N'localhost') | false |  |
| UPDATE_COUNT | int | ((0)) | false |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| PK_BLENTITIES_CUSTOM | PRIMARY KEY | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |
| UQ_BLENTITIES_CUSTOM_NAME | UNIQUE | NONCLUSTERED, unique, part of a UNIQUE constraint, [ NAME ] |

## Indexes

| Name | Definition |
| ---- | ---------- |
| PK_BLENTITIES_CUSTOM | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |
| UQ_BLENTITIES_CUSTOM_NAME | NONCLUSTERED, unique, part of a UNIQUE constraint, [ NAME ] |

## Triggers

| Name | Definition |
| ---- | ---------- |
| AUDIT_BLENTITIES_CUSTOM | -- Talentia Software - All right reserved<br />-- Type: TRIGGER                  Name: AUDIT_BLENTITIES_CUSTOM<br />-- Date: 09-04-2026 07:27:59 (UTC)<br />-- <br />-- ChangeLogId: 00000000-0000-0000-0000-000000000000<br />-- ChangeSetId: 68ec2725-8456-43fc-a3ef-6050b151acb0<br />-- Original file name: C:\repos\Talentia-Software\hcm-core/DB/ProductDB/EDM\Schema\Triggers\AUDIT_BLENTITIES_CUSTOM.xml<br /><br /><br />CREATE TRIGGER AUDIT_BLENTITIES_CUSTOM<br />   ON  TF_BLENTITIES_CUSTOM<br />   AFTER INSERT,DELETE,UPDATE<br />AS <br />BEGIN<br />	-- SET NOCOUNT ON added to prevent extra result sets from<br />	-- interfering with SELECT statements.<br />	SET NOCOUNT ON;<br />	<br />	DECLARE @TableName varchar(100) = 'TF_BLENTITIES_CUSTOM'<br />	DECLARE @FactoryTableName varchar(100) = 'TF_BLENTITIES'<br />	DECLARE @TargetObjectType varchar(100) = 'Entity'<br /><br />	DECLARE	@DefAuditPolicyStatus bit = CASE WHEN (SELECT ACTIVE FROM TF_AUDIT_SWITCH WHERE ID = 1) = 1 THEN 1 ELSE 0 END <br />	DECLARE @OperationType smallint -- Insert 1, Update 2, Delete 3<br /><br />	DECLARE @UpdateDate varchar(23)<br /><br />	DECLARE @ContextInfo varchar(128)<br />	DECLARE @ClientInfo nvarchar(max)<br />	DECLARE @DirectSQL bit = 0<br /><br />	DECLARE @SQL nvarchar(max)<br />	<br />	DECLARE @SQLWorkTable nvarchar(max)<br />	DECLARE @SQLWorkTable2 nvarchar(max)<br />	<br />	DECLARE @SQLStartInsertTo nvarchar(max)<br />	DECLARE @SQLInsertUser nvarchar(max)<br />	DECLARE @SQLInsertClient  nvarchar(max)<br /><br />	if (@DefAuditPolicyStatus=1) <br />	BEGIN<br /><br />		--Get Operation Type<br />		if exists (SELECT * FROM inserted)<br />			if exists (SELECT * FROM deleted)<br />				SELECT @OperationType = 2 --Update<br />			else<br />				SELECT @OperationType = 1 --Insert<br />		else<br />			SELECT @OperationType = 3 --Delete<br /><br />		--GET THE SAME DATE FOR ALL<br />		SELECT @UpdateDate = '''' + convert(varchar(8), getutcdate(), 112) + ' ' + convert(varchar(12), getutcdate(), 114) + ''''<br />		<br />		--get Context Info<br />		IF CONTEXT_INFO() is null<br />			BEGIN<br />				SELECT @ContextInfo= ''<br />				SET @DirectSQL = 1<br />			END<br />		ELSE<br />			BEGIN<br />				-- Context Info should contain the Applicative UserName<br />				SELECT @ContextInfo = REPLACE(CAST(CONTEXT_INFO() as varchar(128)), NCHAR(0) COLLATE Latin1_General_100_BIN2, N'');<br />				SET @DirectSQL = 0<br />			END<br />	<br />		--Get Client Info<br />		SET @ClientInfo = SYSTEM_USER<br /><br />		-- TEMPORARY TABLES<br />		SELECT * INTO #ins FROM inserted<br />		SELECT * INTO #del FROM deleted<br /><br />		-- Start of the SQL request	<br />		SET @SQLStartInsertTo = 'INSERT INTO TF_AUDIT_DATADICTIONARY<br />           ([TARGET_OBJECT_TYPE],[OBJECT_ID],[OBJECT_NAME],[PARENT_OBJECT_ID],[SERIALIZED_MODEL],[OLD_SERIALIZED_MODEL],[OPERATION_TYPE],<br />           [IS_FACTORY],[INSERT_USER],[INSERT_CLIENT],[INSERT_TIME],[TRANSACTION_ID])'<br />			<br />		-- INSERTED OPERATION TYPE<br />		IF(@OperationType = 1)<br />		BEGIN<br />			SET @SQLWorkTable = '#ins'<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + '''' <br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br />			<br />			SET @SQL = @SQLStartInsertTo +'SELECT ''' + @TargetObjectType + ''',i.ID, i.NAME, NULL, convert(nvarchar(max),i.SERIALIZED_MODEL), F.SERIALIZED_MODEL,<br />				1, 0, ' + @SQLInsertUser + ',' + @SQLInsertClient +', ' + @UpdateDate + ', CURRENT_TRANSACTION_ID() <br />				FROM '+@SQLWorkTable+' i <br />					LEFT JOIN '+@FactoryTableName+' F ON i.ID = F.ID' <br /><br />			EXEC ( @Sql )				<br />			   <br />		END<br />		-- UPDATED OPERATION TYPE<br />		IF(@OperationType = 2)<br />		BEGIN<br />			SET @SQLWorkTable = '#ins'<br />			SET @SQLWorkTable2 = '#del'<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + '''' <br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br /><br />			SET @SQL = @SQLStartInsertTo +'SELECT ''' + @TargetObjectType + ''',i.ID, i.NAME, NULL, convert(nvarchar(max),i.SERIALIZED_MODEL), convert(nvarchar(max),d.SERIALIZED_MODEL),<br />				2, 0, ' + @SQLInsertUser + ',' + @SQLInsertClient +', ' + @UpdateDate + ', CURRENT_TRANSACTION_ID() <br />				FROM '+@SQLWorkTable+' i<br />					INNER JOIN '+@SQLWorkTable2+' d ON i.ID = d.ID AND i.SERIALIZED_MODEL <> d.SERIALIZED_MODEL'<br /><br />			EXEC ( @Sql )				<br />			   <br />		END<br />		-- DELETED OPERATION TYPE<br />		IF(@OperationType = 3)<br />		BEGIN<br /><br />			SET @SQLWorkTable = '#del'<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + ''''<br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br />					<br />			SET @SQL = @SQLStartInsertTo +'SELECT ''' + @TargetObjectType + ''',d.ID, d.NAME, NULL, F.SERIALIZED_MODEL, convert(nvarchar(max),d.SERIALIZED_MODEL),<br />				3, CASE WHEN F.SERIALIZED_MODEL IS NULL THEN 0 ELSE 1 END, ' + @SQLInsertUser + ',' + @SQLInsertClient +', ' + @UpdateDate + ', CURRENT_TRANSACTION_ID() <br />				FROM '+@SQLWorkTable+' d <br />					LEFT JOIN '+@FactoryTableName+' F ON d.ID = F.ID' <br /><br />			EXEC ( @Sql )				<br />		END<br />		END<br />END<br /><br /> |

## Relations

![er](TF_BLENTITIES_CUSTOM.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
