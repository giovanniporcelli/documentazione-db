# TF_CODES

## Columns

| Name | Type | Default | Nullable | Parents | Comment |
| ---- | ---- | ------- | -------- | ------- | ------- |
| ID | bigint |  | false |  |  |
| ENTITY_ID | char |  | false |  |  |
| CODIFICATION_ID | bigint |  | true | [TF_CODIFICATIONS](TF_CODIFICATIONS.md) |  |
| CODE | nvarchar(500) |  | false |  |  |
| DESCRIPTION | nvarchar(1000) |  | true |  |  |
| PARENT_ID | bigint |  | true |  |  |
| GLOBAL_ID | bigint |  | true |  |  |
| INTERNAL_CODE_ID | bigint |  | true |  |  |
| EFFECTIVE_FROM | datetime |  | true |  |  |
| EFFECTIVE_TO | datetime |  | true |  |  |
| SORT_ORDER | int | ((0)) | false |  |  |
| IS_FACTORY | smallint | ((0)) | false |  |  |
| IS_ENABLED | smallint | ((1)) | false |  |  |
| IS_UPDATED | smallint | ((0)) | false |  |  |
| CT_STRING1 | nvarchar(2000) |  | true |  |  |
| CT_STRING2 | nvarchar(2000) |  | true |  |  |
| CT_STRING3 | nvarchar(2000) |  | true |  |  |
| CT_STRING4 | nvarchar(2000) |  | true |  |  |
| CT_STRING5 | nvarchar(2000) |  | true |  |  |
| CT_STRING6 | nvarchar(2000) |  | true |  |  |
| CT_STRING7 | nvarchar(2000) |  | true |  |  |
| CT_STRING8 | nvarchar(2000) |  | true |  |  |
| CT_STRING9 | nvarchar(2000) |  | true |  |  |
| CT_STRING10 | nvarchar(2000) |  | true |  |  |
| CT_TEXT1 | nvarchar(MAX) |  | true |  |  |
| CT_TEXT2 | nvarchar(MAX) |  | true |  |  |
| CT_TEXT3 | nvarchar(MAX) |  | true |  |  |
| CT_TEXT4 | nvarchar(MAX) |  | true |  |  |
| CT_TEXT5 | nvarchar(MAX) |  | true |  |  |
| CT_DATETIME1 | datetime |  | true |  |  |
| CT_DATETIME2 | datetime |  | true |  |  |
| CT_DATETIME3 | datetime |  | true |  |  |
| CT_DATETIME4 | datetime |  | true |  |  |
| CT_DATETIME5 | datetime |  | true |  |  |
| CT_DATETIME6 | datetime |  | true |  |  |
| CT_DATETIME7 | datetime |  | true |  |  |
| CT_DATETIME8 | datetime |  | true |  |  |
| CT_DATETIME9 | datetime |  | true |  |  |
| CT_DATETIME10 | datetime |  | true |  |  |
| CT_BOOL1 | smallint |  | true |  |  |
| CT_BOOL2 | smallint |  | true |  |  |
| CT_BOOL3 | smallint |  | true |  |  |
| CT_BOOL4 | smallint |  | true |  |  |
| CT_BOOL5 | smallint |  | true |  |  |
| CT_BOOL6 | smallint |  | true |  |  |
| CT_BOOL7 | smallint |  | true |  |  |
| CT_BOOL8 | smallint |  | true |  |  |
| CT_BOOL9 | smallint |  | true |  |  |
| CT_BOOL10 | smallint |  | true |  |  |
| CT_LOOKUP1 | bigint |  | true |  |  |
| CT_LOOKUP2 | bigint |  | true |  |  |
| CT_LOOKUP3 | bigint |  | true |  |  |
| CT_LOOKUP4 | bigint |  | true |  |  |
| CT_LOOKUP5 | bigint |  | true |  |  |
| CT_LOOKUP6 | bigint |  | true |  |  |
| CT_LOOKUP7 | bigint |  | true |  |  |
| CT_LOOKUP8 | bigint |  | true |  |  |
| CT_LOOKUP9 | bigint |  | true |  |  |
| CT_LOOKUP10 | bigint |  | true |  |  |
| CT_INTEGER1 | bigint |  | true |  |  |
| CT_INTEGER2 | bigint |  | true |  |  |
| CT_INTEGER3 | bigint |  | true |  |  |
| CT_INTEGER4 | bigint |  | true |  |  |
| CT_INTEGER5 | bigint |  | true |  |  |
| CT_INTEGER6 | bigint |  | true |  |  |
| CT_INTEGER7 | bigint |  | true |  |  |
| CT_INTEGER8 | bigint |  | true |  |  |
| CT_INTEGER9 | bigint |  | true |  |  |
| CT_INTEGER10 | bigint |  | true |  |  |
| CT_DECIMAL1 | decimal |  | true |  |  |
| CT_DECIMAL2 | decimal |  | true |  |  |
| CT_DECIMAL3 | decimal |  | true |  |  |
| CT_DECIMAL4 | decimal |  | true |  |  |
| CT_DECIMAL5 | decimal |  | true |  |  |
| CT_DECIMAL6 | decimal |  | true |  |  |
| CT_DECIMAL7 | decimal |  | true |  |  |
| CT_DECIMAL8 | decimal |  | true |  |  |
| CT_DECIMAL9 | decimal |  | true |  |  |
| CT_DECIMAL10 | decimal |  | true |  |  |
| INSERT_TIME | datetime2 | (sysutcdatetime()) | false |  |  |
| INSERT_USER | nvarchar(100) | (N'MAIN') | false |  |  |
| INSERT_CLIENT | nvarchar(50) | (N'localhost') | false |  |  |
| UPDATE_TIME | datetime2 | (sysutcdatetime()) | false |  |  |
| UPDATE_USER | nvarchar(100) | (N'MAIN') | false |  |  |
| UPDATE_CLIENT | nvarchar(50) | (N'localhost') | false |  |  |
| UPDATE_COUNT | int | ((0)) | false |  |  |
| WORKFLOW_ID | bigint |  | true |  |  |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| PK_CODES | PRIMARY KEY | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |
| UQ_CODES | UNIQUE | NONCLUSTERED, unique, part of a UNIQUE constraint, [ ENTITY_ID, CODIFICATION_ID, CODE ] |
| FK_CODES_CODIFICATIONS | FOREIGN KEY | FOREIGN KEY(CODIFICATION_ID) REFERENCES TF_CODIFICATIONS(ID) ON UPDATE NO_ACTION ON DELETE NO_ACTION |

