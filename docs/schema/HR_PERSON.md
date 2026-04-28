# HR_PERSON

## Description

Person - Contains information identifying the person.  


## Columns

| Name | Type | Default | Nullable | Children | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- |
| ID | bigint |  | false | [HR_PUBLICSPEAKINGEVENTS](HR_PUBLICSPEAKINGEVENTS.md) [HR_SHORTLISTEDCND](HR_SHORTLISTEDCND.md) [HR_PERSONSOCIALNETWORKS](HR_PERSONSOCIALNETWORKS.md) [HR_GRIEVANCES](HR_GRIEVANCES.md) [HR_TRAININGPOOL](HR_TRAININGPOOL.md) [HR_COMPANYRELATIONSHIP](HR_COMPANYRELATIONSHIP.md) [HR_ADMINEVENTHEADER](HR_ADMINEVENTHEADER.md) [HR_SCORECOMPONENTPROFILE](HR_SCORECOMPONENTPROFILE.md) [HR_PERSONACCOUNTABILITY](HR_PERSONACCOUNTABILITY.md) [HR_FAMILYANDDEPENDENTS](HR_FAMILYANDDEPENDENTS.md) [HR_INDIVIDUALPLANENROLMENT](HR_INDIVIDUALPLANENROLMENT.md) [HR_OTHERCOMPETENCIES](HR_OTHERCOMPETENCIES.md) [HR_PERSONADDRESSES](HR_PERSONADDRESSES.md) [HR_CONTRACTTYPEASSIGNMENT](HR_CONTRACTTYPEASSIGNMENT.md) [HR_BENEFITSASSIGNMENT](HR_BENEFITSASSIGNMENT.md) [HR_CANDIDATE](HR_CANDIDATE.md) [HR_LEARNER](HR_LEARNER.md) [HR_PERSONALPUBLICATIONS](HR_PERSONALPUBLICATIONS.md) [HR_APPLICANT](HR_APPLICANT.md) [HR_TIMETRACKERPROJECTTEAM](HR_TIMETRACKERPROJECTTEAM.md) [HR_PERSONALTRAININGHISTORY](HR_PERSONALTRAININGHISTORY.md) [HR_DISCIPLINARYEVENTS](HR_DISCIPLINARYEVENTS.md) [HR_COMPETENCYPROFILE](HR_COMPETENCYPROFILE.md) [HR_PERSONALTSCRIPTNAMES](HR_PERSONALTSCRIPTNAMES.md) [HR_CALIBRATIONPOOL](HR_CALIBRATIONPOOL.md) [HR_CAREERASPIRATIONS](HR_CAREERASPIRATIONS.md) [HR_DOCTORDETAILS](HR_DOCTORDETAILS.md) [HR_LANGUAGESKILLS](HR_LANGUAGESKILLS.md) [HR_PERSONBANKDETAILS](HR_PERSONBANKDETAILS.md) [HR_SALARYPROGPOOL](HR_SALARYPROGPOOL.md) [HR_GDPRREQUEST](HR_GDPRREQUEST.md) [HR_TIMESHEET](HR_TIMESHEET.md) [HR_PERSONCITIZENSHIPS](HR_PERSONCITIZENSHIPS.md) [HR_TRAINSTRUCTORS](HR_TRAINSTRUCTORS.md) [HR_SALARYREVIEWPARTICIPANT](HR_SALARYREVIEWPARTICIPANT.md) [HR_EDUCATIONHISTORY](HR_EDUCATIONHISTORY.md) [HR_PERSONCONTACTS](HR_PERSONCONTACTS.md) [HR_PREFTIMETRACKINGACT](HR_PREFTIMETRACKINGACT.md) [HR_EMERGENCYCONTACTS](HR_EMERGENCYCONTACTS.md) [HR_PREVEMPLOYMENTHISTORY](HR_PREVEMPLOYMENTHISTORY.md) [HR_PERSONMEDICALDETAILS](HR_PERSONMEDICALDETAILS.md) [HR_LICENSEPERMITVISA](HR_LICENSEPERMITVISA.md) [HR_PROFQUALIFICATIONS](HR_PROFQUALIFICATIONS.md) [HR_PERSONOTHERINFO](HR_PERSONOTHERINFO.md) [HR_GDPRREQUESTPERSON](HR_GDPRREQUESTPERSON.md) | Indicates the unique identifier |
| FIRSTNAME | nvarchar(100) |  | false |  | The Person's given, or first, name. |
| MIDDLENAME | nvarchar(100) |  | true |  | The Person's middle name. |
| FAMILYNAME | nvarchar(100) |  | false |  | Contains a non-given name. This is an inherited name or one representing a family relationship or in some cultural contexts a Place Name (where someone is from). In some cultural contexts, a single family name is typical, while in others there may be multiple family names. . |
| MAIDENNAME | nvarchar(100) |  | true |  | A previous family name, such as a maiden name, which is a family name prior to marriage and assuming a spouse's name. |
| PREFERREDNAME | nvarchar(100) |  | true |  | The name by which the person prefers to be called. |
| PREFERREDSALUTATIONCODE | nvarchar(50) |  | true |  | Contains a preferred form of address or salutation. For, example, Mr, Mrs, Ms, Dr, etc. |
| INITIALS | nvarchar(50) |  | true |  | A letter or series of letters representing the first letter in each name part. |
| TITLEAFFIX | nvarchar(50) |  | true |  | Could be used to accompany the name of the person with some descent title. |
| QUALIFICATIONAFFIX | nvarchar(100) |  | true |  | Usually an abreviation representing a qualification (a degree or certification, for example) held by a person. For example, BA, BSc, Beng, MSc, MD, RN, CPA, PhD, etc. |
| GENERATIONAFFIX | nvarchar(100) |  | true |  | A portion of a name indicating generation Sr., Jr., III (the third), etc. |
| FORMATTEDNAME | nvarchar(1024) |  | true |  | This is the complete name of a person, made up of the constituent parts (i.e. Family Name, Given Name). The formatCode is an optional attribute which specifies the applicable format. In the case of the Formatted Name of a person, some example formatCodes could be: ''Family Name, Given Name'', ''Given Name Middle Initial Family Name'' or ''First Initial. Family Name''. |
| FORMATTEDCODE | nvarchar(1024) |  | true |  | Formatted Code description |
| LEGALNAME | nvarchar(1024) |  | true |  | Legal name used for legal documentation or other legal purposes. Contains, in one string, a fully formatted name with all of its pieces in their proper place. This includes all of the necessary punctuation. |
| PRIMARYLEGALIDENTIFIER | nvarchar(100) |  | true |  | An identifier issued to a person by a government organization. For example, a social insurance number or driver's license number. The schemeName typically would be used to reference the type of identifier (e.g., SSN, NC Drivers License) and the schemeAgencyID would be used to identify the issuing agency as necessary. |
| PRIMARYLEGALIDENTIFIERKEY | nvarchar(100) |  | true |  | Key of Primary legal Identifier |
| LEGALIDENTIFIERTYPE_ID | bigint |  | true |  | The Identifier of the Document Type record. |
| GENDER_ID | bigint |  | false |  | A code specifying gender. This list includes NotSpecified, which is different from the OAGIS gender list. |
| BIRTHDATE | datetime |  | false |  | The date on which the person was born. |
| BIRTHPLACE | nvarchar(100) |  | true |  | Indicates the place where the person was born. |
| BIRTHCOUNTRY_ID | bigint |  | true |  | Country of Birth |
| BIRTHCOUNTRYSUB | nvarchar(100) |  | true |  | Indicates the County where a person was born. |
| BIRTHCITY | nvarchar(100) |  | true |  | Indicates the City where a person was born. |
| MARITALSTATUS_ID | bigint |  | true |  | A set of codes classifying a person's marital status. This is an HR-XML Open List. Standard effective dating and a certified date are available as attributes. Enumerated values are: Domestic Partner Divorced Married Unreported Separated Unmarried Widowed Legally Separated. |
| MILITARYSTATUS_ID | bigint |  | true |  | A code classifiying a person's current or past military status. Depending on the use case and applicable law, employers may need to track a varity of different information regarding a person's current or military status. Under applicable law, current or prior military personnel may be entitled to certain employment preferences. |
| DEATHDATE | datetime |  | true |  | The date on which the associated person died. |
| PRIMARYLANG_ID | bigint |  | true |  | The primary or preferred language associated with a person or work environment. |
| NATIONALITY_ID | bigint |  | true |  | The Identifier of the Nationality record. |
| ETHNICITY_ID | bigint |  | true |  | A code classifying a person on the basis of their ethnicity. Ethnicity pertains to having common racial, cultural, religious, or linguistic characteristics. Ethnicity classifications may be relevant under government labor or fair employment practice regulations. For example, under U.S. record keeping rules for federal Contractors employers may require reporting of data with respect to whether or not a person is of Hispanic or Latino ethnicity, a classification which encompass persons of Mexican, Puerto Rican, Cuban, Central or South American, or other Spanish culture or origin, regardless of race. |
| RACE_ID | bigint |  | true |  | The Identifier of the Race record. |
| TOBACCOUSERINDICATOR | smallint |  | true |  | Indicates if the Person is a smoker. |
| STUDENTINDICATOR | smallint |  | true |  | An indicator as to whether the Person is currently enrolled as a student within a specific class of educational institution. This is component is attributed with effective dating. A typeCode attribute is available to make fine-grain distinctions such as Full Time or Part Time status. |
| SECONDLASTNAME | nvarchar(100) |  | true |  | Second Last Name. |
| PROVINCENAF | nvarchar(2) |  | true |  | Affiliation Number (PROV) |
| AFFILIATIONNAF | nvarchar(8) |  | true |  | Affiliation number |
| CONTROLENAF | nvarchar(2) |  | true |  | Affiliation number (DC) |
| WARNAME | nvarchar(100) |  | true |  | Used in Portugal. It is another way to format the full name of the Person. |
| NICKNAME | nvarchar(100) |  | true |  | Nickname |
| PICTURE | varbinary(MAX) |  | true |  | This field contains the full Personal Picture, before any crop. |
| PICTURE | vector |  | true |  |  |
| THUMBNAIL | varbinary(MAX) |  | true |  | This is a small verson of the Person's picture, obtained by cropping and reducing the original in size. |
| THUMBNAIL | vector |  | true |  |  |
| ABOUTME | nvarchar(MAX) |  | true |  | This field can be used by an Employee to introduce themselves. |
| INDDRIVINGLICENSE | smallint |  | true |  | Indicates if the person has a valid Driving License. |
| CODDRIVINGLICENCECODE | nvarchar(50) |  | true |  | Driving License Number |
| SHAREDIDENTIFIER | nvarchar(255) |  | true |  | Shared Identifier |
| LISTAGENCY_ID | bigint |  | true |  | The Identifier of List Agency. |
| WORKFLOW_ID | bigint |  | true |  | Indicates the workflow unique identifier |
| INSERT_TIME | datetime2 | (sysutcdatetime()) | false |  | Indicates the date and time of creation |
| INSERT_USER | nvarchar(100) | (N'MAIN') | false |  | Indicates the user who has created it |
| INSERT_CLIENT | nvarchar(50) | (N'localhost') | false |  | Indicates the IP address from which it was created |
| UPDATE_TIME | datetime2 | (sysutcdatetime()) | false |  | Indicates the date and time of last update operation |
| UPDATE_USER | nvarchar(100) | (N'MAIN') | false |  | Indicates the user who has executed last update |
| UPDATE_CLIENT | nvarchar(50) | (N'localhost') | false |  | Indicates the IP address from which was executed last update |
| UPDATE_COUNT | int | ((0)) | false |  | Indicates how many update was executed since its creation |
| NBRFAMILYANDDEP | int |  | true |  | Number of dependents |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| PK_PERSON | PRIMARY KEY | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |

