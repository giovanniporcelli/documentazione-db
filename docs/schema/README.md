# 2026_04_01_Application

## Tables

| Name | Columns | Comment | Type |
| ---- | ------- | ------- | ---- |
| [HR_APPRCOMPSECROWANSW](HR_APPRCOMPSECROWANSW.md) | 15 | Appraisal Competency Section Row Answer - This entity stores the answers to questions which are associated to competencies.<br /> | BASIC TABLE |
| [TF_TAGS_ENTITIES](TF_TAGS_ENTITIES.md) | 15 | Entities Tag - The tags used for the specific entities<br /> | BASIC TABLE |
| [TF_DW_CONSUMED_TOKENS](TF_DW_CONSUMED_TOKENS.md) | 13 | LLM consumed tokens - This entity would return the consumed tokens x iteration, divided into request, response and total consumed tokens<br /> | BASIC TABLE |
| [TF_LANGUAGES](TF_LANGUAGES.md) | 14 | Smart Translator Languages - This entity contains the Smart Translator Languages<br /> | BASIC TABLE |
| [TF_EPR_PACKAGE_RANGES](TF_EPR_PACKAGE_RANGES.md) | 13 | Sequence ranges associated to a package - Package Ranges<br /> | BASIC TABLE |
| [HR_ARCA24ST_CANDIDATE](HR_ARCA24ST_CANDIDATE.md) | 96 | Arca24 Staging Table Candidate - Staging table for data coming from Arca24 - Candidate data.<br /> | BASIC TABLE |
| [HR_LOCATIONASSIGNMENT](HR_LOCATIONASSIGNMENT.md) | 17 | Location Assignment - Indicates which Company's Location the employee has a Contract with. It is not necessarily equal to the Working Location.<br /> | BASIC TABLE |
| [HR_LOCATION](HR_LOCATION.md) | 17 | Location - The location of a Company.<br /> | BASIC TABLE |
| [TF_BLCONTEXT_TYPES](TF_BLCONTEXT_TYPES.md) | 14 | Context types - List of all possible context types<br /> | BASIC TABLE |
| [HR_POSITION](HR_POSITION.md) | 18 | Position - A single or specific instance of a job in the context of an Organizational Structure.<br /> | BASIC TABLE |
| [TF_LICENSES](TF_LICENSES.md) | 11 |  | BASIC TABLE |
| [TF_SECSTORED_FILTER_CATALOG](TF_SECSTORED_FILTER_CATALOG.md) | 12 | Security SQL condition catalog - Catalog of SQL security conditions used by the multi-role security system<br /> | BASIC TABLE |
| [TF_APP_PARAMETERS_ENTITIES](TF_APP_PARAMETERS_ENTITIES.md) | 33 | Application Parameters Entities - Application Parameters Entities<br /> | BASIC TABLE |
| [TF_WFRT_SUBJECTS](TF_WFRT_SUBJECTS.md) | 18 |  | BASIC TABLE |
| [TF_NAV_PRO_CFGS_QUI_ACTIONS](TF_NAV_PRO_CFGS_QUI_ACTIONS.md) | 13 | Navigation Profile Configurations Quick Actions - Navigation Profile Configurations Quick Actions<br /> | BASIC TABLE |
| [HR_ARCA24ST_EVALUATION](HR_ARCA24ST_EVALUATION.md) | 58 | Arca24 Staging Table: Evaluation - Staging table for data coming from Arca24 - Evaluation data. | BASIC TABLE |
| [TF_WFSTAGE_ROLES](TF_WFSTAGE_ROLES.md) | 11 | Workflow Stage Roles - Workflow Stage Roles<br /> | BASIC TABLE |
| [TF_INDEX_CATEGORIES](TF_INDEX_CATEGORIES.md) | 11 | Index Categories - TF_INDEX_CATEGORIES<br /> | BASIC TABLE |
| [HR_COMPINPOINTSPARTICIPANTS](HR_COMPINPOINTSPARTICIPANTS.md) | 15 | Compensation in Points grid participants  - Participants in the Compensation in Points grid | BASIC TABLE |
| [HR_COMPANYACCOUNTABILITY](HR_COMPANYACCOUNTABILITY.md) | 19 | Company to Company Accountabilities - This Entity represents the hierarchical relationship between Companies in the same Group. Used for example to represent a relationship between an Holding and depending companies.<br /> | BASIC TABLE |
| [TF_DATA_LOADER_EXPORT](TF_DATA_LOADER_EXPORT.md) | 6 |  | BASIC TABLE |
| [HR_TIMESHEETDAY](HR_TIMESHEETDAY.md) | 29 | Timesheet Day - The timesheet day entity<br /> | BASIC TABLE |
| [HR_EMPLOYMENTSTATUS](HR_EMPLOYMENTSTATUS.md) | 23 | Employment Status - Used to identify in which stage the Company Relationship is, Active-Non Active-Temporary Leave, etc.<br /> | BASIC TABLE |
| [TF_DW_NAMED_ENTITY_ITEMS](TF_DW_NAMED_ENTITY_ITEMS.md) | 12 | Named Entity Items - Named Entity Items<br /> | BASIC TABLE |
| [TF_BLRULES_PROPERTIES](TF_BLRULES_PROPERTIES.md) | 15 |  | BASIC TABLE |
| [TF_ADV_GRID_RENDER_VALUES](TF_ADV_GRID_RENDER_VALUES.md) | 21 | Advanced Datagrid Renderer Value - Advanced Datagrid Renderer Value<br /> | BASIC TABLE |
| [HR_ADDITIONALTERMS](HR_ADDITIONALTERMS.md) | 17 | Additional Contract Terms - Used to record Additional Terms of the Contract<br /> | BASIC TABLE |
| [TF_BLRELATIONS_CUSTOM](TF_BLRELATIONS_CUSTOM.md) | 22 |  | BASIC TABLE |
| [TF_FOLLOWING_ENTITIES](TF_FOLLOWING_ENTITIES.md) | 11 | Following Entities - The Following Entities.<br /> | BASIC TABLE |
| [TF_SEC_ALTERN_VISIBILITY](TF_SEC_ALTERN_VISIBILITY.md) | 7 |  | BASIC TABLE |
| [TF_BLENTITIES_VIEW](TF_BLENTITIES_VIEW.md) | 29 | BL entities - Business Logic Entities<br /> | VIEW |
| [HR_SALARYREVIEWPARTSNAPSHOT](HR_SALARYREVIEWPARTSNAPSHOT.md) | 24 | Salary Review Participant Snapshot - For each participant, this entity takes a snapshot of relevant attributes at the reference date specified in the Salary Program. For “standalone” setup, this table gets normally imported.<br /> | BASIC TABLE |
| [HR_JOBEDUCATION](HR_JOBEDUCATION.md) | 17 | Job Education - This entity allows defining the education requirements for the specific job.<br /> | BASIC TABLE |
| [TF_TRANSLATIONS_TO_EXCLUDE](TF_TRANSLATIONS_TO_EXCLUDE.md) | 6 |  | BASIC TABLE |
| [HR_STAGING_EXTPAYLOAD](HR_STAGING_EXTPAYLOAD.md) | 14 | External Payload Staging Table - Staging table that stores payloads coming from external applications.<br /> | BASIC TABLE |
| [HR_ARCA24ST_INTVIEW_REQUEST](HR_ARCA24ST_INTVIEW_REQUEST.md) | 22 | Arca24 Staging Table: Interview Request - Staging table for data coming from Arca24 - Interview Request data. | BASIC TABLE |
| [HR_COURSECREDITS](HR_COURSECREDITS.md) | 27 | Course Credits - This entity contains the credits of the course.<br /> | BASIC TABLE |
| [TF_DATA_LOADER_TEMPLATES](TF_DATA_LOADER_TEMPLATES.md) | 41 | Data Loader Templates - Data Loader Templates<br /> | BASIC TABLE |
| [HR_PERSONSINDACATO](HR_PERSONSINDACATO.md) | 16 | Union Membership - Union Membership<br /> | BASIC TABLE |
| [TF_WEAK_DEPENDENCIES](TF_WEAK_DEPENDENCIES.md) | 13 | Weak Dependencies - Weak Dependencies<br /> | BASIC TABLE |
| [TF_SECFILTER_CONDITIONS](TF_SECFILTER_CONDITIONS.md) | 13 | Security Filter Conditions - Security Filter Conditions<br /> | BASIC TABLE |
| [HR_PAYSLIPDELIVERYMETHOD](HR_PAYSLIPDELIVERYMETHOD.md) | 15 | Pay Slip Delivery Method - Indicates how the payslip is delivered to the employee.<br /> | BASIC TABLE |
| [TF_MAINTENANCE_LOGS](TF_MAINTENANCE_LOGS.md) | 9 | Maintenance Logs - Captures detailed records of individual maintenance activities performed.<br /> | BASIC TABLE |
| [HR_ABSPLANEVENTREASON](HR_ABSPLANEVENTREASON.md) | 14 | Absence Plan Event Reason - Contains the association between absence plan and absence event reason.<br /> | BASIC TABLE |
| [TF_QST_QUESTIONNAIRES](TF_QST_QUESTIONNAIRES.md) | 38 | Questionnaires Definitions - Questionnaires Definitions<br /> | BASIC TABLE |
| [HR_PUBLICSPEAKINGEVENTS](HR_PUBLICSPEAKINGEVENTS.md) | 17 | Public Speaking Events - List of Public Events where the person attended as a Speaker.<br /> | BASIC TABLE |
| [HR_VARIABLEITEMS](HR_VARIABLEITEMS.md) | 22 | Variable Items - List of Variable Items.<br /> | BASIC TABLE |
| [HR_GENERICNOTES](HR_GENERICNOTES.md) | 18 | Person Additional Notes - It is the entity that contains the person's additional information.<br /> | BASIC TABLE |
| [HR_TIMESHEETDAY_ATTR](HR_TIMESHEETDAY_ATTR.md) | 13 | Timesheet Day Attributes - The Timesheet Day Attribute associative table.<br /> | BASIC TABLE |
| [TF_PAGES_LINKSETS](TF_PAGES_LINKSETS.md) | 12 | Pages link set - Pages link sets<br /> | BASIC TABLE |
| [HR_APPRAISALCYCLE](HR_APPRAISALCYCLE.md) | 36 | Appraisal Cycle - This Entity allows defining a container of Appraisals that make sense on a specific period for a given employee set.<br /> | BASIC TABLE |
| [HR_ARCA24ST_STEPS](HR_ARCA24ST_STEPS.md) | 19 | ARCA24 Staging Table: Steps - Staging table for data coming from ARCA24 - Steps data. | BASIC TABLE |
| [TF_TEMPORARY_DOCUMENTS](TF_TEMPORARY_DOCUMENTS.md) | 9 |  | BASIC TABLE |
| [HR_APPRCYCLEVALIDATIONLOG](HR_APPRCYCLEVALIDATIONLOG.md) | 17 | Appraisal Cycle Validation Log - Validation logs of an appraisal cycle<br /> | BASIC TABLE |
| [HR_SHORTLISTEDCND](HR_SHORTLISTEDCND.md) | 117 | Shortlisted Candidates - Shortlisted candidates are those candidates, internal or external, to whom a Job offer for a specific Vacancy has been proposed. For each candidate, basic contractual and deployment terms and conditions are also specified.<br /> | BASIC TABLE |
| [TF_DW_CONSUMED_TOKENS_CITS](TF_DW_CONSUMED_TOKENS_CITS.md) | 9 | LLM consumed tokens citations - LLM consumed tokens citations<br /> | BASIC TABLE |
| [TF_SHARED_REQUESTS](TF_SHARED_REQUESTS.md) | 16 | Shared Requests - The Shared Requests.<br /> | BASIC TABLE |
| [TF_EVENT_INSTANCES](TF_EVENT_INSTANCES.md) | 22 | Event Instances - The Event Instances.<br /> | BASIC TABLE |
| [TF_CODIFICATIONS](TF_CODIFICATIONS.md) | 26 | Codifications - List of Codifications.<br /> | BASIC TABLE |
| [HR_ORGUNITASSIGNMENT](HR_ORGUNITASSIGNMENT.md) | 21 | Organizational Deployment - Is the position or designation of the person within the given organization. Examples are Director, Software Engineer, Purchasing Manager etc.<br /> | BASIC TABLE |
| [HR_ORGUNIT](HR_ORGUNIT.md) | 16 | Organizational Unit - Organizational units are functional units in an Group. They can cross several Legal entities (Companies) and are normally designed around specific Functions or Types of Activities.<br /> | BASIC TABLE |
| [TF_USERGROUPS](TF_USERGROUPS.md) | 28 | User Groups - User Groups<br /> | BASIC TABLE |
| [TF_TRANSLATIONS](TF_TRANSLATIONS.md) | 17 | Data Translations Loader - Translations Loader<br /> | BASIC TABLE |
| [TF_LIKES](TF_LIKES.md) | 12 | Likes - The Likes.<br /> | BASIC TABLE |
| [HR_APPRGUIDELINE](HR_APPRGUIDELINE.md) | 16 | Appraisal Guideline - This entity contains the appraisals guidelines.<br /> | BASIC TABLE |
| [HR_LOCATIONATTRIBUTES](HR_LOCATIONATTRIBUTES.md) | 46 | Location Attributes - Contains required details about the properties of the location, like address, GPS coordinates etc.<br /> | BASIC TABLE |
| [TF_TAGS_USERS](TF_TAGS_USERS.md) | 11 | Users Tags - Users Tags<br /> | BASIC TABLE |
| [TF_AUDITED_COLUMNS](TF_AUDITED_COLUMNS.md) | 16 |  | BASIC TABLE |
| [TF_EPR_RECOVERY_DATA](TF_EPR_RECOVERY_DATA.md) | 12 |  | BASIC TABLE |
| [TF_ROLE_GRANTS](TF_ROLE_GRANTS.md) | 18 | Role Grants - Role Grants<br /> | BASIC TABLE |
| [HR_ARCA24ST_TOOL_REQUEST](HR_ARCA24ST_TOOL_REQUEST.md) | 21 | Arca24 Staging Table: Tool Request - Staging table for data coming from Arca24 - Tool Request data. | BASIC TABLE |
| [TF_MATRIX_GUIDELINES](TF_MATRIX_GUIDELINES.md) | 29 | Matrix Guidelines - Matrix Guidelines<br /> | BASIC TABLE |
| [HR_CONSTPAYROLLITEMASSIGN](HR_CONSTPAYROLLITEMASSIGN.md) | 24 | Worker Payroll Item Assignment - CONSTPAYROLLASSIGNMENT<br /> | BASIC TABLE |
| [TF_DW_CONSUMED_TOKENS_DET](TF_DW_CONSUMED_TOKENS_DET.md) | 7 | LLM consumed tokens details - This entity would log the details of each completion with the request and response.<br /> | BASIC TABLE |
| [TF_BLCONTEXT_VALUES](TF_BLCONTEXT_VALUES.md) | 12 | Context values - List of all possible context values<br /> | BASIC TABLE |
| [HR_STRUCTURE](HR_STRUCTURE.md) | 27 | STRUCTURES - STRUCTURES<br /> | BASIC TABLE |
| [HR_EQUIPMNTASSIGNMENT](HR_EQUIPMNTASSIGNMENT.md) | 18 | Equipment Assignment - Represents the history of Equipment Assignments associated to a specific Employee<br /> | BASIC TABLE |
| [TF_DW_NOTIFICATION_LOGS](TF_DW_NOTIFICATION_LOGS.md) | 10 |  | BASIC TABLE |
| [TF_WFSTAGE_RULES](TF_WFSTAGE_RULES.md) | 16 | Workflow Stage Rules - Workflow Stage Rules<br /> | BASIC TABLE |
| [TF_INDEX_DOCUMENT_ENTITIES](TF_INDEX_DOCUMENT_ENTITIES.md) | 11 | Index Document Entities - TF_INDEX_DOCUMENT_ENTITIES<br /> | BASIC TABLE |
| [TF_SCRIPTRULE_CATALOG](TF_SCRIPTRULE_CATALOG.md) | 23 | Script Rule Catalog - Script Rule Catalog<br /> | BASIC TABLE |
| [HR_ADDITIONALWORKERINFO](HR_ADDITIONALWORKERINFO.md) | 17 | Additional information - Additional information<br /> | BASIC TABLE |
| [TF_FOLLOWING_USERS](TF_FOLLOWING_USERS.md) | 11 | Followed Users - The Followed Users<br /> | BASIC TABLE |
| [TF_AUTHENTICATION_PROVIDERS](TF_AUTHENTICATION_PROVIDERS.md) | 24 | Authentication provider - TF_AUTHENTICATION_PROVIDERS<br /> | BASIC TABLE |
| [HR_STAGING_P_ANALYTIC_CR](HR_STAGING_P_ANALYTIC_CR.md) | 22 | External Payroll Worker Analytics - Staging table for comparison between Core and Payroll worker data.<br /> | BASIC TABLE |
| [HR_AUTOCOMPENSATIONINCREASES](HR_AUTOCOMPENSATIONINCREASES.md) | 23 | Automatic compensation increases - This table is useful to store the next increase amount when the points value is achieved at the expected increase date.<br /> | BASIC TABLE |
| [TF_TENANT_CONTEXT_ITEMS](TF_TENANT_CONTEXT_ITEMS.md) | 15 |  | BASIC TABLE |
| [TF_WFRT_DRAFTS](TF_WFRT_DRAFTS.md) | 17 |  | BASIC TABLE |
| [TF_NLP_PROVIDERS](TF_NLP_PROVIDERS.md) | 19 | Natural Language Processing Providers - Natural Language Processing Providers<br /> | BASIC TABLE |
| [TF_TEXT_RESOURCES_VIEW](TF_TEXT_RESOURCES_VIEW.md) | 7 |  | VIEW |
| [HR_SALREVGUIDELINERANGES](HR_SALREVGUIDELINERANGES.md) | 16 | Salary Review Guideline Ranges - It’s the suggested salary increase range, from min to max.<br /> | BASIC TABLE |
| [TF_CALENDAR_RESOURCE_TYPES](TF_CALENDAR_RESOURCE_TYPES.md) | 30 | Calendar Resource Types - TF_CALENDAR_RESOURCE_TYPES<br /> | BASIC TABLE |
| [HR_JOBGRID](HR_JOBGRID.md) | 17 | Job Grid - This entity allows defining the association between the job and grids that should be used during the job suitability assessment.<br /> | BASIC TABLE |
| [HR_PERSONSOCIALNETWORKS](HR_PERSONSOCIALNETWORKS.md) | 15 | Social Media Information - List of Social Media by which the person can be contacted (example: facebook, Twitter etc.). | BASIC TABLE |
| [HR_GRIEVANCES](HR_GRIEVANCES.md) | 25 | Grievances - List of grievances raised against a Person, in relation to behaviors, procedures or disciplinary actions.<br /> | BASIC TABLE |
| [HR_PAYSLIPSLAVEFLOW](HR_PAYSLIPSLAVEFLOW.md) | 26 | Payroll Data Flow - This entity will store the detail of employment payment sourced by a master payroll system.<br /> | BASIC TABLE |
| [HR_COURSEJOB](HR_COURSEJOB.md) | 13 | Suggested Course Jobs - This entity contains jobs suggested for the course.<br /> | BASIC TABLE |
| [TF_DW_INTENTS](TF_DW_INTENTS.md) | 63 | Intents - Intents<br /> | BASIC TABLE |
| [HR_RECRUITMENTREQUEST](HR_RECRUITMENTREQUEST.md) | 30 | Recruitment Request - Details the request for new hires, like the Job the candidate profile, headcount and expected hiring date.<br /> | BASIC TABLE |
| [HR_WORKLOCATIONASSIGNMENT](HR_WORKLOCATIONASSIGNMENT.md) | 22 | Work Location Assignment - Indicates the Working Location, which does not necessarily correspond to the Contract Location.<br /> | BASIC TABLE |
| [HR_TIMETRACKERPROJECT](HR_TIMETRACKERPROJECT.md) | 27 | Time Tracker Project - Time Tracker Project<br /> | BASIC TABLE |
| [HR_PARTYTYPE](HR_PARTYTYPE.md) | 25 | Party Type - This Entity represents all Types of Parties. Organizational Units, Legal entities etc, are Types of Party.<br /> | BASIC TABLE |
| [HR_COMPANYASSIGNMENT](HR_COMPANYASSIGNMENT.md) | 20 | Company Assignment - Contains the information about the Companies assigned to an employee during his contract.<br /> | BASIC TABLE |
| [TF_SECCONDITION_VALUES](TF_SECCONDITION_VALUES.md) | 10 | Security Condition Values - Security Condition Values<br /> | BASIC TABLE |
| [TF_BLRELATIONS](TF_BLRELATIONS.md) | 22 |  | BASIC TABLE |
| [TF_WFDELEGATIONS](TF_WFDELEGATIONS.md) | 25 | Workflow delegations - The workflow delegations.<br /> | BASIC TABLE |
| [TF_DWINTENT_EXECINTENT_LOGS](TF_DWINTENT_EXECINTENT_LOGS.md) | 20 | Intent Execution Logs - Digital Workplace Intent Execution Logs<br /> | BASIC TABLE |
| [HR_REMUNERATIONPOINTSROWS](HR_REMUNERATIONPOINTSROWS.md) | 14 | Compensation in points rows - Defines the rows of the pay grid in points<br /> | BASIC TABLE |
| [TF_PLACEHOLDERS](TF_PLACEHOLDERS.md) | 12 | Placeholders - Placeholders<br /> | BASIC TABLE |
| [TF_SIGN_CERTIFICATES](TF_SIGN_CERTIFICATES.md) | 19 | Sign Certificates - Sign Certificates<br /> | BASIC TABLE |
| [HR_TRAININGPOOL](HR_TRAININGPOOL.md) | 23 | Training Pool - This entity contains the training pool related to a training plan.<br /> | BASIC TABLE |
| [HR_APPRAISAL](HR_APPRAISAL.md) | 20 | Appraisal - Appraisal<br /> | BASIC TABLE |
| [TF_ASSISTANT_INTENTS](TF_ASSISTANT_INTENTS.md) | 24 | Assistant intents entity - Assistant intents<br /> | BASIC TABLE |
| [TF_QST_QUESTION_TYPES](TF_QST_QUESTION_TYPES.md) | 15 | Question types - Question types<br /> | BASIC TABLE |
| [HR_APPRGUIDELINEDETAIL](HR_APPRGUIDELINEDETAIL.md) | 16 | Appraisal Guideline Details - This entity includes the definition of all the payout thresholds.<br /> | BASIC TABLE |
| [TF_TASKS_LOGGER](TF_TASKS_LOGGER.md) | 19 | Tasks Logger - TF_TASKS_LOGGER<br /> | BASIC TABLE |
| [TF_EVENT_ACTIONS](TF_EVENT_ACTIONS.md) | 16 | Event Actions - The Event Actions.<br /> | BASIC TABLE |
| [V_ORGANIZATIONREPORTS](V_ORGANIZATIONREPORTS.md) | 18 |  | VIEW |
| [HR_ORGUNITATTRIBUTES](HR_ORGUNITATTRIBUTES.md) | 21 | Organizational Unit Attributes - Contains required details about the properties of the organizational unit.<br /> | BASIC TABLE |
| [HR_LOCATIONCONTACTS](HR_LOCATIONCONTACTS.md) | 18 | Location Contacts - List of people (and their details) to contact for the location.<br /> | BASIC TABLE |
| [HR_COMPANYRELATIONSHIP](HR_COMPANYRELATIONSHIP.md) | 47 | Company Relationship - Provides key information about an employment contract associated with a staffing assignment or staffing resource.<br /> | BASIC TABLE |
| [V_OTHERSTRUCTREPORTS](V_OTHERSTRUCTREPORTS.md) | 18 |  | VIEW |
| [TF_LINK_CATALOG](TF_LINK_CATALOG.md) | 15 | Link Catalog - The link catalog list<br /> | BASIC TABLE |
| [TF_UI_APP_SCRIPT_PHASES](TF_UI_APP_SCRIPT_PHASES.md) | 11 | Application Script Phases - Application Script Phases<br /> | BASIC TABLE |
| [HR_EXCHANGERATES](HR_EXCHANGERATES.md) | 18 | Exchange Rates - A dated list of exchange rates<br /> | BASIC TABLE |
| [TF_EPR_USER_PACKAGES](TF_EPR_USER_PACKAGES.md) | 11 | User Packages - It associates a package with the users who are developing it<br /> | BASIC TABLE |
| [HR_STAGING_PAYLOAD_DURATIONS](HR_STAGING_PAYLOAD_DURATIONS.md) | 12 | Staging Payload Retention Rules - List of retention policies, expressed in days, for a given flow code.<br /> | BASIC TABLE |
| [V_PERSONTOPERSON](V_PERSONTOPERSON.md) | 18 |  | VIEW |
| [TF_ENTITY_HISTORY](TF_ENTITY_HISTORY.md) | 5 |  | BASIC TABLE |
| [HR_CONTRACTASSIGNMENT](HR_CONTRACTASSIGNMENT.md) | 21 | Contract Assignment - Identifies attributes of a Company Relationship like the Collective Contract Agreement and the compensation Level.<br /> | BASIC TABLE |
| [HR_ADMINEVENTHEADER](HR_ADMINEVENTHEADER.md) | 22 | Administrative Event Header - Administrative Event Header.<br /> | BASIC TABLE |
| [TF_BLCS_CUSTOM](TF_BLCS_CUSTOM.md) | 16 |  | BASIC TABLE |
| [TF_MATRIX_GUIDELINES_RANGES](TF_MATRIX_GUIDELINES_RANGES.md) | 21 | Matrix Guidelines Ranges - Matrix Guidelines Ranges<br /> | BASIC TABLE |
| [V_POSITIONREPORTS](V_POSITIONREPORTS.md) | 18 |  | VIEW |
| [TF_TENANT_CONTEXT](TF_TENANT_CONTEXT.md) | 9 | Tenant Context - Tenant Context<br /> | BASIC TABLE |
| [TF_INDEX_FIELDS](TF_INDEX_FIELDS.md) | 12 | Index Fields - TF_INDEX_FIELDS<br /> | BASIC TABLE |
| [TF_FONTS_FALLBACK](TF_FONTS_FALLBACK.md) | 15 |  | BASIC TABLE |
| [HR_PLANOUTLINE](HR_PLANOUTLINE.md) | 27 | Individual Plan Outline - List of the individual activities that make up an individual plan.<br /> | BASIC TABLE |
| [HR_CHARTER_PRINT_PREFERENCES](HR_CHARTER_PRINT_PREFERENCES.md) | 23 | Charter print preferences - Allows to specify different print preferences of the charter.<br /> | BASIC TABLE |
| [HR_SALARYLINE](HR_SALARYLINE.md) | 25 | Salary Lines - Use this entity to store salary benchmarks useful for analysing your employee’s salaries against recommended market guidelines or internal policies.<br /> | BASIC TABLE |
| [TEAMHISTORY_VIEW](TEAMHISTORY_VIEW.md) | 19 | Team History View - This entity displays all the team members for a manager between specific dates.<br /> | VIEW |
| [TF_WFPROCESSES](TF_WFPROCESSES.md) | 56 | Processes - Workflow Processes View<br /> | BASIC TABLE |
| [TF_TRANSLATION_BCK](TF_TRANSLATION_BCK.md) | 17 |  | BASIC TABLE |
| [TESTIMONIALUSERS_VIEW](TESTIMONIALUSERS_VIEW.md) | 7 |  | VIEW |
| [HR_PARTY](HR_PARTY.md) | 82 | Party - A generic Item that can be represented in a Structure.<br /> | BASIC TABLE |
| [TF_ENTITY_HISTORY_DETAILS](TF_ENTITY_HISTORY_DETAILS.md) | 6 |  | BASIC TABLE |
| [HR_SCORECOMPONENTPROFILE](HR_SCORECOMPONENTPROFILE.md) | 21 | Score Component Profile - This entity collects all individual scores for each component from submitted Summary Reviews.<br /> | BASIC TABLE |
| [TF_AI_MODEL_PROVIDERS](TF_AI_MODEL_PROVIDERS.md) | 17 | AI Model Providers - AI Model Providers<br /> | BASIC TABLE |
| [HR_WORKSCHEDULEASSIGNMENT](HR_WORKSCHEDULEASSIGNMENT.md) | 29 | Work Schedule Assignment - Is the Working Time Pattern to which an employee is assigned. Also indicates their FTE %.<br /> | BASIC TABLE |
| [TF_NOTIFICATION](TF_NOTIFICATION.md) | 47 | The Notifications. - Notifications<br /> | BASIC TABLE |
| [HR_TIMESHEETDAYACTIVITIES](HR_TIMESHEETDAYACTIVITIES.md) | 20 | Timesheet Day Activities - The timesheet day activities entity.<br /> | BASIC TABLE |
| [HR_PERSONACCOUNTABILITY](HR_PERSONACCOUNTABILITY.md) | 19 | Person Accountabilities - This Entity represents "Relationships" between persons. Used for example to represent an alternative Person to Person reporting structure.<br /> | BASIC TABLE |
| [TF_CODES](TF_CODES.md) | 87 |  | BASIC TABLE |
| [HR_ABSACCRUALPROJ_VIEW](HR_ABSACCRUALPROJ_VIEW.md) | 3 | Accural Projection - This entity calculates the projection amount useful for the accrual calculation engine<br /> | VIEW |
| [HR_JOBGRIDCOMP](HR_JOBGRIDCOMP.md) | 14 | Job Grid Competency - This entity collects the grid competencies associated to a job.<br /> | BASIC TABLE |
| [TF_SECCUSTOM_STATEMENTS](TF_SECCUSTOM_STATEMENTS.md) | 19 |  | BASIC TABLE |
| [TF_BATCH_RULES](TF_BATCH_RULES.md) | 19 | Handlers - Batch Rules<br /> | BASIC TABLE |
| [TF_SAFE_API_CATALOG](TF_SAFE_API_CATALOG.md) | 19 | Safe API catalog - Catalog of safe web address to support API call within scripts<br /> | BASIC TABLE |
| [HR_APPRAISALREVIEWCOMP_VIEW](HR_APPRAISALREVIEWCOMP_VIEW.md) | 25 |  | VIEW |
| [HR_COURSEOUTLINE](HR_COURSEOUTLINE.md) | 29 | Course Outline - This entity contains the activities related to a course.<br /> | BASIC TABLE |
| [TF_WFSTAGES_CONTEXTS](TF_WFSTAGES_CONTEXTS.md) | 10 | Workflow Stages Contexts - TF_WFSTAGES_CONTEXTS<br /> | BASIC TABLE |
| [HR_APPRAISALREVIEWMATRIX_VIEW](HR_APPRAISALREVIEWMATRIX_VIEW.md) | 42 | Scores Matrix - With this entity, you can access all individual performance scores between two dates for a Person, across two set of columns representing X Score and Y Score. This entity is suitable to be used in a Matrix Wizard to create, for example, 9 box analytics.<br /> | VIEW |
| [HR_TRAININGREQUESTCOSTS](HR_TRAININGREQUESTCOSTS.md) | 22 | Training Request Costs - This entity contains the costs related to a training request.<br /> | BASIC TABLE |
| [TF_PROFILE_CONTEXT](TF_PROFILE_CONTEXT.md) | 10 | Profile context - TF_PROFILE_CONTEXT<br /> | BASIC TABLE |
| [HR_COMPANYATTRIBUTES](HR_COMPANYATTRIBUTES.md) | 29 | Company Attributes - Contains required details about the properties of the company.<br /> | BASIC TABLE |
| [HR_INDIVIDUALPLAN](HR_INDIVIDUALPLAN.md) | 33 | Individual Plan - Container of people who will be given activities to be completed.<br /> | BASIC TABLE |
| [HR_CALIBRATIONPOOL_STATS](HR_CALIBRATIONPOOL_STATS.md) | 3 |  | VIEW |
| [TF_ENTITYSET_DETAILS](TF_ENTITYSET_DETAILS.md) | 10 | Entity Set Details - TF_ENTITYSET_DETAILS<br /> | BASIC TABLE |
| [TF_QST_QUESTIONS](TF_QST_QUESTIONS.md) | 37 | Questions Definitions - Questions Definitions<br /> | BASIC TABLE |
| [HR_APPRINFORMEDREVIEWER](HR_APPRINFORMEDREVIEWER.md) | 17 | Appraisal Informed Reviewer - This entity contains information about the appraisal informed reviewer.<br /> | BASIC TABLE |
| [TF_CALENDAR_BHOURS_TYPES](TF_CALENDAR_BHOURS_TYPES.md) | 16 | Calendar Business Hours Types - TF_CALENDAR_BHOURS_TYPES<br /> | BASIC TABLE |
| [HR_TIMETRACKERCUSTOMER](HR_TIMETRACKERCUSTOMER.md) | 22 | Customers - A collection of customers<br /> | BASIC TABLE |
| [HR_CANDIDATE_VIEW](HR_CANDIDATE_VIEW.md) | 53 |  | VIEW |
| [HR_ORGUNITCONTACTS](HR_ORGUNITCONTACTS.md) | 18 | Organizational Unit Contacts - List of people (and their details) to contact for the organizational unit.<br /> | BASIC TABLE |
| [HR_LOCATIONSINCOMPANY](HR_LOCATIONSINCOMPANY.md) | 19 | Locations in Company - This Entity represents the hierarchical dependency of Locations with a Company.<br /> | BASIC TABLE |
| [TF_WFRT_LOGS](TF_WFRT_LOGS.md) | 21 |  | BASIC TABLE |
| [HR_TRAININGREQUEST](HR_TRAININGREQUEST.md) | 36 | Training Request - description of entity training request<br /> | BASIC TABLE |
| [TF_EVENT_FOLLOWUP_OUTPARAM](TF_EVENT_FOLLOWUP_OUTPARAM.md) | 15 | Event Followup Output Parameters - The Event Followup Output Parameters.<br /> | BASIC TABLE |
| [HR_CYCLEREVIEWERROLES](HR_CYCLEREVIEWERROLES.md) | 25 | Cycle Reviewers Roles - This entity contains the evaluation roles that will be involved for the specific cycle. For example: Peer, Manager and so on. | BASIC TABLE |
| [HR_EXTERNALFACT](HR_EXTERNALFACT.md) | 27 | External Fact - Use this catalogue to load external Facts, typically quantities, scores or amounts, optionally broken down by various HR dimensions (Company, Location, Job…). External data can be used for As Is analysis.<br /> | BASIC TABLE |
| [HR_STAGING_PAYROLL_ANALYTIC](HR_STAGING_PAYROLL_ANALYTIC.md) | 17 | External Payroll Person Analytics - Staging table for comparison between Core and Payroll person data.<br /> | BASIC TABLE |
| [HR_COSTBYLEARNER_VIEW](HR_COSTBYLEARNER_VIEW.md) | 11 |  | VIEW |
| [TF_DATASOURCES](TF_DATASOURCES.md) | 22 | Data Sources - Data Sources<br /> | BASIC TABLE |
| [TF_UI_APP_SCRIPTS](TF_UI_APP_SCRIPTS.md) | 14 | Application Scripts - Application Scripts<br /> | BASIC TABLE |
| [HR_COSTBYTRAININGREQUEST_VIEW](HR_COSTBYTRAININGREQUEST_VIEW.md) | 11 |  | VIEW |
| [TF_LINKGROUPS](TF_LINKGROUPS.md) | 18 | Link Configurations View - TF_LINKGROUPS<br /> | BASIC TABLE |
| [HR_ABSENCEATTENDANCE](HR_ABSENCEATTENDANCE.md) | 17 | Time and Attendance Data - Use this entity to load using an SDL or a SOA flow actual Attendance (and Absence) data already processed by a Payroll.<br /> | BASIC TABLE |
| [HR_CONTRACTLEVELATTRIBUTES](HR_CONTRACTLEVELATTRIBUTES.md) | 27 | Contract Level Attributes - Contains required details about the properties of the contract level.<br /> | BASIC TABLE |
| [TF_MCP_TOOLS](TF_MCP_TOOLS.md) | 18 | MCP Tools - MCP tools available in HCM<br /> | BASIC TABLE |
| [HR_INDIVIDUALSCORESBYCOMP_VIEW](HR_INDIVIDUALSCORESBYCOMP_VIEW.md) | 20 |  | VIEW |
| [TF_TENANT_PROPERTIES](TF_TENANT_PROPERTIES.md) | 17 | Tenant Properties - TF_TENANT_PROPERTIES<br /> | BASIC TABLE |
| [HR_APP_PROPERTIES](HR_APP_PROPERTIES.md) | 15 | Application Properties - Application Properties<br /> | BASIC TABLE |
| [HR_POOLACCOUNTABILITY](HR_POOLACCOUNTABILITY.md) | 19 | Salary Program Pool to Salary Program Pool  Accountabilities - This Entity represents the hierarchical relationship between Salary pool in the same Group. Used for example to represent a relationship between pools.<br /> | BASIC TABLE |
| [TF_BLCS](TF_BLCS.md) | 16 |  | BASIC TABLE |
| [HR_FAMILYANDDEPENDENTS](HR_FAMILYANDDEPENDENTS.md) | 44 | Family and Dependents - People who have been nominated as Family Members or other Dependents<br /> | BASIC TABLE |
| [HR_SIMULATIONSCENARIOS](HR_SIMULATIONSCENARIOS.md) | 32 | Simulation Scenario - A Scenario is a container of Participants including a selection of attributes, valid at a snapshot date and possibly effective dated hypothesis of change.<br /> | BASIC TABLE |
| [HR_INDIVIDUALSCORESMATRIX_VIEW](HR_INDIVIDUALSCORESMATRIX_VIEW.md) | 33 | Individual Scores Matrix - Individual Scores Matrix Description<br /> | VIEW |
| [TF_INTEROP_SCENARIOS](TF_INTEROP_SCENARIOS.md) | 21 | Interoperability Scenarios - Interoperability Scenarios<br /> | BASIC TABLE |
| [TF_DW_INTENT_CHANNELS](TF_DW_INTENT_CHANNELS.md) | 11 | Intent enabled channels - Intent enabled channels<br /> | BASIC TABLE |
| [TF_BLRULE_CATALOG](TF_BLRULE_CATALOG.md) | 18 | BL Rule Catalog - BL Rule Catalog<br /> | BASIC TABLE |
| [TF_SOA_LOGS](TF_SOA_LOGS.md) | 10 | SOA Logs - SOA Logs<br /> | BASIC TABLE |
| [TF_EVENT_FOLLOWUP_TYPES](TF_EVENT_FOLLOWUP_TYPES.md) | 27 | Event Followup Types - The Types of the Event Followup.<br /> | BASIC TABLE |
| [HR_JOBVACKANBANSTEPS](HR_JOBVACKANBANSTEPS.md) | 18 | Job Vacancy Outline Steps visible in the Kanban Board - Job vacancy outline steps visible as Kanban Board status.<br /> | VIEW |
| [HR_ACCOUNTABILITY](HR_ACCOUNTABILITY.md) | 18 | Accountability - This entity represents a relationship between two items.<br /> | BASIC TABLE |
| [TF_TASKS_LOGGER_DETAILS](TF_TASKS_LOGGER_DETAILS.md) | 17 | Tasks Logger Details - TF_TASKS_LOGGER_DETAILS<br /> | BASIC TABLE |
| [TF_DATA_LOADER_TEXT_EXPORT](TF_DATA_LOADER_TEXT_EXPORT.md) | 2 |  | BASIC TABLE |
| [HR_KANBANBOARD_SELSTEP](HR_KANBANBOARD_SELSTEP.md) | 35 | Details of the selection step in the Kanban Board - Details of the Selection Step in the Kanban Board.<br /> | VIEW |
| [HR_SCORMREGISTRATIONS](HR_SCORMREGISTRATIONS.md) | 14 | Scorm Cloud Registrations - description of  entity Scorm Cloud Registrations<br /> | BASIC TABLE |
| [HR_WTP_TOLERANCE](HR_WTP_TOLERANCE.md) | 18 | Working Time Patterns Tolerance - Working Time Pattern Tolerance for Clock In<br /> | BASIC TABLE |
| [TF_WFDELEGATION_ITEMS](TF_WFDELEGATION_ITEMS.md) | 12 | Process categories - The process categories.<br /> | BASIC TABLE |
| [HR_BENCHMARKLINE](HR_BENCHMARKLINE.md) | 13 | Benchmark Line - A benchmark line is the associative of a simulation scenario and a salary line<br /> | BASIC TABLE |
| [HR_CANDIDATE_CV_RX](HR_CANDIDATE_CV_RX.md) | 26 | Candidate's Curriculum Attachment - The Candidate's Curriculum Attachment<br /> | VIEW |
| [TF_MODULES](TF_MODULES.md) | 15 | Modules - Licensed modules<br /> | BASIC TABLE |
| [TF_DEFAULT_ENTITIES_PARAMS](TF_DEFAULT_ENTITIES_PARAMS.md) | 10 | Default Entities Params - Default Entities Params<br /> | BASIC TABLE |
| [HR_OUCURRENTFIRSTLEVELS_VIEW](HR_OUCURRENTFIRSTLEVELS_VIEW.md) | 14 | Organisational Unit First Levels - Reports the Org. Units in the first "n" levels of the current version of the Organisational structure<br /> | VIEW |
| [HR_COURSEPREREQUIREMENTS](HR_COURSEPREREQUIREMENTS.md) | 20 | Course Prerequirements - Contains the course prerequirements.<br /> | BASIC TABLE |
| [TF_WFSTAGES_ROLES_CATEGORIES](TF_WFSTAGES_ROLES_CATEGORIES.md) | 16 | Workflow Stages Roles Categories - Workflow Stages Roles Categories<br /> | BASIC TABLE |
| [HR_JOBGRIDCOMPGAP](HR_JOBGRIDCOMPGAP.md) | 14 | Job Grid expected competency proficiency  - This entity enables a user to set a gap value from the expected proficiency for the competencies associated to the job grid. The value zero (0) indicates it is the expected proficiency.<br /> | BASIC TABLE |
| [TF_GENERIC_ENTITIES](TF_GENERIC_ENTITIES.md) | 108 |  | BASIC TABLE |
| [HR_COMPANYCONTACTS](HR_COMPANYCONTACTS.md) | 18 | Company Contacts - List of people (and their details) to contact for the company.<br /> | BASIC TABLE |
| [HR_INDIVIDUALPLANENROLMENT](HR_INDIVIDUALPLANENROLMENT.md) | 36 | Individual Plan Enrolment - Enrolment of a person to an individual plan.<br /> | BASIC TABLE |
| [HR_TIMETRACKERPROJ_ACTIVITY](HR_TIMETRACKERPROJ_ACTIVITY.md) | 13 | Time Tracker Project Activities - This entity links the Time Tracker Projects and Activities<br /> | BASIC TABLE |
| [HR_CHARTERPERSPECTIVEITEM](HR_CHARTERPERSPECTIVEITEM.md) | 21 | Charter Perspective Item - Charter Perspective Item<br /> | BASIC TABLE |
| [HR_SELSTEPSHORTLISTSTEP](HR_SELSTEPSHORTLISTSTEP.md) | 15 | Step Type of the Selection Process visible in the Kanban Board - Step Type of the Selection Process visible in the Kanban Board<br /> | VIEW |
| [TF_ENUMS](TF_ENUMS.md) | 11 |  | BASIC TABLE |
| [TF_CALENDAR_DEFAULT_BHOURS](TF_CALENDAR_DEFAULT_BHOURS.md) | 18 | Calendar Default Business Hours - TF_CALENDAR_DEFAULT_BHOURS<br /> | BASIC TABLE |
| [HR_REQUESTCOSTFINANCING](HR_REQUESTCOSTFINANCING.md) | 20 | Request Costs Financing - Contains the financed costs about training request.<br /> | BASIC TABLE |
| [HR_STAGING_PAYROLL_CONTRACT](HR_STAGING_PAYROLL_CONTRACT.md) | 17 |  | BASIC TABLE |
| [HR_TEAMRATINGCOMPETENCIES](HR_TEAMRATINGCOMPETENCIES.md) | 9 | Competencies to be assessed of a Team - Competencies to be assessed of a Team<br /> | VIEW |
| [HR_OTHERCOMPETENCIES](HR_OTHERCOMPETENCIES.md) | 13 | Other personal competencies - List of additional skills held by the person.<br /> | BASIC TABLE |
| [TF_FUNC_AREA_CUSTOM_AUTH](TF_FUNC_AREA_CUSTOM_AUTH.md) | 11 | TF_PROFILE_CUSTOM_AUTH - TF_PROFILE_CUSTOM_AUTH<br /> | BASIC TABLE |
| [TF_WFRT_PROCESSES_ENTITIES](TF_WFRT_PROCESSES_ENTITIES.md) | 18 | Process Person - Workflow runtime process person view<br /> | BASIC TABLE |
| [TF_SOAINCLUDES](TF_SOAINCLUDES.md) | 14 | SOA Includes - SOA Includes<br /> | BASIC TABLE |
| [TF_EVENT_SUBSCRIPTION_RULES](TF_EVENT_SUBSCRIPTION_RULES.md) | 17 | Event Subscription Rules - The Event Subscription Rules.<br /> | BASIC TABLE |
| [TF_SECDIMENSION_EXCLUSIONS](TF_SECDIMENSION_EXCLUSIONS.md) | 10 | Security Dimension Exclusions - TF_SECDIMENSION_EXCLUSIONS<br /> | BASIC TABLE |
| [HR_PERSONADDRESSES](HR_PERSONADDRESSES.md) | 32 | Address - Provides the information about the address or semantic address of an associated entity<br /> | BASIC TABLE |
| [TF_BATCH_QUEUES](TF_BATCH_QUEUES.md) | 16 | Batch queues - Batch queues<br /> | BASIC TABLE |
| [TF_SCHEDULES](TF_SCHEDULES.md) | 14 |  | BASIC TABLE |
| [TF_CODIFICATIONS_CONTEXTS](TF_CODIFICATIONS_CONTEXTS.md) | 10 |  | BASIC TABLE |
| [HR_TEAMRATINGQUESTIONS](HR_TEAMRATINGQUESTIONS.md) | 18 | Questions for evaluating a Team - Questions for evaluating a Team<br /> | VIEW |
| [HR_OBJECTIVETEMPLATE](HR_OBJECTIVETEMPLATE.md) | 22 | Objective Template - Objective templates are examples/models that a user can start from when creating an Objective in a plan.<br /> | BASIC TABLE |
| [HR_CONTRACTTYPEASSIGNMENT](HR_CONTRACTTYPEASSIGNMENT.md) | 24 | Contract Type Assignment - Specifies the nature of the contract for an Employee, for example if it is Permanent or not.<br /> | BASIC TABLE |
| [HR_CYCLEPARTICIPANT](HR_CYCLEPARTICIPANT.md) | 17 | Cycle Participant - Contains the participants, meaning people evaluated, of an appraisal cycle.<br /> | BASIC TABLE |
| [HR_BENEFITSASSIGNMENT](HR_BENEFITSASSIGNMENT.md) | 29 | Benefits Assignment - Contains details of a benefit including the amount, interval and other related information.<br /> | BASIC TABLE |
| [HR_TIMESHEETDAYKPI](HR_TIMESHEETDAYKPI.md) | 5 |  | VIEW |
| [HR_V_JOBOUTANDSELSTEPS](HR_V_JOBOUTANDSELSTEPS.md) | 11 |  | VIEW |
| [TF_LINKS](TF_LINKS.md) | 20 | Linkgroups - TF_LINKS<br /> | BASIC TABLE |
| [TF_ASSISTANT_RTPARAMS](TF_ASSISTANT_RTPARAMS.md) | 29 | Assistant intent runtime params entity - The entity that manage runtime parameters of each intent.<br /> | BASIC TABLE |
| [HR_CALENDAR](HR_CALENDAR.md) | 15 | Calendar - Calendar Entity<br /> | BASIC TABLE |
| [HR_CANDIDATE](HR_CANDIDATE.md) | 50 | External Candidate - External Candidate Entity.<br /> | BASIC TABLE |
| [HR_LEARNER](HR_LEARNER.md) | 43 | Learner - This is the entity representing a person enrolled or candidate to a course.<br /> | BASIC TABLE |
| [HR_FAMILYANDDEPENDENTATTRS](HR_FAMILYANDDEPENDENTATTRS.md) | 20 | Family and Dependents Attributes - The attributes of Family Members or other Dependents<br /> | BASIC TABLE |
| [HR_V_Z_MASTERRECORD](HR_V_Z_MASTERRECORD.md) | 24 |  | VIEW |
| [TF_ROLE_CATALOG](TF_ROLE_CATALOG.md) | 14 | Role Catalog - TF_ROLE_CATALOG<br /> | BASIC TABLE |
| [HR_MAPPINGCODES](HR_MAPPINGCODES.md) | 15 | Mapping settings (system) - Used for sake of synchronization between HCM and Core HR.<br /> | BASIC TABLE |
| [TF_BLENTITIES_CUSTOM](TF_BLENTITIES_CUSTOM.md) | 33 |  | BASIC TABLE |
| [TF_USER_NOTIFICATIONS](TF_USER_NOTIFICATIONS.md) | 13 | User Notifications - User Notifications<br /> | BASIC TABLE |
| [HR_V_Z_MASTERRECORDHEAD](HR_V_Z_MASTERRECORDHEAD.md) | 8 |  | VIEW |
| [HR_SELECTIONPROCESSTEMPLATE](HR_SELECTIONPROCESSTEMPLATE.md) | 14 | Selection Process Template - This entity contains the selection process templates<br /> | BASIC TABLE |
| [TF_TEMP_ENTITYSET_DETAILS](TF_TEMP_ENTITYSET_DETAILS.md) | 6 |  | BASIC TABLE |
| [HR_WTPDAILYDETAILS](HR_WTPDAILYDETAILS.md) | 25 | WTP Daily Details - Contains all the daily details of a specific working time pattern.<br /> | BASIC TABLE |
| [HR_POOLAPPRAISAL](HR_POOLAPPRAISAL.md) | 13 | Pool Appraisal - Pool Appraisal consists of the relationship between Calibration Pool and Appraisal entity.<br /> | BASIC TABLE |
| [HR_V_Z_SHORTLISTEDCND](HR_V_Z_SHORTLISTEDCND.md) | 13 |  | VIEW |
| [TF_DW_INTENT_MESSAGES](TF_DW_INTENT_MESSAGES.md) | 16 | Intent action messages - Intent action messages<br /> | BASIC TABLE |
| [TF_MENU](TF_MENU.md) | 12 | Menu - Entity TF_MENU<br /> | BASIC TABLE |
| [HR_V_Z_SHORTLISTVERT](HR_V_Z_SHORTLISTVERT.md) | 10 |  | VIEW |
| [HR_ACCOUNTABILITYTYPE](HR_ACCOUNTABILITYTYPE.md) | 29 | Accountability Type - This entity represents a type of relationship between two types of items.<br /> | BASIC TABLE |
| [TF_TEXT_RESOURCES](TF_TEXT_RESOURCES.md) | 14 | Text resource - Text resource<br /> | BASIC TABLE |
| [TF_FUNCTIONAL_AREA](TF_FUNCTIONAL_AREA.md) | 16 | Functional Area - Functional area<br /> | BASIC TABLE |
| [TF_ICONS](TF_ICONS.md) | 14 | Icon - Icon<br /> | BASIC TABLE |
| [TF_DEPENDENCY_PROVIDERS](TF_DEPENDENCY_PROVIDERS.md) | 14 |  | BASIC TABLE |
| [TF_NOTIFICATION_FACTORY](TF_NOTIFICATION_FACTORY.md) | 5 |  | BASIC TABLE |
| [HR_V_Z_USERS](HR_V_Z_USERS.md) | 11 |  | VIEW |
| [TF_PROPERTY_ENUMS](TF_PROPERTY_ENUMS.md) | 10 | Property Enumerable - Property Enumerable<br /> | BASIC TABLE |
| [HR_COMPENSATION_CHANGE_LOG](HR_COMPENSATION_CHANGE_LOG.md) | 21 | Compensation Change Log - COMPENSATION_CHANGE_LOG<br /> | BASIC TABLE |
| [TF_WFPROCESS_STAGE_CONTEXTS](TF_WFPROCESS_STAGE_CONTEXTS.md) | 10 | Workflow Process Stage Contexts - Workflow Process Stage Contexts<br /> | BASIC TABLE |
| [HR_STAGING_PAYROLL_PERSON](HR_STAGING_PAYROLL_PERSON.md) | 13 | How to - How to<br /> | BASIC TABLE |
| [HR_WTPDETAILSBYPERIOD](HR_WTPDETAILSBYPERIOD.md) | 20 | Working Time Pattern Details by Period - Working Time Pattern Details by Period<br /> | VIEW |
| [HR_DAYSTIMELINE](HR_DAYSTIMELINE.md) | 15 | DAYSTIMELINE - DAYSTIMELINE<br /> | BASIC TABLE |
| [TF_EPR_FAILED_VALIDATIONS](TF_EPR_FAILED_VALIDATIONS.md) | 16 | eProvisioning Failed Validations - eProvisioning Failed Validations<br /> | BASIC TABLE |
| [HR_TIMETRACKERWORKERRATE](HR_TIMETRACKERWORKERRATE.md) | 14 | Time Tracker Worker Rate - Worker Rate for a Time Tracker Project<br /> | BASIC TABLE |
| [TF_SCRIPT_SNIPPETS](TF_SCRIPT_SNIPPETS.md) | 12 | Script Snippets - Script Snippets<br /> | BASIC TABLE |
| [TF_BLCS_VIEW](TF_BLCS_VIEW.md) | 11 | Blcs - Blcs<br /> | VIEW |
| [HR_OTHERSTRUCTASSIGNMENT](HR_OTHERSTRUCTASSIGNMENT.md) | 22 | Other Structure Assignment - Is a deployment of a employee in a Structure which is an alternative to the Organizational Structure. Used for example, to represent Deployment by Project or Deployment in Simulated Structures.<br /> | BASIC TABLE |
| [TF_TEMP_ENTITYSETS](TF_TEMP_ENTITYSETS.md) | 9 |  | BASIC TABLE |
| [HR_RESOLUTIONRULEINSTANCE](HR_RESOLUTIONRULEINSTANCE.md) | 14 | Actor Resolution Rules - This entity enables the definition of rules to calculate a user with a relationship to another person. Such rules can be used in multiple scenarios  like workflow, appraisal cycle etc.<br /> | BASIC TABLE |
| [HR_SELECTIONPROCESSTMPSTEPS](HR_SELECTIONPROCESSTMPSTEPS.md) | 21 | Selection Process Template Steps - Selection Process Template Steps<br /> | BASIC TABLE |
| [TF_SOASCHEDULES](TF_SOASCHEDULES.md) | 21 | SOA Schedules - TF_SOASCHEDULES<br /> | BASIC TABLE |
| [HR_POOLINPROGRAM](HR_POOLINPROGRAM.md) | 17 |  | BASIC TABLE |
| [HR_INDIVIDUALACTION](HR_INDIVIDUALACTION.md) | 28 | Individual Action - Individual action with a type, a completion percentage and optionally a linked Entity that can be a workflow task of a course session enrolment.<br /> | BASIC TABLE |
| [HR_PERSONALPUBLICATIONS](HR_PERSONALPUBLICATIONS.md) | 18 | Personal Publications - List of a person’s Publications such as articles, books, abstracts, etc.<br /> | BASIC TABLE |
| [TF_EVENT_RULE_CATALOG](TF_EVENT_RULE_CATALOG.md) | 25 | Event Rule Catalog - The Event Rule Catalog.<br /> | BASIC TABLE |
| [TF_BLENTITY_MR_STATES_VIEW](TF_BLENTITY_MR_STATES_VIEW.md) | 8 |  | VIEW |
| [TF_WFSTAGES_ROLES_SUBJECTS](TF_WFSTAGES_ROLES_SUBJECTS.md) | 20 | Workflow Stages Roles Subjects - Workflow Stages Roles Subjects<br /> | BASIC TABLE |
| [TF_INTEROP_RULES](TF_INTEROP_RULES.md) | 18 | Interoperability Rules - Interoperability Rules<br /> | BASIC TABLE |
| [TF_PROFILE_GRANTS](TF_PROFILE_GRANTS.md) | 15 | Profile grant - TF_PROFILE_GRANT<br /> | BASIC TABLE |
| [TF_SECFACTORY_STATEMENTS](TF_SECFACTORY_STATEMENTS.md) | 19 |  | BASIC TABLE |
| [TF_BLENTITY_STATES_VIEW](TF_BLENTITY_STATES_VIEW.md) | 13 |  | VIEW |
| [HR_DEVICEASSIGNMENT](HR_DEVICEASSIGNMENT.md) | 21 | Device Assignment - Represents the history of Device Assignments associated to a specific Employee.<br /> | BASIC TABLE |
| [HR_SELECTIONSTEP](HR_SELECTIONSTEP.md) | 28 | Selection Step - Indicates step in the selection process, for a selected candidate. Includes the date of the appointment, who will do the interview and the outcome.<br /> | BASIC TABLE |
| [TF_CALENDAR_TYPES](TF_CALENDAR_TYPES.md) | 47 | Calendar Types - TF_CALENDAR_TYPES<br /> | BASIC TABLE |
| [HR_RISKASSESSMENT](HR_RISKASSESSMENT.md) | 25 | Risk Assessment - This entity includes HR Risk annotations being them associated to a What If Scenario or not.<br /> | BASIC TABLE |
| [HR_CYCLEPARTICREVIEWER](HR_CYCLEPARTICREVIEWER.md) | 17 | Cycle Participant Reviewer - Contains reviewers/evaluators of cycle participants.<br /> | BASIC TABLE |
| [HR_CALENDARBYLOCATION](HR_CALENDARBYLOCATION.md) | 13 | Calendar by Location - This entity stores the link between a calendar and a location.<br /> | BASIC TABLE |
| [TF_COMMENTS](TF_COMMENTS.md) | 16 | Comments - The Comments.<br /> | BASIC TABLE |
| [TF_BLFIELDS_VIEW](TF_BLFIELDS_VIEW.md) | 21 | BL Fields View - Business Logic Fields View<br /> | VIEW |
| [HR_MISCEMPLTERMINDUCTIONS](HR_MISCEMPLTERMINDUCTIONS.md) | 21 | Miscellaneous Employment Terms Inductions - Contains miscellaneous employment terms inductions related to the job.<br /> | BASIC TABLE |
| [HR_ABSEVENTCOMPULSORY](HR_ABSEVENTCOMPULSORY.md) | 20 | Compulsory Absence Event - This entity contains calendar events representing compulsory holidays.<br /> | BASIC TABLE |
| [HR_CORESLAVEANALYTICS](HR_CORESLAVEANALYTICS.md) | 12 | Core Slave Analytics - This entity is a container for Analytics build from IP Data.<br /> | BASIC TABLE |
| [HR_JOBVACANCY](HR_JOBVACANCY.md) | 59 | Job Vacancy - Includes the Job, the candidate ideal profile, the text of the advert, economical and contractual conditions offered, Job location etc.<br /> | BASIC TABLE |
| [TF_NOTIFICATION_TARGET](TF_NOTIFICATION_TARGET.md) | 14 | Notification Target - Notification Target<br /> | BASIC TABLE |
| [HR_CHARTERTEMPLATES](HR_CHARTERTEMPLATES.md) | 14 | Charter Templates - Charter Templates<br /> | BASIC TABLE |
| [TF_BATCHES](TF_BATCHES.md) | 42 | Batches - Batches<br /> | BASIC TABLE |
| [HR_FEEDBACK](HR_FEEDBACK.md) | 25 | Received Feedback - This entity contains feedback received.<br /> | BASIC TABLE |
| [TF_BLPROPERTY_EXCEPTIONS_VIEW](TF_BLPROPERTY_EXCEPTIONS_VIEW.md) | 13 |  | VIEW |
| [TF_QST_ANSWERS](TF_QST_ANSWERS.md) | 22 | Answers Definitions - Answers Definitions<br /> | BASIC TABLE |
| [HR_Z_FLOWDEFINITION](HR_Z_FLOWDEFINITION.md) | 20 | Zucchetti Flow Definition - Dictionary containing mappings between Zucchetti and HCM fields.<br /> | BASIC TABLE |
| [TF_BLRELATIONS_VIEW](TF_BLRELATIONS_VIEW.md) | 18 | Business Logic Relations View - Business Logic Relations View<br /> | VIEW |
| [HR_SALARYDIMENSION](HR_SALARYDIMENSION.md) | 21 | Salary Analysis Dimensions - This entity catalogues all dimensions you can use in Scenarios typed “Salary Analysis” to cluster specific salaries by specific employment dimensions.<br /> | BASIC TABLE |
| [TF_WFRT_SIGN_REQUESTS](TF_WFRT_SIGN_REQUESTS.md) | 17 | E-Signature Requests - This entity includes all e-Signature packages created/initialized by a Workflow Process.<br /> | BASIC TABLE |
| [TF_BLRULES_VIEW](TF_BLRULES_VIEW.md) | 19 | Rules - Rules<br /> | VIEW |
| [HR_ACCOUNTABILITYTYPEDIR](HR_ACCOUNTABILITYTYPEDIR.md) | 16 | Accountability Type Directives - Accountability Type Directives<br /> | BASIC TABLE |
| [TF_ASSISTANT_INTENT_RTPARAMS](TF_ASSISTANT_INTENT_RTPARAMS.md) | 14 | Assistant runtime params - Runtime Parameter<br /> | BASIC TABLE |
| [HR_APPLICANT](HR_APPLICANT.md) | 27 | Applicant - It’s an application for a vacancy by a candidate, regardless if internal or external.<br /> | BASIC TABLE |
| [TF_EVENT_SUBSCRIPTIONS](TF_EVENT_SUBSCRIPTIONS.md) | 12 | Event Subscriptions - The Event Subscriptions.<br /> | BASIC TABLE |
| [TF_WFSTAGES](TF_WFSTAGES.md) | 26 | Workflow Stages - Workflow Stages<br /> | BASIC TABLE |
| [TF_MENU_CFGS](TF_MENU_CFGS.md) | 13 | Log Layers - Entity TF_MENU_CFGS<br /> | BASIC TABLE |
| [TF_DATADICTIONARY_EXPLORER](TF_DATADICTIONARY_EXPLORER.md) | 16 | Data Dictionary Explorer   - TF_DATADICTIONARY_EXPLORER<br /> | VIEW |
| [TF_LINK_CFGS](TF_LINK_CFGS.md) | 18 | Landing Topics - TF_LINK_CFGS<br /> | BASIC TABLE |
| [HR_SESSIONCOSTS](HR_SESSIONCOSTS.md) | 21 | Session Costs - Session Costs<br /> | BASIC TABLE |
| [TF_SECFILTER_CATALOG](TF_SECFILTER_CATALOG.md) | 12 | Security Filter Catalog - Security Filter Catalog<br /> | BASIC TABLE |
| [HR_SESSIONOUTLINE](HR_SESSIONOUTLINE.md) | 45 | Session Content - This entity contains the session content / activities.<br /> | BASIC TABLE |
| [HR_STRUCTURELOG](HR_STRUCTURELOG.md) | 34 | Export Structure - Export changes of structure<br /> | BASIC TABLE |
| [TF_DW_COMPPROMPTS_LKPVIEW](TF_DW_COMPPROMPTS_LKPVIEW.md) | 30 | Lookup LLM Completion Resources - Lookup LLM Completion Resources<br /> | VIEW |
| [TF_EPR_PACKAGES](TF_EPR_PACKAGES.md) | 28 | Packages - Packages installed and in development<br /> | BASIC TABLE |
| [TF_DW_INTENT_PARAMS_PAGEKEYS](TF_DW_INTENT_PARAMS_PAGEKEYS.md) | 10 | Intent Parameter Page Keys - Intent Parameter Page Keys<br /> | BASIC TABLE |
| [TF_BLRULE_PARAMETER_CATALOG](TF_BLRULE_PARAMETER_CATALOG.md) | 17 | BL Rule Parameter Catalog - BL Rule Parameter Catalog<br /> | BASIC TABLE |
| [HR_JOBVACANCYOUTLINESTEPS](HR_JOBVACANCYOUTLINESTEPS.md) | 16 | Job Vacancy Outline Steps - In a Job Vacancy definition, the steps needed to select a candidate.<br /> | BASIC TABLE |
| [TF_SOACOMPONENTS](TF_SOACOMPONENTS.md) | 21 | SOA Component - TF_SOACOMPONENTS<br /> | BASIC TABLE |
| [TF_DOCUMENT_TEMPLATES](TF_DOCUMENT_TEMPLATES.md) | 48 | Document Template - Document Template<br /> | BASIC TABLE |
| [HR_TIMETRACKERPROJECTTEAM](HR_TIMETRACKERPROJECTTEAM.md) | 14 | Time Tracker Team - Team<br /> | BASIC TABLE |
| [TF_USER_PASSWORD_HISTORY](TF_USER_PASSWORD_HISTORY.md) | 4 |  | BASIC TABLE |
| [TF_SDL_EXECUTIONS](TF_SDL_EXECUTIONS.md) | 31 | Duration - Duration of session in seconds<br /> | BASIC TABLE |
| [TF_DW_INTENTS_VIEW](TF_DW_INTENTS_VIEW.md) | 63 | Digital Workplace Intents - Digital Workplace Intents<br /> | VIEW |
| [TF_TEMP_INDEX_OPERATIONS](TF_TEMP_INDEX_OPERATIONS.md) | 12 |  | BASIC TABLE |
| [HR_COMPENSATIONASSIGNMENT](HR_COMPENSATIONASSIGNMENT.md) | 34 | Compensation Assignment - Contains a remuneration amount and related metadata, including the interval or basis used to express the pay rate (per hour, day, week, month, etc.).<br /> | BASIC TABLE |
| [HR_POSITIONACCOUNTABILITY](HR_POSITIONACCOUNTABILITY.md) | 19 | Position to Position Accountabilies - This Entity represents "Relationships" between positions. Used for example to represent a functional structure as opposed to an Organizational Structure.<br /> | BASIC TABLE |
| [TF_DW_PUSH_NOTIFICATION_LOG](TF_DW_PUSH_NOTIFICATION_LOG.md) | 15 | Digital Workplace Push Notifications Log - This entity contains the notification log related to the Digital workplace<br /> | VIEW |
| [TF_THEME_SETTINGS](TF_THEME_SETTINGS.md) | 11 | Theme Settings - TF_THEME_SETTINGS<br /> | BASIC TABLE |
| [TF_WFRESOURCE_CATEGORIES](TF_WFRESOURCE_CATEGORIES.md) | 11 | Workflow Resource Categories - Workflow Resource Categories<br /> | BASIC TABLE |
| [HR_PERSONALTRAININGHISTORY](HR_PERSONALTRAININGHISTORY.md) | 16 | Training History - History of all relevant courses attended.<br /> | BASIC TABLE |
| [TF_ENTITYSETS_STATS_VIEW](TF_ENTITYSETS_STATS_VIEW.md) | 4 |  | VIEW |
| [HR_INDACTCHECKPOINTS](HR_INDACTCHECKPOINTS.md) | 15 | Individual Activity Checkpoints - Individual Activity Checkpoints<br /> | BASIC TABLE |
| [TF_USER_PROFILES](TF_USER_PROFILES.md) | 12 | User profiles - User profiles<br /> | BASIC TABLE |
| [TF_INTEROP_SCENARIOS_LKPVIEW](TF_INTEROP_SCENARIOS_LKPVIEW.md) | 19 | Lookup Interoperability Scenarios - Lookup Interoperability Scenarios<br /> | VIEW |
| [HR_DISCIPLINARYEVENTS](HR_DISCIPLINARYEVENTS.md) | 26 | Disciplinary Events - The list of disciplinary events recorded for a Person, including Issuing Manager and outcome.<br /> | BASIC TABLE |
| [HR_COSTCENTER](HR_COSTCENTER.md) | 23 | Cost Center - A cost center is a department within a business to which costs can be allocated.<br /> | BASIC TABLE |
| [HR_APPLICATIONSEQUENCES](HR_APPLICATIONSEQUENCES.md) | 13 | Auto Numbering's Sequences - If Null, set the FieldName parameter as the last value from correct applicationSequence in DB +1, else use the last value of the application sequence of the corresponding application sequence key name.<br /> | BASIC TABLE |
| [TF_SOATRANSFORM](TF_SOATRANSFORM.md) | 16 | SOA Transform - SOA Transform<br /> | BASIC TABLE |
| [TF_ENTITYSETS](TF_ENTITYSETS.md) | 34 | Entity Sets - TF_ENTITYSETS<br /> | BASIC TABLE |
| [HR_FEEDBACKBYSTATUS](HR_FEEDBACKBYSTATUS.md) | 16 | Feedback by Status - Feedback by Status (entity description).<br /> | BASIC TABLE |
| [TF_INTEROP_SCENARIOS_VIEW](TF_INTEROP_SCENARIOS_VIEW.md) | 20 |  | VIEW |
| [HR_OVERTIMEREQUEST](HR_OVERTIMEREQUEST.md) | 17 | Overtime Request - This entity contains data about a overtime request made from a person associated to a company relationship.<br /> | BASIC TABLE |
| [HR_ABSENCEEVENT](HR_ABSENCEEVENT.md) | 49 | Absence Event - Contains the absence events.<br /> | BASIC TABLE |
| [TF_AI_MODELS](TF_AI_MODELS.md) | 20 | AI models - AI models<br /> | BASIC TABLE |
| [HR_TRAACTIVITYTYPES](HR_TRAACTIVITYTYPES.md) | 29 | Learning Activity Types - description of entity Activity Types<br /> | BASIC TABLE |
| [TF_LINK_CFGS_VIEW](TF_LINK_CFGS_VIEW.md) | 18 | Link Configurations - TF_LINK_CFGS_VIEW<br /> | VIEW |
| [TF_WIDGETS_GALLERY_CATEGORY](TF_WIDGETS_GALLERY_CATEGORY.md) | 12 | Widgets gallery category - TF_WIDGETS_GALLERY_CATEGORY<br /> | BASIC TABLE |
| [HR_MULTIPLEXER_TYPES](HR_MULTIPLEXER_TYPES.md) | 13 | MULTIPLEXERTYPES - MULTIPLEXERTYPES DESCRIPTION<br /> | BASIC TABLE |
| [TF_INTEROP_TYPES](TF_INTEROP_TYPES.md) | 31 | Interoperability Skills - Interoperability Skill Catalog<br /> | BASIC TABLE |
| [TF_BLENTITIES](TF_BLENTITIES.md) | 33 | TF_BLENTITIES_LOOKUP - TF_BLENTITIES_LOOKUP<br /> | BASIC TABLE |
| [HR_CALIBRATIONMODEL](HR_CALIBRATIONMODEL.md) | 16 | Calibration Model - Calibration models to calculate evaluation scores based on an expected distribution<br /> | BASIC TABLE |
| [TF_COMPONENTS_CATALOG](TF_COMPONENTS_CATALOG.md) | 15 | Components Catalog - Entity TF_COMPONENTS_CATALOG<br /> | BASIC TABLE |
| [TF_LINKGROUPS_VIEW](TF_LINKGROUPS_VIEW.md) | 18 | Linksets - Linksets<br /> | VIEW |
| [HR_COURSE](HR_COURSE.md) | 47 | Course - This entity contains the catalogue of courses.<br /> | BASIC TABLE |
| [HR_SALARYGRADEASSIGNMENT](HR_SALARYGRADEASSIGNMENT.md) | 16 | Salary Grade Assignment - The history of Individual Salary Grades to which a specific worker has been assigned.<br /> | BASIC TABLE |
| [TF_PROFILE_ROLES](TF_PROFILE_ROLES.md) | 10 | Profile role - TF_PROFILE_ROLES<br /> | BASIC TABLE |
| [HR_APPRAISALFORMPAYOUT](HR_APPRAISALFORMPAYOUT.md) | 23 | Appraisal Form Payout - This entity contains the payout configuration associated with an appraisal form.<br /> | BASIC TABLE |
| [TF_WFRT_SIGN_REQUEST_SIGNERS](TF_WFRT_SIGN_REQUEST_SIGNERS.md) | 20 | E-Signature Signers - This entity aggregates information about individuals who have been invited to sign one or more documents (for ex. contact data).<br /> | BASIC TABLE |
| [TF_SECFILTER_CONTEXT](TF_SECFILTER_CONTEXT.md) | 10 | Security Filter Context - Security Filter Context<br /> | BASIC TABLE |
| [HR_APPRAISALREVIEW](HR_APPRAISALREVIEW.md) | 43 | Appraisal Review - This entity stores the history of all individual appraisals.<br /> | BASIC TABLE |
| [HR_FINANCINGORGANIZATIONS](HR_FINANCINGORGANIZATIONS.md) | 20 | Financing Organization - Contains the financing organizations.<br /> | BASIC TABLE |
| [TF_LINKS_VIEW](TF_LINKS_VIEW.md) | 20 |  | VIEW |
| [TF_OAUTH_ACTIONS](TF_OAUTH_ACTIONS.md) | 14 | OAuth Actions - OAuth Actions<br /> | BASIC TABLE |
| [HR_TRAININGCHECKLIST](HR_TRAININGCHECKLIST.md) | 20 | Training Checklist - This entity logs all activities due to setup/execute a Training Session.<br /> | BASIC TABLE |
| [TF_GENERAL_RULES](TF_GENERAL_RULES.md) | 76 | Resolution Rules - Catalogue of rules to resolve who is assigned to a specific function based on the selected person.<br /> | BASIC TABLE |
| [HR_STRUCTURESTAGINGTABLE](HR_STRUCTURESTAGINGTABLE.md) | 31 | Structure Staging Table - A staging table where Structures being imported are stored.<br /> | BASIC TABLE |
| [TF_LINKSETS_VIEW](TF_LINKSETS_VIEW.md) | 14 | Linksets - Linksets<br /> | VIEW |
| [TF_LINKSETS](TF_LINKSETS.md) | 14 | Link sets - Link sets<br /> | BASIC TABLE |
| [TF_EVENTDEF_MESSAGE_CHANNELS](TF_EVENTDEF_MESSAGE_CHANNELS.md) | 11 | Event definition message channels - Event definition message channels<br /> | BASIC TABLE |
| [HR_CALIBRATIONMODELLEVEL](HR_CALIBRATIONMODELLEVEL.md) | 16 | Calibration Model Level - Calibration Model's levels<br /> | BASIC TABLE |
| [TF_MENU_CFGS_VIEW](TF_MENU_CFGS_VIEW.md) | 13 | Menu Configurations View - TF_MENU_CFGS_VIEW<br /> | VIEW |
| [TF_QST_QUESTIONTYPE_LAYOUTS](TF_QST_QUESTIONTYPE_LAYOUTS.md) | 15 | Question type layouts - Question type layouts<br /> | BASIC TABLE |
| [TF_PROFILE_CATALOG](TF_PROFILE_CATALOG.md) | 24 | Profile catalog - TF_PROFILE_CATALOG<br /> | BASIC TABLE |
| [TF_TEMP_INDEX_DETAILS](TF_TEMP_INDEX_DETAILS.md) | 5 |  | BASIC TABLE |
| [HR_JOBVACEMPLOYMENTAGENCY](HR_JOBVACEMPLOYMENTAGENCY.md) | 13 | Job Vacancy Employment Agency - Employment agency associated with the job vacancy<br /> | BASIC TABLE |
| [HR_Z_IMPORTHEADER](HR_Z_IMPORTHEADER.md) | 20 | Staging Table - Header staging table: it contains the inbound flow definitions, along with the web service definitions and the statistics for executions. | BASIC TABLE |
| [TF_MESSAGE_TEMPLATES](TF_MESSAGE_TEMPLATES.md) | 19 | Message templates - Message templates<br /> | BASIC TABLE |
| [TF_MENU_VIEW](TF_MENU_VIEW.md) | 12 | TF_MENU_VIEW | VIEW |
| [HR_SESSIONCOSTFINANCING](HR_SESSIONCOSTFINANCING.md) | 21 | Session Costs Financing - Contains the financing rule about session by cost type.<br /> | BASIC TABLE |
| [TF_DW_INTENT_RAG_RESOURCES](TF_DW_INTENT_RAG_RESOURCES.md) | 10 | AI Agent RAG Resources - This entity would include the list of all indexed RAG resources used by an AI Agent.<br /> | BASIC TABLE |
| [HR_COMPETENCYPROFILE](HR_COMPETENCYPROFILE.md) | 17 | Competency Profile - This entity retrieves all the competencies for an employee that have been evaluated and submitted, that are included in a Section of the Appraisal with the flag  'include in profile' activated.<br /> | BASIC TABLE |
| [HR_TRAINSTRUCTORCONTACTS](HR_TRAINSTRUCTORCONTACTS.md) | 27 | Instructor Contacts - This entity stores the contacts of an external instructor.<br /> | BASIC TABLE |
| [TF_NAV_PROFILE_CFGS_VIEW](TF_NAV_PROFILE_CFGS_VIEW.md) | 22 | Navigation Profiles Configurations - Navigation Profiles Configurations<br /> | VIEW |
| [TF_BLRULE_PARAMETERS_CUSTOM](TF_BLRULE_PARAMETERS_CUSTOM.md) | 16 |  | BASIC TABLE |
| [HR_LEARNERACTIVITIES](HR_LEARNERACTIVITIES.md) | 35 | Learner Activities - This entity is child of a Learner and details all learning activities for an enrolled Learner.<br /> | BASIC TABLE |
| [HR_PERSONALTSCRIPTNAMES](HR_PERSONALTSCRIPTNAMES.md) | 30 | Names in alternate language - Use this entity  to store one or more versions of the Names in an alternate language<br /> | BASIC TABLE |
| [TF_NAV_PROFILES_VIEW](TF_NAV_PROFILES_VIEW.md) | 12 | Navigation profiles - Navigation profiles<br /> | VIEW |
| [TF_ASYNC_RULE_CATALOG](TF_ASYNC_RULE_CATALOG.md) | 19 | Async Rule Catalog - Async Rule Catalog<br /> | BASIC TABLE |
| [TF_WEB_RESOURCES](TF_WEB_RESOURCES.md) | 25 | Web Resources - TF_WEB_RESOURCES<br /> | BASIC TABLE |
| [TF_TEMP_RETRIEVE](TF_TEMP_RETRIEVE.md) | 2 |  | BASIC TABLE |
| [HR_COSTCENTERACCOUNTABILITY](HR_COSTCENTERACCOUNTABILITY.md) | 19 | Cost Center to Cost Center Accountabilities - Representes the Cost Center associated to a specific Employee.<br /> | BASIC TABLE |
| [DWH_ENTITY_INST_VISIBILITY](DWH_ENTITY_INST_VISIBILITY.md) | 6 |  | BASIC TABLE |
| [TF_WFRULE_CATALOG](TF_WFRULE_CATALOG.md) | 19 | Workflow Rule Catalog - Workflow Rule Catalog<br /> | BASIC TABLE |
| [HR_INSEECITY](HR_INSEECITY.md) | 18 | INSEE City - Contains the INSEE code. It is a numerical indexing code used by the French National Institute for Statistics and Economic Studies (INSEE) to identify various entities, including towns and regions.<br /> | BASIC TABLE |
| [TF_BATCH_INSTANCES](TF_BATCH_INSTANCES.md) | 37 | Batch instances - Batch Instances<br /> | BASIC TABLE |
| [HR_CALIBRATIONPOOL](HR_CALIBRATIONPOOL.md) | 18 | Calibration Pool - Calibration Pool consists of the list of managers that need to perform a calibration cycle.<br /> | BASIC TABLE |
| [TF_PAGE_CFGS_VIEW](TF_PAGE_CFGS_VIEW.md) | 37 | TF_PAGES_CFGS_VIEW - TF_PAGES_CFGS_VIEW<br /> | VIEW |
| [HR_PARTICEMPHYPOTHESIS](HR_PARTICEMPHYPOTHESIS.md) | 27 | Participant Employment Hypothesis - For each participant, includes the employment situation at the Scenario snapshot date and can include other effective dated Hypothesis, if a change is planned.<br /> | BASIC TABLE |
| [TF_CALENDAR_TYPES_RESOURCES](TF_CALENDAR_TYPES_RESOURCES.md) | 11 | Calendar Types Resources - TF_CALENDAR_TYPES_RESOURCES<br /> | BASIC TABLE |
| [TF_PAGES_VIEW](TF_PAGES_VIEW.md) | 17 | Pages View - Pages View<br /> | VIEW |
| [TF_SOAFLOWS](TF_SOAFLOWS.md) | 52 | SOA Flows - SOA Flows<br /> | BASIC TABLE |
| [HR_ABSENCEPLAN](HR_ABSENCEPLAN.md) | 64 | Absence Plan - Contains the absence plans.<br /> | BASIC TABLE |
| [TF_STARTUP_FACTORY](TF_STARTUP_FACTORY.md) | 9 |  | BASIC TABLE |
| [TF_QUICK_ACTIONS_VIEW](TF_QUICK_ACTIONS_VIEW.md) | 17 | Quick actions - Quick actions<br /> | VIEW |
| [HR_PUBLICHOLIDAY](HR_PUBLICHOLIDAY.md) | 16 | Public Holiday - Includes all public holidays for a calendar.<br /> | BASIC TABLE |
| [TF_TEMP_RETRIEVE_DETAILS](TF_TEMP_RETRIEVE_DETAILS.md) | 3 |  | BASIC TABLE |
| [HR_POSITIONATTRIBUTES](HR_POSITIONATTRIBUTES.md) | 26 | Position Attributes - Contains required details about the properties of the position.<br /> | BASIC TABLE |
| [TF_PROPERTY_GROUPS](TF_PROPERTY_GROUPS.md) | 13 | Property group - TF_PROPERTY_GROUPS<br /> | BASIC TABLE |
| [TF_SECFILTER_STATEMENTS_VIEW](TF_SECFILTER_STATEMENTS_VIEW.md) | 14 |  | VIEW |
| [HR_TRAININGCENTER](HR_TRAININGCENTER.md) | 18 | Training Center - description of entity Training Center<br /> | BASIC TABLE |
| [HR_MULTIPLEXER](HR_MULTIPLEXER.md) | 20 | MULTIPLEXER - MULTIPLEXER DESCRIPTION<br /> | BASIC TABLE |
| [HR_SALARYGRADES](HR_SALARYGRADES.md) | 18 | Salary Grade - A salary grade contains a grade and an associated salary range.<br /> | BASIC TABLE |
| [HR_APPRAISALTYPEROLE](HR_APPRAISALTYPEROLE.md) | 14 |  | BASIC TABLE |
| [TF_USER_PROPERTIES](TF_USER_PROPERTIES.md) | 14 | User Properties - TF_USER_PROPERTIES<br /> | BASIC TABLE |
| [HR_LERNFORECASTCOSTS](HR_LERNFORECASTCOSTS.md) | 21 | Learner Forecast Costs - The currency of the course cost.<br /> | BASIC TABLE |
| [HR_CAREERASPIRATIONS](HR_CAREERASPIRATIONS.md) | 16 | Career Aspirations - Effective Dated Request for relocation.<br /> | BASIC TABLE |
| [TF_SECFILTERS_ADV_VIEW](TF_SECFILTERS_ADV_VIEW.md) | 14 | Security filters Adv - Security filters Adv<br /> | VIEW |
| [HR_DOCTORDETAILS](HR_DOCTORDETAILS.md) | 29 | Doctor Details - Contains details of the doctor.<br /> | BASIC TABLE |
| [TF_EPR_PACKAGE_OBJECTS](TF_EPR_PACKAGE_OBJECTS.md) | 23 | eProvisioning  Package Objects - TF_EPR_PACKAGE_OBJECTS<br /> | BASIC TABLE |
| [TF_STARTUP_TASKS](TF_STARTUP_TASKS.md) | 26 |  | BASIC TABLE |
| [TF_SECURITY_OBJECT_TYPE](TF_SECURITY_OBJECT_TYPE.md) | 10 | Security Object Type - Security Object Type<br /> | BASIC TABLE |
| [TF_SECTEMPORARY_STATEMENTS](TF_SECTEMPORARY_STATEMENTS.md) | 20 |  | BASIC TABLE |
| [TF_WFRT_PROCESSES](TF_WFRT_PROCESSES.md) | 29 | Process Instances - Workflow Runtime Processes View<br /> | BASIC TABLE |
| [HR_STRUCTUREVERSIONS](HR_STRUCTUREVERSIONS.md) | 18 | Structure Versions - If a Structure Type is "Versionable" a Structure of that Type can be multiple Versions over time.<br /> | BASIC TABLE |
| [TF_SECGRANTS_VIEW](TF_SECGRANTS_VIEW.md) | 14 | Security Grants - Security Grants<br /> | VIEW |
| [TF_AI_SEARCH_PROVIDERS](TF_AI_SEARCH_PROVIDERS.md) | 18 | AI Search Providers - AI Search Providers<br /> | BASIC TABLE |
| [TF_TEMP_SEARCH_DATA](TF_TEMP_SEARCH_DATA.md) | 6 |  | BASIC TABLE |
| [TF_PROMPTS](TF_PROMPTS.md) | 17 | Prompt - TF_PROMPTS<br /> | BASIC TABLE |
| [HR_APPRFORMSECTIONTYPE](HR_APPRFORMSECTIONTYPE.md) | 19 | Appraisal Form Section Type - Defines the form section parameters and also how to initialise the section content, specifying the initialisation rule.<br /> | BASIC TABLE |
| [TF_SECURITY_NAV_PROFILES_VIEW](TF_SECURITY_NAV_PROFILES_VIEW.md) | 12 |  | VIEW |
| [TF_LINKSETS_LINKS](TF_LINKSETS_LINKS.md) | 13 | Links - TF_LINKSETS_LINKS<br /> | BASIC TABLE |
| [TF_QSTRT_QUESTIONNAIRES](TF_QSTRT_QUESTIONNAIRES.md) | 19 | Questionnaires - Questionnaires<br /> | BASIC TABLE |
| [TF_WFRT_SIGNREQ_DOCUMENTS](TF_WFRT_SIGNREQ_DOCUMENTS.md) | 7 | E-Signature Documents - This entity includes the name of the documents included in the same E-Signature request.<br /> | BASIC TABLE |
| [HR_TRAINSTRUCTORSKILLS](HR_TRAINSTRUCTORSKILLS.md) | 13 | Instructor Skill - This entity stores the skills of an external instructor.<br /> | BASIC TABLE |
| [HR_SALARYPROGRAM](HR_SALARYPROGRAM.md) | 39 | Salary Program - A salary program includes all rules necessary to kick off a salary review process, including eligible people, reviewable items and budget rules.<br /> | BASIC TABLE |
| [TF_SDL_CHUNKS](TF_SDL_CHUNKS.md) | 17 | SDL Chunks - The chunk detail<br /> | BASIC TABLE |
| [TF_WIDGETS_GALLERY_VIEW](TF_WIDGETS_GALLERY_VIEW.md) | 14 | Widgets Gallery - Widgets Gallery<br /> | VIEW |
| [HR_LANGUAGESKILLS](HR_LANGUAGESKILLS.md) | 22 | Language Skills - A list of the Language Skills for a person, including their mother tongues and any foreign languages, with the associated proficiency level.<br /> | BASIC TABLE |
| [HR_Z_IL_FILE_10_99Z](HR_Z_IL_FILE_10_99Z.md) | 75 | SDL Staging Table 10 99 Z - Zucchetti - Staging table for the Smart Data Load, flow 10 99 - Employees<br /> | BASIC TABLE |
| [TF_EXTAPP_RULE_CATALOG](TF_EXTAPP_RULE_CATALOG.md) | 17 | External Application Rule Catalog - External Application Rule Catalog<br /> | BASIC TABLE |
| [HR_PERSONBANKDETAILS](HR_PERSONBANKDETAILS.md) | 28 | Bank Details - Manage the bank accounts details related to a Person. Multiple bank accounts can be stored. These may be used by the company to pay expenses or salary.<br /> | BASIC TABLE |
| [HR_SESSIONOUTLINECOSTS](HR_SESSIONOUTLINECOSTS.md) | 21 | Session Outline Costs - Session Outline Costs<br /> | BASIC TABLE |
| [TF_DW_INTENT_RESOURCE_TYPES](TF_DW_INTENT_RESOURCE_TYPES.md) | 14 | Intent resource types - Intent resource types<br /> | BASIC TABLE |
| [HR_COMPGRIDROWSCORE](HR_COMPGRIDROWSCORE.md) | 15 | Competency Grid Row Score - This entity allows setting a score for competencies within the grid.<br /> | BASIC TABLE |
| [HR_JOBACCOUNTABILITY](HR_JOBACCOUNTABILITY.md) | 19 | Job Profile to Job Profile Accountabilies - This Entity can be used to represent hierarchical relationship between Job Profiles, for example to represent Job Families.<br /> | BASIC TABLE |
| [TF_MODULE_CONSUMED_ITEMS](TF_MODULE_CONSUMED_ITEMS.md) | 12 | Module consumed items - Log of consumed module items<br /> | BASIC TABLE |
| [TF_BLRULES](TF_BLRULES.md) | 17 |  | BASIC TABLE |
| [TF_EVENT_DEFINITIONS](TF_EVENT_DEFINITIONS.md) | 50 | Event Definitions - The Event Definitions.<br /> | BASIC TABLE |
| [TF_TOPICS](TF_TOPICS.md) | 27 | Topics - Topics entity<br /> | BASIC TABLE |
| [TF_INTEROP_SCENARIO_STEPS](TF_INTEROP_SCENARIO_STEPS.md) | 26 | Interoperability Scenarios Steps - Interoperability Scenarios Steps<br /> | BASIC TABLE |
| [TF_TEMP_SEARCH](TF_TEMP_SEARCH.md) | 15 |  | BASIC TABLE |
| [HR_Z_IMPORTPAYLOADS](HR_Z_IMPORTPAYLOADS.md) | 17 | Payload Staging Table - Payload staging table: it contains the imported payloads for a given entity. | BASIC TABLE |
| [HR_LERNACTIVFORECASTCOSTS](HR_LERNACTIVFORECASTCOSTS.md) | 22 | Learner Activity Forecast Costs - This entity details all forecast costs for an activity learner.<br /> | BASIC TABLE |
| [HR_PARTICIPANTINPOOL](HR_PARTICIPANTINPOOL.md) | 17 |  | BASIC TABLE |
| [TF_ASYNC_TASKS](TF_ASYNC_TASKS.md) | 31 | Async Tasks - Async Tasks<br /> | BASIC TABLE |
| [HR_INDIVIDUALABSALLOWANCE](HR_INDIVIDUALABSALLOWANCE.md) | 17 | Individual Absence Allowance - Contains the individual absence allowances.<br /> | BASIC TABLE |
| [TF_CFGS_CONTEXTS](TF_CFGS_CONTEXTS.md) | 12 | Configuration Contexts - TF_CFGS_CONTEXTS<br /> | BASIC TABLE |
| [HR_ABSENCEEVENTDETAIL](HR_ABSENCEEVENTDETAIL.md) | 22 | Absence Event Detail - This entity includes the daily absence details.<br /> | BASIC TABLE |
| [HR_SALARYLINESPOT](HR_SALARYLINESPOT.md) | 17 | Salary Line Spots - Salary Line Spots<br /> | BASIC TABLE |
| [TF_WFRT_SIGNREQ_INTEROPS](TF_WFRT_SIGNREQ_INTEROPS.md) | 6 | E-Signature Runtime Logs - This entity includes the reference to the interop runtimes that where created to get the signature. For the same request, more than one record can exist in case of reminders sent.<br /> | BASIC TABLE |
| [TF_DW_CHANNELS](TF_DW_CHANNELS.md) | 24 | Interoperability channels - Interoperability channels<br /> | BASIC TABLE |
| [HR_POSITIONSINUNIT](HR_POSITIONSINUNIT.md) | 19 | Positions in Organizational Unit - This represents the relationship between Positions and Units.<br /> | BASIC TABLE |
| [TF_BLENTITY_CATEGORIES](TF_BLENTITY_CATEGORIES.md) | 11 | TF_BLENTITIES_CATEGORIES - TF_BLENTITIES_CATEGORIES<br /> | BASIC TABLE |
| [HR_TRAININGCLASSROOM](HR_TRAININGCLASSROOM.md) | 21 | Training Classroom - description of entity Training Classroom<br /> | BASIC TABLE |
| [HR_APPRCOMPONENTSCORE](HR_APPRCOMPONENTSCORE.md) | 25 | Appraisal Component Score - This entity stores the score for each component in an appraisal review. For example, an individual appraisal which will generate an overall performance assessment calculated as a weighted average of Objectives and Competencies will generate, for each review, at least three scores in this table: one for the overall performance and two partial scores for objectives and competencies respectively. | BASIC TABLE |
| [TF_OBJECT_TYPE_ACTION](TF_OBJECT_TYPE_ACTION.md) | 10 |  | BASIC TABLE |
| [TF_WFROLES](TF_WFROLES.md) | 25 | Workflow Roles - Workflow Roles<br /> | BASIC TABLE |
| [TF_COMPONENT_PROPERTIES](TF_COMPONENT_PROPERTIES.md) | 35 | Component Properties - TF_COMPONENT_PROPERTIES<br /> | BASIC TABLE |
| [HR_DPAE](HR_DPAE.md) | 22 | DPAE - DPAE<br /> | BASIC TABLE |
| [HR_COSTCENTERASSIGNMENT](HR_COSTCENTERASSIGNMENT.md) | 26 | Cost Center Assignment - Representes the Cost Center associated to a specific Employee.<br /> | BASIC TABLE |
| [TF_TAG_CATEGORIES](TF_TAG_CATEGORIES.md) | 17 | Tag Categories - The Tag Categories<br /> | BASIC TABLE |
| [HR_FORECASTCOSTFINANCING](HR_FORECASTCOSTFINANCING.md) | 19 | Forecast Costs Financing - Contains the financed forecast costs.<br /> | BASIC TABLE |
| [HR_SURVEY](HR_SURVEY.md) | 26 | Survey - This datasource returns data relating to a survey.<br /> | BASIC TABLE |
| [HR_CAREERASPDETAILS](HR_CAREERASPDETAILS.md) | 17 | Career aspiration details - Reallocation preferences including Job and Location.<br /> | BASIC TABLE |
| [HR_COMPGRID](HR_COMPGRID.md) | 21 | Competency Grid - Defines a list of competencies and, optionally, enables a weight to be associated.<br /> | BASIC TABLE |
| [HR_OBJECTIVE](HR_OBJECTIVE.md) | 31 | Objectives - Objectives including targets, results and assignment rules.<br /> | BASIC TABLE |
| [HR_TRAINSTRUCTORSOCIAL](HR_TRAINSTRUCTORSOCIAL.md) | 15 | Instructor Social Contacts Portrait - This entity returns the social contacts of all instructors, internal and external.<br /> | BASIC TABLE |
| [HR_OBJASSIGNRULE](HR_OBJASSIGNRULE.md) | 15 | Objective Assignment Rule - With this entity it's possible to specify who an objective goes to.<br /> | BASIC TABLE |
| [TF_DW_INTENT_RESOURCES](TF_DW_INTENT_RESOURCES.md) | 49 | Intent resources - Intent resources<br /> | BASIC TABLE |
| [TF_PROPERTY_ENUM_VALUES](TF_PROPERTY_ENUM_VALUES.md) | 13 | Property Enumerable Values - Property Enumerable Values<br /> | BASIC TABLE |
| [HR_LEARNERCOSTS](HR_LEARNERCOSTS.md) | 21 | Learner Costs - This entity contains the costs related to a learner.<br /> | BASIC TABLE |
| [HR_PERSONCATEGORIAPROTETTA](HR_PERSONCATEGORIAPROTETTA.md) | 17 | Legal Category Status - Legal Category Status<br /> | BASIC TABLE |
| [TF_MODULE_DETAILS](TF_MODULE_DETAILS.md) | 12 | Module details - Licensed module details<br /> | BASIC TABLE |
| [TF_USER_PROVIDERS](TF_USER_PROVIDERS.md) | 14 | User authentication providers - The TF_USER_PROVIDERS Entity<br /> | BASIC TABLE |
| [TF_SEC_ACL_LOG](TF_SEC_ACL_LOG.md) | 5 |  | BASIC TABLE |
| [HR_SESSIONOUTCOSTFINANCING](HR_SESSIONOUTCOSTFINANCING.md) | 21 | Session Content Cost Financing - Contains the session content costs financing.<br /> | BASIC TABLE |
| [TF_QSTRT_ANSWERS](TF_QSTRT_ANSWERS.md) | 18 | Questions - Questions<br /> | BASIC TABLE |
| [TF_ANALYTICS_TYPES](TF_ANALYTICS_TYPES.md) | 13 | Analytics Types - Analytics Types<br /> | BASIC TABLE |
| [TF_SECURITY_NAV_PROFILES](TF_SECURITY_NAV_PROFILES.md) | 12 | Security Navigation Profiles - TF_SECURITY_NAV_PROFILES<br /> | BASIC TABLE |
| [HR_SALARYPROGPOOL](HR_SALARYPROGPOOL.md) | 17 | Salary Program Pool - Identifies a group of people eligible to receive a salary review and the salary reviewer.<br /> | BASIC TABLE |
| [TF_MAIL_CONFIG](TF_MAIL_CONFIG.md) | 27 | TF_MAIL_CONFIG - TF_MAIL_CONFIG<br /> | BASIC TABLE |
| [TF_EPR_OBJECT_DEPENDENCIES](TF_EPR_OBJECT_DEPENDENCIES.md) | 23 | eProvisioning  Object Dependencies - TF_EPR_OBJECT_DEPENDENCIES<br /> | BASIC TABLE |
| [HR_COMPHISTORY](HR_COMPHISTORY.md) | 20 | Compensation History - A history of Compensation Changes<br /> | BASIC TABLE |
| [HR_PARTYATTRIBUTES](HR_PARTYATTRIBUTES.md) | 80 | Party Attributes - Contains required details about the properties of the party.<br /> | BASIC TABLE |
| [TF_TEMP_SEARCH_DETAILS](TF_TEMP_SEARCH_DETAILS.md) | 6 |  | BASIC TABLE |
| [TF_BLRULE_PARAMETERS](TF_BLRULE_PARAMETERS.md) | 16 |  | BASIC TABLE |
| [TF_WFTRANSITIONS](TF_WFTRANSITIONS.md) | 31 | Workflow Transitions - Workflow Transitions<br /> | BASIC TABLE |
| [TF_EXTENDED_ATTRIBUTES](TF_EXTENDED_ATTRIBUTES.md) | 108 |  | BASIC TABLE |
| [TF_BATCH_INSTANCE_LOGS](TF_BATCH_INSTANCE_LOGS.md) | 12 | Batch Instance Logs - Batch Instance Logs<br /> | BASIC TABLE |
| [TF_SEC_ACL](TF_SEC_ACL.md) | 6 |  | BASIC TABLE |
| [HR_OBJECTIVEASSIGNEES](HR_OBJECTIVEASSIGNEES.md) | 16 | Objective Assignees - This entity contains the list of people that comes from the resolution of assignment rules for an objective.<br /> | BASIC TABLE |
| [HR_ACTFORECASTCOSTFINANCING](HR_ACTFORECASTCOSTFINANCING.md) | 20 | Activity Forecast Cost Financing - Contains the activity forecasted financed costs.<br /> | BASIC TABLE |
| [TF_ASYNC_TASK_LOGS](TF_ASYNC_TASK_LOGS.md) | 11 | Async Task Logs - Async Task Logs<br /> | BASIC TABLE |
| [HR_APPROBJSECROW](HR_APPROBJSECROW.md) | 49 | Appraisal Objective Section Row - This entity collects the objective within an appraisal review objective section<br /> | BASIC TABLE |
| [HR_ABSACCRUAL](HR_ABSACCRUAL.md) | 28 | Accrual - Contains the accruals.<br /> | BASIC TABLE |
| [TF_ACTIONS](TF_ACTIONS.md) | 11 | Actions - Actions<br /> | BASIC TABLE |
| [TF_CONNECTIVE_PACKAGES](TF_CONNECTIVE_PACKAGES.md) | 12 |  | BASIC TABLE |
| [TF_WIDGETS_CATEGORIES](TF_WIDGETS_CATEGORIES.md) | 13 | Widgets Category - TF_WIDGETS_CATEGORIES<br /> | BASIC TABLE |
| [HR_SALARYPROGCOMPITEMS](HR_SALARYPROGCOMPITEMS.md) | 23 | Salary Program Compensation Item - This is the compensation item for the proposed new compensation amount.<br /> | BASIC TABLE |
| [TF_BLFIELDS_CUSTOM](TF_BLFIELDS_CUSTOM.md) | 22 |  | BASIC TABLE |
| [HR_JOBASSIGNMENT](HR_JOBASSIGNMENT.md) | 21 | Job Assignment - Indicates the Job associated to a Person in the context of a specific Company Relationship.<br /> | BASIC TABLE |
| [TF_SECRULE_CATALOG](TF_SECRULE_CATALOG.md) | 15 | Security Rule Catalog - Security Rule Catalog<br /> | BASIC TABLE |
| [HR_SESSION](HR_SESSION.md) | 47 | Session - This entity contains training session.<br /> | BASIC TABLE |
| [HR_DPAECONNECTORSINFO](HR_DPAECONNECTORSINFO.md) | 16 | URSSAF Connection Profile - Information about DPAE connection details.<br /> | BASIC TABLE |
| [HR_OBJECTIVEMETRIC](HR_OBJECTIVEMETRIC.md) | 29 | Objective Metric - This entity further describes an Objective with the Kpis that it will be measured by.<br /> | BASIC TABLE |
| [HR_ABSENCEDAILYACCRUAL](HR_ABSENCEDAILYACCRUAL.md) | 14 | Absence Daily Accrual - Daily details of taken from accrual.<br /> | BASIC TABLE |
| [TF_PAGE_CFGS_ACL](TF_PAGE_CFGS_ACL.md) | 13 | Page configuration's Access Control List - Page configuration's Access Control List<br /> | BASIC TABLE |
| [HR_SURVEYPARTICIPANT](HR_SURVEYPARTICIPANT.md) | 17 | Survey Participant - Survey Participant entity description.<br /> | BASIC TABLE |
| [HR_STRUCTURETYPE](HR_STRUCTURETYPE.md) | 26 | Structure Type - A Structure Type define the semantics of all Structures in that type.<br /> | BASIC TABLE |
| [HR_COSTXPARTICIPANT](HR_COSTXPARTICIPANT.md) | 21 | Cost x Participant - For each scenario participant, normalises the individual Cost due to the planned hypothesis.<br /> | BASIC TABLE |
| [HR_COMPGRIDROW](HR_COMPGRIDROW.md) | 18 | Competency Grid Row - This represents the link between Competencies and Grid.<br /> | BASIC TABLE |
| [HR_TRANSPOSEDENTITY](HR_TRANSPOSEDENTITY.md) | 22 | Transposed Entity - When TransposeDatasource rule is active, the entities of the datasource of the process workflow are transpose in this entity<br /> | BASIC TABLE |
| [HR_GDPRREQUEST](HR_GDPRREQUEST.md) | 19 | Personal Data Privacy Request - This entity manages requests to exercise rights around personal data privacy. With this entity, you can for example ask to anonymize data for terminated employees or audit data obsolescence.<br /> | BASIC TABLE |
| [TF_TEMP_SEC_ACL](TF_TEMP_SEC_ACL.md) | 7 |  | BASIC TABLE |
| [HR_OBJECTIVEPLAN](HR_OBJECTIVEPLAN.md) | 20 | Objective Plan - This entity is a container where defining objectives with Targets, results and assignment rules.<br /> | BASIC TABLE |
| [TF_BATCH_QUEUES_NODES](TF_BATCH_QUEUES_NODES.md) | 10 |  | BASIC TABLE |
| [HR_TIMESHEET](HR_TIMESHEET.md) | 17 | Timesheet - The timesheet entity.<br /> | BASIC TABLE |
| [HR_PERSONCITIZENSHIPS](HR_PERSONCITIZENSHIPS.md) | 18 | Citizenships - This Entity is used to manage multiple Citizenships of a Person. A specific validity period can be recorded for each record.<br /> | BASIC TABLE |
| [HR_SURVEYRECIPIENT](HR_SURVEYRECIPIENT.md) | 18 | Survey Recipient - This is used to store survey recipients data.<br /> | BASIC TABLE |
| [TF_AUDIT_DATADICTIONARY](TF_AUDIT_DATADICTIONARY.md) | 13 | Audit Data Dictionary logs - Audit Data Dictionary logs<br /> | BASIC TABLE |
| [HR_OBJMETRICTARGET](HR_OBJMETRICTARGET.md) | 17 | Objective Metric Target - This entity is used to detail the Objective Metric targets.<br /> | BASIC TABLE |
| [HR_LEARNERCOSTFINANCING](HR_LEARNERCOSTFINANCING.md) | 19 | Actual Costs Financing - Contains the financed actual costs.<br /> | BASIC TABLE |
| [HR_TRASHAREDRESOURCES](HR_TRASHAREDRESOURCES.md) | 35 | Shared Resources - Digital shared resources, like web pages, SCORM contents, YouTube videos that can be used to build course content.<br /> | BASIC TABLE |
| [TF_QUICK_ACTIONS](TF_QUICK_ACTIONS.md) | 17 | Quick actions - Quick actions<br /> | BASIC TABLE |
| [TF_TOPIC_ENTITIES](TF_TOPIC_ENTITIES.md) | 11 | Topic Entities - The Topic Entities.<br /> | BASIC TABLE |
| [HR_TRAINSTRUCTORS](HR_TRAINSTRUCTORS.md) | 33 | Instructor - This entity is used to represent all instructors.<br /> | BASIC TABLE |
| [TF_INTEROP_RUNTIME](TF_INTEROP_RUNTIME.md) | 33 | Interop Runtime - Interop Runtime<br /> | BASIC TABLE |
| [TF_ANALYTICS](TF_ANALYTICS.md) | 29 | Analytics - Analytics<br /> | BASIC TABLE |
| [TF_TEMPLATE_RESOURCE_TYPES](TF_TEMPLATE_RESOURCE_TYPES.md) | 14 | Template Resource Types - TF_TEMPLATE_RESOURCE_TYPES<br /> | BASIC TABLE |
| [TF_PROXY_ACL](TF_PROXY_ACL.md) | 14 | Proxy ACL - Proxy ACL<br /> | BASIC TABLE |
| [HR_SCENARIOPARTICIPANT](HR_SCENARIOPARTICIPANT.md) | 17 | Scenario Participant - A Scenario Participant is an individual participating in the scenario. If a new hire, it’s a simulated person without a link to any existing person in the HCM database.<br /> | BASIC TABLE |
| [TF_DW_CHANNELS_USERS](TF_DW_CHANNELS_USERS.md) | 13 | Digital workplace channels users - Digital workplace channels users<br /> | BASIC TABLE |
| [TF_EXTENDED_ENTITIES](TF_EXTENDED_ENTITIES.md) | 111 |  | BASIC TABLE |
| [HR_TRAININGPLAN](HR_TRAININGPLAN.md) | 26 | Training Plan - This entity will be a container for the Training Request<br /> | BASIC TABLE |
| [HR_PARTYLOG](HR_PARTYLOG.md) | 22 | PARTYLOG - PARTYLOG<br /> | BASIC TABLE |
| [TF_AUDIT_LOG](TF_AUDIT_LOG.md) | 10 | Audit Log - TF_AUDIT_LOG<br /> | BASIC TABLE |
| [TF_DW_INTENTPAGES](TF_DW_INTENTPAGES.md) | 10 | Intent Pages - Intent Pages<br /> | BASIC TABLE |
| [TF_TAG_CATEGORY_ENTITIES](TF_TAG_CATEGORY_ENTITIES.md) | 14 | Entities Tag Category  - The categories used on the specific entity<br /> | BASIC TABLE |
| [TF_SECURITYQUESTIONS](TF_SECURITYQUESTIONS.md) | 9 |  | BASIC TABLE |
| [HR_SALARYREVIEWPARTICIPANT](HR_SALARYREVIEWPARTICIPANT.md) | 14 | Salary Review Participant - Reference to a person or company relationship who is eligible for a salary review.<br /> | BASIC TABLE |
| [TF_USER_TIME_TRACKING](TF_USER_TIME_TRACKING.md) | 18 | User Time Tracking - Entity used to track user work time<br /> | BASIC TABLE |
| [HR_SURVEYUSERPARTICIPANT](HR_SURVEYUSERPARTICIPANT.md) | 15 | Survey User Participant - This entity manages the confidentiality of anonymous surveys and contains the association between the answers provided and a specific user or person.<br /> | BASIC TABLE |
| [TF_QSTRT_CHOICES](TF_QSTRT_CHOICES.md) | 15 | Answers - Answers<br /> | BASIC TABLE |
| [TF_WFRT_ACTORS](TF_WFRT_ACTORS.md) | 15 | Workflow Runtime Actors - TF_WFRT_ACTORS<br /> | BASIC TABLE |
| [TF_AUDIT_SWITCH](TF_AUDIT_SWITCH.md) | 2 |  | BASIC TABLE |
| [HR_OBJMETRICTEMPLATE](HR_OBJMETRICTEMPLATE.md) | 22 | Objective Metric Template - This entity further describes an Objective Template with the Kpi that it will be measured by.<br /> | BASIC TABLE |
| [TF_BLRULES_CUSTOM](TF_BLRULES_CUSTOM.md) | 17 |  | BASIC TABLE |
| [TF_ACTIVITY_STREAM_TYPES](TF_ACTIVITY_STREAM_TYPES.md) | 14 | Activity Stream Types - Activity Stream Types<br /> | BASIC TABLE |
| [HR_ACTIONTYPE_ADVSETTINGS](HR_ACTIONTYPE_ADVSETTINGS.md) | 18 | Activity Type Advanced Settings - Extended settings for the activity type.<br /> | BASIC TABLE |
| [HR_TSDAYACTIVITIES_ATTR](HR_TSDAYACTIVITIES_ATTR.md) | 13 | Timesheet Day Activity Attributes  - The associative table between a Timesheet Day Activity and its Time Tracker Activity Attributes.<br /> | BASIC TABLE |
| [HR_EDUCATIONHISTORY](HR_EDUCATIONHISTORY.md) | 30 | Education History - List of qualifications achieved by the person.<br /> | BASIC TABLE |
| [TF_DASHBOARD_ITEMS_HANDLERS](TF_DASHBOARD_ITEMS_HANDLERS.md) | 18 | Dashboard Items Handlers - Dashboard Items Handlers<br /> | BASIC TABLE |
| [HR_COMPANY](HR_COMPANY.md) | 17 | Company - This Entity represents the Companies in the Group.<br /> | BASIC TABLE |
| [HR_TARGET](HR_TARGET.md) | 27 | Targets - A Simulation Scenario Target can be either a Decimal, Percentage, Long, Date or a discrete value from a Code Table. Is attached to a dimension like the Company, the Job or the Unit.<br /> | BASIC TABLE |
| [HR_CHARTERPERSPECTIVES](HR_CHARTERPERSPECTIVES.md) | 28 | Charter Perspectives - Charter Perspectives<br /> | BASIC TABLE |
| [TF_AUDIT_TRIGGER](TF_AUDIT_TRIGGER.md) | 5 |  | BASIC TABLE |
| [HR_APPROBJMETRIC](HR_APPROBJMETRIC.md) | 42 | Appraisal Objective Metric - description of entity appraisal objective metric<br /> | BASIC TABLE |
| [HR_COURSE_PROCESSES](HR_COURSE_PROCESSES.md) | 17 | Course Processes - Course Processes<br /> | BASIC TABLE |
| [HR_SALARYPROGPOOLBUDGET](HR_SALARYPROGPOOLBUDGET.md) | 25 | Salary Program Pool Budget - It’s the entity where the budget by salary pool is represented.<br /> | BASIC TABLE |
| [TF_INDEX_SEARCH_PROVIDERS](TF_INDEX_SEARCH_PROVIDERS.md) | 18 | Index Search Providers - TF_INDEX_SEARCH_PROVIDERS<br /> | BASIC TABLE |
| [HR_JOBATTRIBUTES](HR_JOBATTRIBUTES.md) | 18 | Job Attributes - Contains details related to the job.<br /> | BASIC TABLE |
| [TF_CURRENCIES](TF_CURRENCIES.md) | 3 |  | BASIC TABLE |
| [TF_EPR_PACKAGE_DELIVERABLES](TF_EPR_PACKAGE_DELIVERABLES.md) | 18 | Package deliverables - Package deliverables<br /> | BASIC TABLE |
| [HR_ABSENTITLEMENTADJ](HR_ABSENTITLEMENTADJ.md) | 17 | Absence Entitlement Adjustment - Contains the absence entitlement adjustments.<br /> | BASIC TABLE |
| [TF_SEC_ADV_FILTERS_PROFILE](TF_SEC_ADV_FILTERS_PROFILE.md) | 16 | Advanced Security Profile Filters - Advanced Security Profile Filters<br /> | BASIC TABLE |
| [TF_AUDIT](TF_AUDIT.md) | 34 | Audit - Audit<br /> | BASIC TABLE |
| [HR_OFFBOARDINGDETAILS](HR_OFFBOARDINGDETAILS.md) | 34 | Off Boarding Details - This table is used to store the worker departure<br /> | BASIC TABLE |
| [HR_APPRCOMPSECROW](HR_APPRCOMPSECROW.md) | 25 | Appraisal Competency Section Row - This entity represents a single competency review.<br /> | BASIC TABLE |
| [TF_CURRENCIES_RATES](TF_CURRENCIES_RATES.md) | 4 |  | BASIC TABLE |
| [TF_BATCHES_SEQUENCES](TF_BATCHES_SEQUENCES.md) | 11 | Batch Sequence - Batch Sequence<br /> | BASIC TABLE |
| [HR_GDPRAUDITREQUESTRESPONSE](HR_GDPRAUDITREQUESTRESPONSE.md) | 19 | GDPR Audit Request Response - This is the response to a request for data obsolescence and includes, by category of data, some information related to, for instance, how many records are managed in the database, what is the oldest date time a record was last updated, the oldest document reference date etc.<br /> | BASIC TABLE |
| [TF_MAIL_TEMPLATES](TF_MAIL_TEMPLATES.md) | 26 | Mail Templates - Mail Templates<br /> | BASIC TABLE |
| [HR_ASSESMENTCOMPONENT](HR_ASSESMENTCOMPONENT.md) | 33 | Assessment Component - Assessment Component<br /> | BASIC TABLE |
| [HR_APPROBJMETRICTARGET](HR_APPROBJMETRICTARGET.md) | 19 | Appraisal Objective Metric Target - description of entity appraisal objective metric target<br /> | BASIC TABLE |
| [TF_PAGES](TF_PAGES.md) | 18 | Page - Entity TF_PAGES<br /> | BASIC TABLE |
| [HR_PERSONCONTACTS](HR_PERSONCONTACTS.md) | 36 | Contact Information - Contact Information for the Person, including email addresses, phone numbers and social media accounts.<br /> | BASIC TABLE |
| [TF_BLPHYSICAL_TABLES](TF_BLPHYSICAL_TABLES.md) | 23 |  | BASIC TABLE |
| [TF_TEMPLATE_RESOURCES](TF_TEMPLATE_RESOURCES.md) | 59 | Template Resources - Template Resources<br /> | BASIC TABLE |
| [TF_BLFIELDS](TF_BLFIELDS.md) | 22 |  | BASIC TABLE |
| [TF_EXTERNAL_APPLICATIONS](TF_EXTERNAL_APPLICATIONS.md) | 17 | External Applications - TF_EXTERNAL_APPLICATIONS<br /> | BASIC TABLE |
| [TF_WFPROCESS_TYPES](TF_WFPROCESS_TYPES.md) | 37 | Workflow Process Types - Workflow Process Types<br /> | BASIC TABLE |
| [HR_PARTYTYPECHARTERELEMENTS](HR_PARTYTYPECHARTERELEMENTS.md) | 14 | PARTYTYPECHARTERELEMENTS - PARTYTYPECHARTERELEMENTS<br /> | BASIC TABLE |
| [TF_TOPIC_NAMED_USERS](TF_TOPIC_NAMED_USERS.md) | 12 | Topic Named Users - The Topic Named Users.<br /> | BASIC TABLE |
| [HR_OUTLINEINSTRUCTOR](HR_OUTLINEINSTRUCTOR.md) | 14 | Session Outline Teacher and Tutors - The entity where every activity in a session is linked to one or more instructor.<br /> | BASIC TABLE |
| [HR_LEARNERCREDITS](HR_LEARNERCREDITS.md) | 26 | Learner Credits - Contains the credits achieved by the learner.<br /> | BASIC TABLE |
| [HR_PARTICCOMPHYPOTHESIS](HR_PARTICCOMPHYPOTHESIS.md) | 32 | Participant Compensation Hypothesis - For each participant, includes the compensation situation at the Scenario snapshot date and can include other effective dated Hypothesis, if a change is planned.<br /> | BASIC TABLE |
| [HR_PREFTIMETRACKINGACT](HR_PREFTIMETRACKINGACT.md) | 17 | Preferred Time Tracking Activities - Preferred Time Tracking Activities<br /> | BASIC TABLE |
| [TF_SEQUENCES](TF_SEQUENCES.md) | 9 |  | BASIC TABLE |
| [TF_WIDGETS_GALLERY](TF_WIDGETS_GALLERY.md) | 14 | Widgets gallery - TF_WIDGETS_GALLERY<br /> | BASIC TABLE |
| [TF_NAV_PROFILES](TF_NAV_PROFILES.md) | 12 | Navigation profiles - Navigation profiles<br /> | BASIC TABLE |
| [HR_APPRAISALFORMSECTION](HR_APPRAISALFORMSECTION.md) | 83 | Appraisal Form Section - This entity contains the section definition within an appraisal form.<br /> | BASIC TABLE |
| [HR_APPRSCORECALIBRATION](HR_APPRSCORECALIBRATION.md) | 21 | Appraisal Score Calibration - Appraisal score calibration<br /> | BASIC TABLE |
| [TF_EVENT_CHECKRULE_CATALOG](TF_EVENT_CHECKRULE_CATALOG.md) | 17 | Event CheckRule Catalog - The Event CheckRule Catalog.<br /> | BASIC TABLE |
| [TF_DW_INTENTPAGES_SNOOZES](TF_DW_INTENTPAGES_SNOOZES.md) | 10 | TF_DW_INTENTPAGES_SNOOZES | BASIC TABLE |
| [TF_ACTIVITY_STREAM](TF_ACTIVITY_STREAM.md) | 19 | Social Activity Stream - The Social Activity Stream<br /> | BASIC TABLE |
| [TF_DW_COMPLETION_PROMPTS](TF_DW_COMPLETION_PROMPTS.md) | 29 | LLM Completion Resources - This catalog would return any reusable prompt or knowledge base fragment/indexed file folder that could be used by an AI agent to complete a response.<br /> | BASIC TABLE |
| [HR_PERSON](HR_PERSON.md) | 56 | Person - Contains information identifying the person.<br /> | BASIC TABLE |
| [HR_LEARNERACTIVITYCOSTS](HR_LEARNERACTIVITYCOSTS.md) | 22 | Learner Activity Costs - This entity contains the costs related to a learner activity.<br /> | BASIC TABLE |
| [HR_USERSTALENTIAECOSYSTEM](HR_USERSTALENTIAECOSYSTEM.md) | 16 | Talentia Ecosystem Users - Contains details of user access to Talentia Ecosystem products<br /> | BASIC TABLE |
| [TF_QUEUE](TF_QUEUE.md) | 39 | Queue - Queue<br /> | BASIC TABLE |
| [TF_APP_PARAMETERS](TF_APP_PARAMETERS.md) | 34 | Application Parameters - Application Parameters<br /> | BASIC TABLE |
| [TF_PROPERTIES](TF_PROPERTIES.md) | 30 | Properties - Properties<br /> | BASIC TABLE |
| [TF_WFRT_TASKS](TF_WFRT_TASKS.md) | 34 | Tasks - Workflow Runtime Tasks<br /> | BASIC TABLE |
| [HR_COLLATERALSALARYREVITEM](HR_COLLATERALSALARYREVITEM.md) | 16 | Collateral Salary Review Items - Represents additional items that might be included as part of a salary review, like a promotion to a new Job Class or a change to the salary grade.<br /> | BASIC TABLE |
| [TF_USERGROUP_USERS](TF_USERGROUP_USERS.md) | 10 | User Group Users - User Group Users<br /> | BASIC TABLE |
| [HR_TARGETSTEMPLATE](HR_TARGETSTEMPLATE.md) | 20 | Target Template - List of Target Models (like Turnover, Minimum Compensation Ratio, Average Job Suitability, etc.) that you might want to use in a Scenario to set goals.<br /> | BASIC TABLE |
| [HR_EMERGENCYCONTACTS](HR_EMERGENCYCONTACTS.md) | 30 | Emergency Contacts - An additional list of people that might be contacted for emergency reasons. Includes e-mail, address and type of relationship.<br /> | BASIC TABLE |
| [HR_APPRSECFIELDSCTX](HR_APPRSECFIELDSCTX.md) | 18 | Form settings exceptions by context - Form settings exceptions by context<br /> | BASIC TABLE |
| [HR_COURSECOSTS](HR_COURSECOSTS.md) | 20 | Course Costs - Document Template<br /> | BASIC TABLE |
| [TF_TAGS](TF_TAGS.md) | 17 | Tags - The tags can be used<br /> | BASIC TABLE |
| [HR_PREVEMPLOYMENTHISTORY](HR_PREVEMPLOYMENTHISTORY.md) | 28 | Previous Employment History - This entity maintains the history of all the previous personal work experiences, including Job Title, Period, Employer and Location.<br /> | BASIC TABLE |
| [HR_JOBCLASSASSIGNMENT](HR_JOBCLASSASSIGNMENT.md) | 17 | Qualification Assignment - A Qualification assigned to the Employee.<br /> | BASIC TABLE |
| [TF_SHARED_RULE_CATALOG](TF_SHARED_RULE_CATALOG.md) | 19 | Shared Rule Catalog - The Shared Rule Catalog.<br /> | BASIC TABLE |
| [HR_SALARYREVIEWGUIDELINE](HR_SALARYREVIEWGUIDELINE.md) | 26 | Salary Review Guideline - This is a decision support tool for people in charge of a salary review. Represents a matrix with two dimensions on X and Y axis, representing an attribute of an employee. The cell is a min/max salary increase for each couple of attribute values.<br /> | BASIC TABLE |
| [TF_PROXY_ACL_PROFILES](TF_PROXY_ACL_PROFILES.md) | 10 | Proxy ACL Profiles - Profiles that can be impersonated by a proxy user<br /> | BASIC TABLE |
| [TF_EPR_PACKAGE_DEPENDENCIES](TF_EPR_PACKAGE_DEPENDENCIES.md) | 15 | eProvisioning  Package Dependencies - TF_EPR_PACKAGE_DEPENDENCIES<br /> | BASIC TABLE |
| [TF_WIDGETS](TF_WIDGETS.md) | 26 | Widget - TF_WIDGETS<br /> | BASIC TABLE |
| [HR_ORGUNITACCOUNTABILITY](HR_ORGUNITACCOUNTABILITY.md) | 19 | Organizational Unit to Organizational Unit Accountabilities - This Entity is used to represent hierarchies between Organizational Units.<br /> | BASIC TABLE |
| [TF_INTEROP_PARENT_RUNTIME](TF_INTEROP_PARENT_RUNTIME.md) | 3 | Interop Parent Runtime - Interop Parent Runtime<br /> | BASIC TABLE |
| [HR_ABSPLANCLASHRULES](HR_ABSPLANCLASHRULES.md) | 14 | Absence Plan Clash Rule - description of entity Absence Plan Clash Rule<br /> | BASIC TABLE |
| [TF_WFSUBJECTS](TF_WFSUBJECTS.md) | 26 | Workflow Subjects - Workflow Subjects<br /> | BASIC TABLE |
| [HR_PERSONMEDICALDETAILS](HR_PERSONMEDICALDETAILS.md) | 18 | Medical Details - Manage the medical details related to a Person.<br /> | BASIC TABLE |
| [TF_BATCHES_SEQUENCES_ITEMS](TF_BATCHES_SEQUENCES_ITEMS.md) | 16 | Batch Sequence Item - Batch Sequence Item<br /> | BASIC TABLE |
| [HR_GDPRREQUESTINFORMATION](HR_GDPRREQUESTINFORMATION.md) | 13 | Data Privacy Request Areas of Interests - Represents all types of personal data which are subjects of the parent request.<br /> | BASIC TABLE |
| [HR_APPRAISALFORM](HR_APPRAISALFORM.md) | 41 | Appraisal Form - This entity stores the appraisal form model or template that will be used during an evaluation.<br /> | BASIC TABLE |
| [HR_COMPGRIDROWQST](HR_COMPGRIDROWQST.md) | 15 | Competency Grid Row Question - Defines, for each competency grid, one or more questions whose answer score will influence the competency score calculation.<br /> | BASIC TABLE |
| [TF_INDEXES](TF_INDEXES.md) | 19 | Indexes - TF_INDEXES<br /> | BASIC TABLE |
| [HR_PARTYTYPEPORTRAITS](HR_PARTYTYPEPORTRAITS.md) | 17 | Party Type Portraits - This Entity represents, for each Party Type, all possible "Views" that it is possible to access to when accessing to the node detail from a Tree View.<br /> | BASIC TABLE |
| [TF_RESOURCES](TF_RESOURCES.md) | 25 |  | BASIC TABLE |
| [TF_PAGE_CFGS](TF_PAGE_CFGS.md) | 38 | Page configuration - Entity TF_PAGE_CFGS<br /> | BASIC TABLE |
| [HR_LICENSEPERMITVISA](HR_LICENSEPERMITVISA.md) | 21 | Licenses, Permits and Visas - Manages the list of documents for a Person, like Licenses, Work Permits or Visas.<br /> | BASIC TABLE |
| [TF_NAV_PROFILE_CFGS](TF_NAV_PROFILE_CFGS.md) | 22 | Navigation Profiles Configurations - TF_NAV_PROFILE_CFGS<br /> | BASIC TABLE |
| [HR_COMPHYPOTHESISSPOT](HR_COMPHYPOTHESISSPOT.md) | 16 | Compensation Hypothesis Spot - This entity is used to see where scenario participants are placed against salary benchmarks before and after hypothesys. A “Spot” is a participant and includes the name, an additional dimension and the compensation amount.<br /> | BASIC TABLE |
| [TF_DASHBOARD_GALLERIES_ITEMS](TF_DASHBOARD_GALLERIES_ITEMS.md) | 12 | Dashboard Gallery Items - Dashboard Gallery Items<br /> | BASIC TABLE |
| [TF_EVENT_FOLLOWUPS](TF_EVENT_FOLLOWUPS.md) | 29 | Event Followups - The Event Followups.<br /> | BASIC TABLE |
| [TF_SEC_ADV_FILTERS_ROLE](TF_SEC_ADV_FILTERS_ROLE.md) | 16 | Advanced Security Filters Role - Advanced Security Filters Role<br /> | BASIC TABLE |
| [HR_SIMULATIONMODELS](HR_SIMULATIONMODELS.md) | 25 | Simulation Model -   A Simulation model includes all tools and best practices to manage a Simulation Scenario built on top of such model. For example, it defines how scenario participants will be initialised, which reporting dashboards will be used to analyse the “As Is” and “To Be” situations respectively, and which actions will allowed to plan participants hypothesis.<br /> | BASIC TABLE |
| [TF_INTEROP_RUNTIME_LOGS](TF_INTEROP_RUNTIME_LOGS.md) | 9 | Interop Runtime Logs - Interop Runtime Logs<br /> | BASIC TABLE |
| [HR_JOB](HR_JOB.md) | 17 | Job - Contains a collection of information relating to a job. A job can be thought of as a template for a position. A position is an instance of a job. Jobs describe the nature of the work, whereas related positions represent the time, place, and organizational structure in which a person or persons actually perform the work. Positions usually have a specific budget associated with them.<br /> | BASIC TABLE |
| [TF_EXTERNAL_USERS](TF_EXTERNAL_USERS.md) | 17 | External Users - External Users<br /> | BASIC TABLE |
| [TF_MAIL_LOGS](TF_MAIL_LOGS.md) | 11 | Mail logs - Mail logs entity<br /> | BASIC TABLE |
| [TF_TOPIC_RESOURCES](TF_TOPIC_RESOURCES.md) | 18 | Topic resources entity - Topic resources<br /> | BASIC TABLE |
| [TF_DW_NAMED_ENTITIES](TF_DW_NAMED_ENTITIES.md) | 19 | Intent Named Entities - Intent Named Entities<br /> | BASIC TABLE |
| [HR_TEAMRATINGREVIEWER](HR_TEAMRATINGREVIEWER.md) | 15 | Team Rating Reviewer - This entity records the reviewer for each group of an appraisal cycle.<br /> | BASIC TABLE |
| [TF_USERS](TF_USERS.md) | 66 | Users - The TF_USERS Entity<br /> | BASIC TABLE |
| [HR_STAGING_ABSACCRUAL](HR_STAGING_ABSACCRUAL.md) | 30 | Staging Individual Absence Accrual - This is an intermediate table between Talentia HCM and a Payroll system where accruals are temporarily stored before getting loaded into actual tables.<br /> | BASIC TABLE |
| [TF_ADV_GRID_RENDERERS](TF_ADV_GRID_RENDERERS.md) | 21 | Advanced Datagrid Renderer - Advanced Datagrid Renderer<br /> | BASIC TABLE |
| [HR_ACTIVITYCOSTFINANCING](HR_ACTIVITYCOSTFINANCING.md) | 20 | Activity Cost Financing - Contains the activity costs financing.<br /> | BASIC TABLE |
| [HR_EMPCALENDAREXCEPTION](HR_EMPCALENDAREXCEPTION.md) | 15 | Employee Calendar Exception - This entity is used to define a calendar for an employee and a given period, that is different from the default one defined for them by their location<br /> | BASIC TABLE |
| [HR_ARCA24ST_AGENDA](HR_ARCA24ST_AGENDA.md) | 23 | Arca24 Staging Table Agenda - Staging table for data coming from Arca24 - Agenda data.<br /> | BASIC TABLE |
| [HR_SALARYREVIEWITEM](HR_SALARYREVIEWITEM.md) | 29 | Salary Review Item - It’s a compensation item used for the salary review. Example, Base Salary.<br /> | BASIC TABLE |
| [HR_REMUNERATIONINPOINTSGRID](HR_REMUNERATIONINPOINTSGRID.md) | 31 | Compensation in points grid - Defines the pay grid in points<br /> | BASIC TABLE |
| [TF_BLPROPERTY_EXCEPTIONS](TF_BLPROPERTY_EXCEPTIONS.md) | 13 | Audit Fields - Audit Fields<br /> | BASIC TABLE |
| [HR_JOBCOMPETENCY](HR_JOBCOMPETENCY.md) | 16 | Job Competencies - This entity allows defining skills associated to a Job. These skills are descriptive and are not considered during the assessment to evaluate a job suitability.<br /> | BASIC TABLE |
| [HR_COLLECTIVEAGREEMENTPOINT](HR_COLLECTIVEAGREEMENTPOINT.md) | 15 | Collective Agreements Points - Collective Agreements Points Values Management<br /> | BASIC TABLE |
| [HR_COURSECOSTFINANCING](HR_COURSECOSTFINANCING.md) | 18 | Course Costs Financing - Contains the financing rule about course by cost type.<br /> | BASIC TABLE |
| [HR_PROFQUALIFICATIONS](HR_PROFQUALIFICATIONS.md) | 24 | Professional Qualifications - This entity maintains a list of professional qualifications, entitlements or certifications, both current and expired, regardless of whether they were achieved during the current employment or before.<br /> | BASIC TABLE |
| [HR_USERPRODUCTTALECOSYSTEM](HR_USERPRODUCTTALECOSYSTEM.md) | 16 | Talentia Ecosystem Products Assignment - Talentia Ecosystem Products Assignment to User<br /> | BASIC TABLE |
| [TF_USERS_PAT](TF_USERS_PAT.md) | 12 | Personal Access Tokens - Personal Access Tokens<br /> | BASIC TABLE |
| [TF_MAINTENANCE](TF_MAINTENANCE.md) | 21 | Maintenance - Represents a planned or ongoing maintenance process for the application. It is designed to monitor and manage the different phases of the maintenance lifecycle, including preparation, execution, and completion.<br /> | BASIC TABLE |
| [TF_BLPHYSICAL_COLUMNS](TF_BLPHYSICAL_COLUMNS.md) | 23 |  | BASIC TABLE |
| [HR_STAGING_DELETE_RESOURCES](HR_STAGING_DELETE_RESOURCES.md) | 25 | Documents to delete - STAGING_DELETE_RESOURCES<br /> | BASIC TABLE |
| [TF_TEMPLATERULE_CATALOG](TF_TEMPLATERULE_CATALOG.md) | 16 | Template Rule Catalog - Template Rule Catalog<br /> | BASIC TABLE |
| [HR_PERSONOTHERINFO](HR_PERSONOTHERINFO.md) | 16 | Person other information - Other Information about a Person.<br /> | BASIC TABLE |
| [HR_APPRAISALSECTION](HR_APPRAISALSECTION.md) | 52 | Appraisal Review Section - This entity represents a section of an individual appraisal review, where the section scores are recorded.<br /> | BASIC TABLE |
| [HR_GDPRREQUESTPERSON](HR_GDPRREQUESTPERSON.md) | 13 | GDPR Request Affected People - List of People referred to in a data privacy request .<br /> | BASIC TABLE |
| [HR_PAYINADVANCEREQUEST](HR_PAYINADVANCEREQUEST.md) | 16 | Pay in Advance Request - A request to be paid in advance.<br /> | BASIC TABLE |
| [HR_ARCA24ST_APPLICATION](HR_ARCA24ST_APPLICATION.md) | 17 | Arca24 Staging Table Application - Staging table for data coming from Arca24 - Application data.<br /> | BASIC TABLE |
| [TF_LICENSE_MESSAGES](TF_LICENSE_MESSAGES.md) | 7 | License Messages - License Messages<br /> | BASIC TABLE |
| [HR_ABSPLANENTITDETAIL](HR_ABSPLANENTITDETAIL.md) | 14 | Absence Plan Entitlement Detail - Individual absence plan detail.<br /> | BASIC TABLE |
| [TF_PROXY_SETTINGS](TF_PROXY_SETTINGS.md) | 9 | TF_PROXY_SETTINGS - TF_PROXY_SETTINGS<br /> | BASIC TABLE |
| [TF_SHARED_RESOURCES](TF_SHARED_RESOURCES.md) | 13 | Shared Resources - The Shared Resources.<br /> | BASIC TABLE |
| [HR_APPRAISALTYPE](HR_APPRAISALTYPE.md) | 30 | Appraisal Type - Defines information relating to an appraisal type such as the default form to be used for the specifc appraisal type and other properties, e.g. main component for the associated appraisals, eligibility group, security settings.<br /> | BASIC TABLE |
| [TF_CHARTER_NODES](TF_CHARTER_NODES.md) | 18 | Charter Nodes - Charter Nodes<br /> | BASIC TABLE |