## Indexes

| Name | Definition |
| ---- | ---------- |
| PK_CODES | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |
| UQ_CODES | NONCLUSTERED, unique, part of a UNIQUE constraint, [ ENTITY_ID, CODIFICATION_ID, CODE ] |
| IDX_CODES_CODIFICATION | NONCLUSTERED, [ CODIFICATION_ID ] |
| TF_CODES_LOOKUP1 | NONCLUSTERED, [ CT_LOOKUP1 ] |
| TF_CODES_LOOKUP2 | NONCLUSTERED, [ CT_LOOKUP2 ] |
| TF_CODES_LOOKUP3 | NONCLUSTERED, [ CT_LOOKUP3 ] |
| TF_CODES_LOOKUP4 | NONCLUSTERED, [ CT_LOOKUP4 ] |
| TF_CODES_LOOKUP5 | NONCLUSTERED, [ CT_LOOKUP5 ] |
| TF_CODES_LOOKUP6 | NONCLUSTERED, [ CT_LOOKUP6 ] |
| TF_CODES_LOOKUP7 | NONCLUSTERED, [ CT_LOOKUP7 ] |
| TF_CODES_LOOKUP8 | NONCLUSTERED, [ CT_LOOKUP8 ] |
| TF_CODES_LOOKUP9 | NONCLUSTERED, [ CT_LOOKUP9 ] |
| TF_CODES_LOOKUP10 | NONCLUSTERED, [ CT_LOOKUP10 ] |
| IDX_CODES_DECIMALS | NONCLUSTERED, [ ENTITY_ID, CT_DECIMAL1, CT_DECIMAL2 ] |