## Indexes

| Name | Definition |
| ---- | ---------- |
| PK_PERSON | CLUSTERED, unique, part of a PRIMARY KEY constraint, [ ID ] |
| IDX_PERSON_STANDARD | NONCLUSTERED, unique, [ FIRSTNAME, FAMILYNAME, GENDER_ID, BIRTHDATE, WARNAME, SECONDLASTNAME ] |
| IDX_PERSON_LEGAL | NONCLUSTERED, unique, [ PRIMARYLEGALIDENTIFIER, LEGALIDENTIFIERTYPE_ID ] |
| IDX_PERSON_FORMATTEDNAME | NONCLUSTERED, [ FORMATTEDNAME ] |
| IDX_PERSON_BIRTHCOUNTRY | NONCLUSTERED, [ BIRTHCOUNTRY_ID ] |
| IDX_PERSON_ETHNICITY | NONCLUSTERED, [ ETHNICITY_ID ] |
| IDX_PERSON_GENDER | NONCLUSTERED, [ GENDER_ID ] |
| IDX_PERSON_LEGALIDENTIFIERTYPE | NONCLUSTERED, [ LEGALIDENTIFIERTYPE_ID ] |
| IDX_PERSON_MARITALSTATUS | NONCLUSTERED, [ MARITALSTATUS_ID ] |
| IDX_PERSON_MILITARYSTATUS | NONCLUSTERED, [ MILITARYSTATUS_ID ] |
| IDX_PERSON_NATIONALITY | NONCLUSTERED, [ NATIONALITY_ID ] |
| IDX_PERSON_PRIMARYLANG | NONCLUSTERED, [ PRIMARYLANG_ID ] |
| IDX_PERSON_RACE | NONCLUSTERED, [ RACE_ID ] |
| IDX_PERSON_SHAREDIDENTIFIER | NONCLUSTERED, [ SHAREDIDENTIFIER ] |

## Relations

![er](HR_PERSON.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