## Stored procedures and functions

| Name | ReturnType | Arguments | Type |
| ---- | ------- | ------- | ---- |
| dbo.BASESALARYPENETRATION | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.BONUSPENETRATION | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.CR_PENETRATION | decimal | @CR_ID bigint, @PARTICCOM_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.fn_GetEntityName | nvarchar | @pEntityId char | SQL scalar function |
| dbo.fn_GetTableName | nvarchar | @pEntityId char | SQL scalar function |
| dbo.GETJSONPROP | nvarchar | @VALUE nvarchar, @PROPNAME nvarchar | SQL scalar function |
| dbo.GetTextIdFromText |  | @input nvarchar | SQL table-valued-function |
| dbo.HEADCOUNT_BY_LOCATION | int | @LOCATION_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.HR_APPLICANTSBYSTEPS_FILTER |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_diff_minutes | nvarchar | @startDate datetime, @endDate datetime | SQL scalar function |
| dbo.HR_fn_AbsSeniorityCLS | decimal | @pCompRelId bigint, @pDate datetime | SQL scalar function |
| dbo.HR_fn_AbsSeniorityLS | decimal | @pCompRelId bigint, @pDate datetime | SQL scalar function |
| dbo.HR_fn_AbsWTPOrder | int | @pRefDate date, @WTPDAILYDETAILS_ID bigint | SQL scalar function |
| dbo.HR_fn_CustomAbsWTPOrder | int | @pRefDate date, @WTPDAILYDETAILS_ID bigint, @WTP_ID bigint | SQL scalar function |
| dbo.HR_fn_d_AbsAwardPlanSeniority | decimal | @pAbsencePlan bigint, @pSeniority decimal | SQL scalar function |
| dbo.HR_fn_d_AbsProRateAtDate | decimal | @comprelId bigint, @pRefDate datetime | SQL scalar function |
| dbo.HR_fn_VirtualDateTable |  | @pStartDate nvarchar, @pEndDate nvarchar | SQL table-valued-function |
| dbo.HR_ft_AbsAccrualInit |  | @pAccrualStartDate nvarchar, @pAccrualEndDate nvarchar, @comprelId bigint, @pAbsPlanId bigint, @pAllowanceStartDate nvarchar, @pAllowanceEndDate nvarchar | SQL table-valued-function |
| dbo.HR_ft_AbsWTPOrder |  | @pRefDate date, @WTPDAILYDETAILS_ID bigint | SQL inline table-valued function |
| dbo.HR_ft_CustomAbsWTPOrder |  | @pRefDate date, @WTPDAILYDETAILS_ID bigint, @WTP_ID bigint | SQL inline table-valued function |
| dbo.HR_ft_WTPDetailByPeriod |  | @pStartDate nvarchar, @pEndDate nvarchar, @comprelId bigint, @IsSyncCal char | SQL table-valued-function |
| dbo.HR_HCM_MY_TEAM_FILTER |  | @LogonPersonId bigint, @LogonProfileId bigint | SQL table-valued-function |
| dbo.HR_HIER_MANAGER_FORMNAME_PIT | nvarchar | @COMPANYRELATIONSHIP_ID bigint, @REFERENCEDATE date | SQL scalar function |
| dbo.HR_HIER_MANAGER_FORMNAME_PIT_1 | nvarchar | @COMPANYRELATIONSHIP_ID bigint, @REFERENCEDATE date, @COMPANYRELATIONSHIP_EFFECTIVEFROM date, @COMPANYRELATIONSHIP_EFFECTIVETO date, @COMPANYRELATIONSHIP_PERSON_ID bigint | SQL scalar function |
| dbo.HR_HIER_MANAGER_PIT | bigint | @COMPANYRELATIONSHIP_ID bigint, @REFERENCEDATE date | SQL scalar function |
| dbo.HR_HIER_MANAGER_PIT_1 | bigint | @COMPANYRELATIONSHIP_ID bigint, @REFERENCEDATE date, @COMPANYRELATIONSHIP_EFFECTIVEFROM date, @COMPANYRELATIONSHIP_EFFECTIVETO date, @COMPANYRELATIONSHIP_PERSON_ID bigint | SQL scalar function |
| dbo.HR_HIST_FLAT_STRORG |  | @SNAPSHOT_DATE date, @LANGUAGE_ID int | SQL inline table-valued function |
| dbo.HR_MY_PEERS |  | @PERSON_ID bigint | SQL table-valued-function |
| dbo.HR_MY_PEERS_ALLDEPLOYMENTS |  | @PERSON_ID bigint | SQL table-valued-function |
| dbo.HR_MY_POOLS |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM |  | @PERSON_ID bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_FILTER |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_FILTER_1 |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_FILTER_2 |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_FILTER_DELEGATED |  | @LogonPersonId bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_STRUCTURE |  | @RootParty_ID bigint, @Structure_ID bigint, @StructureTYPE_ID bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_STRUCTURE_1 |  | @RootParty_ID bigint, @Structure_ID bigint, @StructureTYPE_ID bigint | SQL table-valued-function |
| dbo.HR_MY_TEAM_STRUCTURE_2 |  | @RootParty_ID bigint, @Structure_ID bigint, @StructureTYPE_ID bigint | SQL table-valued-function |
| dbo.HR_NextAnniversaryDate | date | @DATE date | SQL scalar function |
| dbo.HR_PARTY_TREE |  | @RootParty_ID bigint, @Structure_ID bigint | SQL inline table-valued function |
| dbo.HR_POOL_TREE |  | @RootParty_ID bigint | SQL inline table-valued function |
| dbo.HR_STRUCTURE_VIEW |  | @TableName nvarchar, @RootPartyId bigint, @EffectiveFrom date, @EffectiveTo date, @StructureId bigint, @IsLeaf smallint, @OperationId nvarchar, @EntitiSetId bigint | SQL inline table-valued function |
| dbo.HR_TraRequestHasFollowUp | int | @RequestId int | SQL scalar function |
| dbo.HR_UNIT_FILTER |  | @ORGUNIT_IDList nvarchar | SQL table-valued-function |
| dbo.HR_UNIT_TREE |  | @RootParty_ID bigint, @RefDate date | SQL inline table-valued function |
| dbo.HR_Z_GetAdmEvTransposedValue | nvarchar | @TaskId bigint, @RecordId bigint, @ItemCode nvarchar, @ItemReference nvarchar, @FieldType char, @FieldValue_Int bigint, @FieldValue_String nvarchar, @FieldValue_StringDesc nvarchar, @FieldValue_DateTime datetime, @FieldValue_Bool smallint, @FieldValue_Decimal decimal, @DefaultValue nvarchar | SQL scalar function |
| dbo.HR_Z_GetCompanyCode | nvarchar | @TaskID bigint, @PersonID bigint, @ReferenceDate datetime | SQL scalar function |
| dbo.HR_Z_GetEffDateOnClusterCode | datetime | @TaskID bigint, @PersonID bigint, @RecordID bigint, @ReferenceDate datetime, @ClusterCode char | SQL scalar function |
| dbo.HR_Z_GetEffectiveStartDate | datetime | @TaskID bigint, @PersonID bigint, @RecordID bigint, @ReferenceDate datetime, @EntityName nvarchar, @ClusterCode char | SQL scalar function |
| dbo.HR_Z_GetEmployeeID | nvarchar | @TaskID bigint, @PersonID bigint, @RecordID bigint, @ReferenceDate datetime | SQL scalar function |
| dbo.HR_Z_GetItemReference | nvarchar | @TaskId bigint, @RecordId bigint, @ItemCode nvarchar, @ItemReference nvarchar, @EntityName nvarchar, @FieldName nvarchar | SQL scalar function |
| dbo.HR_Z_GetTransposedFieldName | nvarchar | @TaskId bigint, @RecordId bigint, @EntityName nvarchar, @FieldName nvarchar | SQL scalar function |
| dbo.LENGHTOFSERVICE | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.MANAGERSINCE | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.TENUREPRIMARYJOB | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.TENUREPRIMARYPOSITION | decimal | @CR_ID bigint, @REFDATE datetime | SQL scalar function |
| dbo.TF_ALIGNALLLANGUAGES |  | @sourceLangId int | SQL Stored Procedure |
| dbo.TF_ALIGNAUDITFIELDS |  |  | SQL Stored Procedure |
| dbo.TF_ALIGNSPECIFICLANGUAGE |  | @SourceLangId int, @TargetLangId int | SQL Stored Procedure |
| dbo.TF_CHECK_SERIALIZED_MODEL_FLAG | bit | @serializedModel nvarchar, @flagName nvarchar | SQL scalar function |
| dbo.TF_GET_NESTED_PROP_CTX_VALUE | nvarchar | @VALUE nvarchar, @PROPNAME nvarchar, @CTXTYPE nvarchar, @CTXVALUE nvarchar | SQL scalar function |
| dbo.TF_GET_NESTED_PROPERTY_VALUE | nvarchar | @VALUE nvarchar, @PROPNAME nvarchar | SQL scalar function |
| dbo.TF_GET_PROPERTY_VALUE | nvarchar | @VALUE nvarchar, @PROPNAME nvarchar | SQL scalar function |
| dbo.TF_GET_TABLE_FROM_COLUMN | nvarchar | @columnId char | SQL scalar function |
| dbo.TF_HAS_CONTEXTUALIZATIONS | bit | @SERIALIZED_MODEL nvarchar | SQL scalar function |
| dbo.TF_HAS_CONTEXTUALIZED_PROPS | bit | @VALUE nvarchar, @PROPNAME nvarchar | SQL scalar function |
| dbo.TF_MARK_2_EXCLUDED_TRNSLTN |  | @LangId int | SQL Stored Procedure |
| dbo.TF_PROFILE_HAS_CUSTOM_AUTH | bit | @profileId bigint | SQL scalar function |
| dbo.TF_PROPERTY_LIST |  | @VALUE nvarchar | SQL table-valued-function |
| dbo.TF_REBUILD_AUDIT_TRIGGER |  | @Type int | SQL Stored Procedure |
| dbo.TF_SECGET_ACTUAL_PARENT_ID | char | @EntityName nvarchar | SQL scalar function |
| dbo.TF_TEXTRESOURCESTOTRANSLATE |  | @minManual int, @maxManual int, @minAuto int, @maxAuto int, @languageID int, @usersList nvarchar | SQL table-valued-function |
| dbo.TF_TRANSLATIONSTOTRANSLATE |  | @minManual int, @maxManual int, @minAuto int, @maxAuto int, @languageID int, @usersList nvarchar | SQL table-valued-function |
| dbo.TF_WFGETPREVACTORS | nvarchar | @wfid bigint | SQL scalar function |
| dbo.TF_WFGETPROCESSENTITIES | nvarchar | @id bigint | SQL scalar function |

## Relations

![er](schema.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