## Triggers

| Name | Definition |
| ---- | ---------- |
| AUDIT_TF_CODES | -- Talentia Software - All right reserved<br />-- Type: TRIGGER                  Name: AUDIT_TF_CODES<br />-- Date: 09-04-2026 07:27:59 (UTC)<br />-- <br />-- ChangeLogId: 00000000-0000-0000-0000-000000000000<br />-- ChangeSetId: 1b02963b-55cf-490f-9461-86919fac3d78<br />-- Original file name: C:\repos\Talentia-Software\hcm-core/DB/ProductDB/EDM\Schema\Triggers\AUDIT_TF_CODES.xml<br /><br /><br />CREATE TRIGGER AUDIT_TF_CODES <br />   ON  TF_CODES<br />   AFTER INSERT,DELETE,UPDATE<br />AS <br />BEGIN<br />	-- SET NOCOUNT ON added to prevent extra result sets from<br />	-- interfering with SELECT statements.<br />	SET NOCOUNT ON;<br /><br />    -- Insert statements for trigger here<br /><br />	DECLARE @TableName varchar(100)<br />	DECLARE @LinkedEntityID varchar(36)<br /><br />	DECLARE	@DefAuditPolicyStatus bit<br />	DECLARE @OperationType smallint -- Insert 1, Update 2, Delete 3<br />	DECLARE @ColumnKey varchar(100)<br />	DECLARE @PrimaryKey int<br />	DECLARE @Fields nvarchar(max)<br />	DECLARE @PrimaryKeyFieldName nvarchar(100)<br />	DECLARE @UpdateDate varchar(21)<br /><br />	DECLARE @EntityIdColumn varchar(100)<br /><br />	DECLARE @ColumnName nvarchar(max)<br />	DECLARE @EntityName nvarchar(max)<br />	DECLARE @EntityID char(36)<br />	DECLARE @ColumnID char(36)<br />	DECLARE @FieldID char(36)<br />	DECLARE @FieldName nvarchar(max)<br />	DECLARE @FieldType smallint<br /><br />	DECLARE @ContextInfo varchar(128)<br />	DECLARE @ClientInfo nvarchar(max)<br />	DECLARE @DirectSQL bit = 0<br /><br />	DECLARE @SQL nvarchar(max)<br />	DECLARE @SQL1 nvarchar(max)<br />	DECLARE @SQL2 nvarchar(max)<br />	DECLARE @SQL3 nvarchar(max)<br />	DECLARE @SQL4 nvarchar(max)<br />	DECLARE @SQL5 nvarchar(max)<br />	DECLARE @SQL6 nvarchar(max)<br />	DECLARE @SQLWorkTable nvarchar(max)<br />	DECLARE @SQLWorkTableRef nvarchar(max)<br />	DECLARE @SQLStart nvarchar(max)<br />	DECLARE @SQLStartInsertTo nvarchar(max)<br />	DECLARE @SQLStartSelect nvarchar(max)<br />	DECLARE @SQLPrimaryKeyField nvarchar(max)<br />	DECLARE @SQLNewValueFields nvarchar(max)<br />	DECLARE @SQLOldValueFields nvarchar(max)<br />	DECLARE @SQLInsertUser nvarchar(max)<br />	DECLARE @SQLInsertClient  nvarchar(max)<br />	DECLARE @SQLAuditFields nvarchar(max)<br />	DECLARE @SQLAuditFieldsInserted nvarchar(max)<br />	DECLARE @SQLAuditFieldsDeleted nvarchar(max)<br />	DECLARE @req nVARCHAR(MAX) <br /><br />	SET @Tablename = 'TF_CODES'<br /><br />	--IF AUDITED IS ENABLE<br />	SELECT @DefAuditPolicyStatus = ACTIVE FROM TF_AUDIT_SWITCH WHERE [ID]=1<br />	if (@DefAuditPolicyStatus=1) <br />	BEGIN<br /><br />		DECLARE @EntityAuditedFields as int = (SELECT COUNT(*) FROM TF_AUDITED_COLUMNS WHERE ENTITY_ID IN<br />		(<br />			SELECT DISTINCT ENTITY_ID FROM inserted <br />			UNION<br />			SELECT DISTINCT ENTITY_ID FROM deleted<br />		)<br />		AND IS_UNDER_AUDIT = 1)<br />		<br />		IF (@EntityAuditedFields = 0)<br />		RETURN;<br />    <br />		--Get Operation Type<br />		if exists (SELECT * FROM inserted)<br />			if exists (SELECT * FROM deleted)<br />				SELECT @OperationType = 2 --Update<br />			else<br />				SELECT @OperationType = 1 --Insert<br />		else<br />			SELECT @OperationType = 3 --Delete<br /><br />		--GET HasEntityId<br />		SET @EntityIdColumn = 'ENTITY_ID'<br /><br />		--GET THE SAME DATE FOR ALL<br />		SELECT @UpdateDate = convert(varchar(8), getutcdate(), 112) + ' ' + convert(varchar(12), getutcdate(), 114)<br /><br />		--Get Primary field name<br />		SELECT @PrimaryKeyFieldName = 'ID'<br /><br />		--get Context Info<br />		IF CONTEXT_INFO() is null<br />			BEGIN<br />				SELECT @ContextInfo= ''<br />				SET @DirectSQL = 1<br />			END<br />		ELSE<br />			BEGIN<br />				-- Context Info should contain the Applicative UserName<br />				SELECT @ContextInfo = REPLACE(CAST(CONTEXT_INFO() as varchar(128)), NCHAR(0) COLLATE Latin1_General_100_BIN2, N'');<br />				SET @DirectSQL = 0<br />			END<br />	<br />		--Get Client Info<br />		SET @ClientInfo = SYSTEM_USER<br /><br />		-- TEMPORARY TABLES<br />		SELECT * INTO #ins FROM inserted<br />		SELECT * INTO #del FROM deleted<br /><br />		-- Start of the SQL request<br />		SET @SQLStart = 'INSERT INTO TF_AUDIT<br />				(  [TABLE_NAME], [ENTITY_NAME], [ENTITY_ID], [COLUMN_NAME], [FIELD_NAME], [FIELD_ID], [FIELD_TYPE]<br />				    ,[PRIMARY_KEY], [OPERATION_TYPE]<br />					,[LONG_VALUE],[DECIMAL_VALUE],[DATETIME_VALUE],[STRING_VALUE],[VARBINARY_VALUE]<br />					,[OLD_LONG_VALUE],[OLD_DECIMAL_VALUE],[OLD_DATETIME_VALUE],[OLD_STRING_VALUE],[OLD_VARBINARY_VALUE]<br />					,[INSERT_USER],[INSERT_CLIENT],[INSERT_TIME],[TRANSACTION_ID]<br />				) <br />				SELECT AUDITED_COLUMNS.[TABLE_NAME], AUDITED_COLUMNS.[ENTITY_NAME], AUDITED_COLUMNS.[ENTITY_ID], AUDITED_COLUMNS.[COLUMN_NAME], AUDITED_COLUMNS.[FIELD_NAME], AUDITED_COLUMNS.[FIELD_ID], AUDITED_COLUMNS.[FIELD_TYPE]'<br />		<br />		SET @SQLStartInsertTo = 'INSERT INTO TF_AUDIT<br />				(  [TABLE_NAME], [ENTITY_NAME], [ENTITY_ID], [COLUMN_NAME], [FIELD_NAME], [FIELD_ID], [FIELD_TYPE]<br />				    ,[PRIMARY_KEY], [OPERATION_TYPE]<br />					,[LONG_VALUE],[DECIMAL_VALUE],[DATETIME_VALUE],[STRING_VALUE],[VARBINARY_VALUE]<br />					,[OLD_LONG_VALUE],[OLD_DECIMAL_VALUE],[OLD_DATETIME_VALUE],[OLD_STRING_VALUE],[OLD_VARBINARY_VALUE]<br />					,[INSERT_USER],[INSERT_CLIENT],[INSERT_TIME],[TRANSACTION_ID]<br />				) <br />				'<br />		SET @SQLStartSelect = '<br />				SELECT AUDITED_COLUMNS.[TABLE_NAME], AUDITED_COLUMNS.[ENTITY_NAME], AUDITED_COLUMNS.[ENTITY_ID], AUDITED_COLUMNS.[COLUMN_NAME], AUDITED_COLUMNS.[FIELD_NAME], AUDITED_COLUMNS.[FIELD_ID], AUDITED_COLUMNS.[FIELD_TYPE]<br />				'<br />	<br />		-- INSERTED OPERATION TYPE<br />		IF(@OperationType = 1)<br />		BEGIN<br />			SET @SQLWorkTable = '#ins'<br />			SET @SQLWorkTableRef = @SQLWOrkTable + '.'<br />			SET @SQLPrimaryKeyField = @SQLWorkTableRef + @PrimaryKeyFieldName<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + '''' <br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br />			SET @SQL1 = @SQLStartSelect + ' ,' + @SQLPrimaryKeyField + ', ' + convert(nvarchar(max), @OperationType) <br />			SET @SQL2 = ',NULL, NULL, NULL, NULL, NULL' + <br />			',' + @SQLInsertUser + ', ' + @SQLInsertClient + ', '''+ @UpdateDate + ''', CURRENT_TRANSACTION_ID()<br />			FROM TF_AUDITED_COLUMNS AUDITED_COLUMNS INNER JOIN ' + @SQLWorkTable + ' ON AUDITED_COLUMNS.TABLE_NAME = ''' + @Tablename + ''' AND IS_KEY = 0 AND AUDITED_COLUMNS.COLUMN_NAME = '''<br />			SET @SQL3 = ''' AND AUDITED_COLUMNS.ENTITY_ID = '''<br />			SET @SQL4 = ''' WHERE ' + @SQLWorkTableRef + @EntityIdColumn + ' = AUDITED_COLUMNS.ENTITY_ID<br />			'<br />			SELECT @req = Coalesce( @req +  ' UNION ', '') + @SQL1 +'<br />			' + <br />				CASE WHEN Field_type =  2  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  3  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  4  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  1  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  5  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />			@SQL2 + COLUMN_NAME + @SQL3 + ENTITY_ID + @SQL4<br /><br />			FROM   TF_AUDITED_COLUMNS<br />			WHERE  TABLE_NAME = @Tablename<br />							AND IS_UNDER_AUDIT = 1<br />			ORDER BY COLUMN_NAME<br /><br />			SET @SQL = @SQLStartInsertTo + @req<br /><br />			EXEC ( @Sql )	<br />			   <br />		END<br />		-- UPDATED OPERATION TYPE<br />		IF(@OperationType = 2)<br />		BEGIN<br />			SET @SQLWorkTable = '#ins'<br />			SET @SQLWorkTableRef = @SQLWOrkTable + '.'<br />			SET @SQLPrimaryKeyField = @SQLWorkTableRef + @PrimaryKeyFieldName<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + '''' <br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br />			SET @SQL1 = @SQLStartSelect + ' ,' + @SQLPrimaryKeyField + ', ' + convert(nvarchar(max), @OperationType) <br />			SET @SQL2 = ', ' + @SQLInsertUser + ', ' +@SQLInsertClient + ', '''+ @UpdateDate + ''', CURRENT_TRANSACTION_ID()<br />			FROM TF_AUDITED_COLUMNS AUDITED_COLUMNS INNER JOIN #INS ON AUDITED_COLUMNS.TABLE_NAME = ''' + @Tablename + ''' AND IS_KEY = 0 AND AUDITED_COLUMNS.COLUMN_NAME = '''<br />			SET @SQL3 = ''' AND AUDITED_COLUMNS.ENTITY_ID = '''<br />			SET @SQL4 = ''' <br />			INNER JOIN #DEL on ' + @SQLWorkTableRef + @PrimaryKeyFieldName + ' = #DEL.' + @PrimaryKeyFieldName + ' AND ' + @SQLWorkTableRef<br />			SET @SQL5 = ' <> #DEL.'<br />			SET @SQL6 = '<br />			WHERE ' + @SQLWorkTableRef + @EntityIdColumn + ' = AUDITED_COLUMNS.ENTITY_ID'<br /><br />			SELECT @req = Coalesce( @req +  ' UNION ', '') + @SQL1 +'<br />			' + <br />				CASE WHEN Field_type =  2  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  3  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  4  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  1  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  5  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  2  THEN ', #del.' + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  3  THEN ', #del.' + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  4  THEN ', #del.' + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  1  THEN ', #del.' + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  5  THEN ', #del.' + COLUMN_NAME ELSE ', NULL' END + <br />			@SQL2 + COLUMN_NAME + @SQL3 + ENTITY_ID +@SQL4 + COLUMN_NAME + @SQL5 + COLUMN_NAME + @SQL6<br /><br />			FROM   TF_AUDITED_COLUMNS<br />			WHERE  TABLE_NAME = @Tablename<br />							AND IS_UNDER_AUDIT = 1<br />			ORDER BY COLUMN_NAME<br /><br />			SET @SQL = @SQLStartInsertTo + @req<br /><br />			EXEC ( @Sql )<br />			   <br />		END<br />		-- DELETED OPERATION TYPE<br />		IF(@OperationType = 3)<br />		BEGIN<br />			SET @SQLWorkTable = '#del'<br />			SET @SQLWorkTableRef = @SQLWOrkTable + '.'<br />			SET @SQLPrimaryKeyField = @SQLWorkTableRef + @PrimaryKeyFieldName<br />			SET @SQLInsertUser = '''' + Replace(@ContextInfo,'''','''''') + '''' <br />			SET @SQLInsertClient =  '''' + @ClientInfo + ''''<br />			SET @SQL1 = @SQLStartSelect + ' ,' + @SQLPrimaryKeyField + ', ' + convert(nvarchar(max), @OperationType) <br />			SET @SQL2 = ',NULL, NULL, NULL, NULL, NULL' +  <br />			', ' + @SQLInsertUser + ', ' + @SQLInsertClient + ', '''+ @UpdateDate + ''', CURRENT_TRANSACTION_ID()<br />			FROM TF_AUDITED_COLUMNS AUDITED_COLUMNS INNER JOIN ' + @SQLWorkTable + ' ON AUDITED_COLUMNS.TABLE_NAME = ''' + @Tablename + ''' AND IS_KEY = 0 AND AUDITED_COLUMNS.COLUMN_NAME = '''<br />			SET @SQL3 = ''' AND AUDITED_COLUMNS.ENTITY_ID = '''<br />			SET @SQL4 = ''' <br />			WHERE ' + @SQLWorkTableRef + @EntityIdColumn + ' = AUDITED_COLUMNS.ENTITY_ID'<br />			SELECT @req = Coalesce( @req +  ' UNION ', '') + @SQL1 +'<br />			' + <br />				CASE WHEN Field_type =  2  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  3  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  4  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  1  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				CASE WHEN Field_type =  5  THEN ', ' + @SQLWorkTableRef + COLUMN_NAME ELSE ', NULL' END +<br />				@SQL2 + COLUMN_NAME + @SQL3 + ENTITY_ID + @SQL4<br /><br />			FROM   TF_AUDITED_COLUMNS<br />			WHERE  TABLE_NAME = @Tablename<br />							AND IS_UNDER_AUDIT = 1<br />			ORDER BY COLUMN_NAME<br /><br />			SET @SQL = @SQLStartInsertTo + @req<br /><br />			EXEC ( @Sql )			<br />			   <br />		END<br />	END<br />END<br /><br /> |

## Relations

![er](TF_CODES.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
