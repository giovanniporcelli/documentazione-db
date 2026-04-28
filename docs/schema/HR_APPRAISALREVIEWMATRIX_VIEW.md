# HR_APPRAISALREVIEWMATRIX_VIEW

## Description

Scores Matrix - With this entity, you can access all individual performance scores between two dates for a Person, across two set of columns representing X Score and Y Score. This entity is suitable to be used in a Matrix Wizard to create, for example, 9 box analytics.  


<details>
<summary><strong>Table Definition</strong></summary>

```sql
-- Talentia Software - All right reserved
-- Type: VIEW                     Name: HR_APPRAISALREVIEWMATRIX_VIEW
-- Date: 09-04-2026 07:27:59 (UTC)
-- 
-- ChangeLogId: 00000000-0000-0000-0000-000000000000
-- ChangeSetId: b5c55324-e9c6-4f6d-a9ac-41c4390129d3
-- Original file name: C:\repos\Talentia-Software\hcm-core/DB/ProductDB/EDM\Schema\Views\HR_APPRAISALREVIEWMATRIX_VIEW.xml


CREATE VIEW [HR_APPRAISALREVIEWMATRIX_VIEW]
 ( EFFECTIVEFROM, EFFECTIVETO, PERSON_ID, COMPANYRELATIONSHIP_ID, XCYCLEID, XAPPRAISALTYPEID, XREVIEWID, XISMAINREVIEW, XISSUMMARYREVIEW, XAPPRAISALROLEID, XREVIEWSTATEID, XAPPRAISALCOMPONENTID, XCOMPONENTID, XRATINGID, XRATINGADJUSTEDID, XNORMRATINGID, XNORMRATINGADJUSTEDID, XSCORE, XSCOREADJUSTED, XSCOREPERCENTAGE, XSCOREPERCENTAGEADJUSTED, XCALIBRATEDRATINGID, XNORMCALIBRATEDRATINGID, YCYCLEID, YAPPRAISALTYPEID, YREVIEWID, YISMAINREVIEW, YISSUMMARYREVIEW, YAPPRAISALROLEID, YREVIEWSTATEID, YAPPRAISALCOMPONENTID, YCOMPONENTID, YRATINGID, YRATINGADJUSTEDID, YNORMRATINGID, YNORMRATINGADJUSTEDID, YSCORE, YSCOREADJUSTED, YSCOREPERCENTAGE, YSCOREPERCENTAGEADJUSTED, YCALIBRATEDRATINGID, YNORMCALIBRATEDRATINGID ) 
 AS 
( SELECT (Case when X.EFFECTIVEFROM<Y.EFFECTIVEFROM THEN Y.EFFECTIVEFROM else X.EFFECTIVEFROM END) as EFFECTIVEFROM,
(Case when X.EFFECTIVETO<Y.EFFECTIVETO THEN X.EFFECTIVETO else Y.EFFECTIVETO END) as EFFECTIVETO,
X.PERSON_ID,
X.COMPANYRELATIONSHIP_ID,
X.APPRAISALCYCLE_ID as XCYCLEID,
X.APPRAISALTYPE_ID as XAPPRAISALTYPEID,
X.REVIEW_ID as XREVIEWID,
X.IS_MAIN as XISMAINREVIEW,
X.IS_SUMMARY as XISSUMMARYREVIEW,
X.APPRAISALROLE_ID as XAPPRAISALROLEID,
X.REVIEWSTATE_ID as XREVIEWSTATEID,
X.APPRAISALCOMPONENTID as XAPPRAISALCOMPONENTID, 
X.ASSESMENTCOMPONENT_ID as XCOMPONENTID, 
X.SCALEVALUE_ID as XRATINGID,
X.SCALEVALUEADJ_ID as XRATINGADJUSTEDID,
X.NORMSCALEVALUE_ID as XNORMRATINGID,
X.NORMSCALEVALUEADJ_ID as XNORMRATINGADJUSTEDID,
X.SCORE as XSCORE,
X.SCOREADJ as XSCOREADJUSTED,
X.SCOREPERCENTAGE as XSCOREPERCENTAGE,
X.SCOREPERCENTAGEADJ as XSCOREPERCENTAGEADJUSTED,
X.CALIBRATEDRATING_ID as XCALIBRATEDRATINGID,
X.NORMCALIBRATEDRATING_ID as XNORMCALIBRATEDRATINGID,
Y.APPRAISALCYCLE_ID as YCYCLEID,
Y.APPRAISALTYPE_ID as YAPPRAISALTYPEID,
Y.REVIEW_ID as YREVIEWID,
Y.IS_MAIN as YISMAINREVIEW,
Y.IS_SUMMARY as YISSUMMARYREVIEW,
Y.APPRAISALROLE_ID as YAPPRAISALROLEID ,
Y.REVIEWSTATE_ID as YREVIEWSTATEID,
Y.APPRAISALCOMPONENTID as YAPPRAISALCOMPONENTID,
Y.ASSESMENTCOMPONENT_ID as YCOMPONENTID,
Y.SCALEVALUE_ID as YRATINGID,
Y.SCALEVALUE_ID as YRATINGADJUSTEDID,
Y.NORMSCALEVALUE_ID as YNORMRATINGID,
Y.NORMSCALEVALUEADJ_ID as YNORMRATINGADJUSTEDID,
Y.SCORE as YSCORE,
Y.SCOREADJ as YSCOREADJUSTED,
Y.SCOREPERCENTAGE as YSCOREPERCENTAGE,
Y.SCOREPERCENTAGEADJ as YSCOREPERCENTAGEADJUSTED,
Y.CALIBRATEDRATING_ID as YCALIBRATEDRATINGID,
Y.NORMCALIBRATEDRATING_ID as YNORMCALIBRATEDRATINGID
from HR_APPRAISALREVIEWCOMP_VIEW X
Inner join HR_APPRAISALREVIEWCOMP_VIEW Y
on (X.PERSON_ID=Y.PERSON_ID) and (X.COMPANYRELATIONSHIP_ID=Y.COMPANYRELATIONSHIP_ID)
and (X.APPRAISALCOMPONENTID<>Y.APPRAISALCOMPONENTID) )

```

</details>

## Columns

| Name | Type | Default | Nullable | Comment |
| ---- | ---- | ------- | -------- | ------- |
| EFFECTIVEFROM | date |  | true | The validity start date for an historical situation. |
| EFFECTIVETO | date |  | true | The validity end date for an historical situation. |
| PERSON_ID | bigint |  | true | The Identifier of the Person record. |
| COMPANYRELATIONSHIP_ID | bigint |  | true | The Identifier of the Company Relationship record. |
| XCYCLEID | bigint |  | true | Reference to the Appraisal Cycle where the X Score was collected. |
| XAPPRAISALTYPEID | bigint |  | false | Reference to the Appraisal Type where the X Score was collected. |
| XREVIEWID | bigint |  | false | Identifier of the Appraisal Review where the X Score was collected. |
| XISMAINREVIEW | smallint |  | true | States if the Review where the score X comes from is the Primary/Main review. |
| XISSUMMARYREVIEW | smallint |  | true | States if the review where the score X comes from is the Summary review. |
| XAPPRAISALROLEID | bigint |  | true | Reference to the Appraisal Role who gave the X Score. |
| XREVIEWSTATEID | bigint |  | true | The state of the review where the X Score comes from. Can be Submitted or Draft. |
| XAPPRAISALCOMPONENTID | bigint |  | false | Reference to the X component score in the individual appraisal. |
| XCOMPONENTID | bigint |  | false | Reference to the X Score library component. |
| XRATINGID | bigint |  | true | X discrete score rating. |
| XRATINGADJUSTEDID | bigint |  | true | X discrete score adjusted rating. |
| XNORMRATINGID | bigint |  | true | X discrete score normalised rating. |
| XNORMRATINGADJUSTEDID | bigint |  | true | X discrete score rating adjusted and normalised. |
| XSCORE | decimal |  | true | Numeric X Score |
| XSCOREADJUSTED | decimal |  | true | Numeric X Score adjusted. |
| XSCOREPERCENTAGE | decimal |  | true | X Score expressed as a percentage. |
| XSCOREPERCENTAGEADJUSTED | decimal |  | true | X Score adjusted as a percentage. |
| XCALIBRATEDRATINGID | bigint |  | true | X Calibrated score scale value |
| XNORMCALIBRATEDRATINGID | bigint |  | true | X Normalized Calibrated score scale value |
| YCYCLEID | bigint |  | true | Reference to the Appraisal Cycle where the Y Score was collected. |
| YAPPRAISALTYPEID | bigint |  | false | Reference to the Appraisal Type of the Y Score was collected. |
| YREVIEWID | bigint |  | false | Identifier of the Appraisal Review where the Y Score was collected. |
| YISMAINREVIEW | smallint |  | true | States if the Review where the score Y comes from is the primary/main review. |
| YISSUMMARYREVIEW | smallint |  | true | States if the Review where the score Y comes from is the Summary review. |
| YAPPRAISALROLEID | bigint |  | true | Reference to the Appraisal Role who gave the Y Score. |
| YREVIEWSTATEID | bigint |  | true | The state of the Review where the Y Score comes from. Can be Submitted or Draft. |
| YAPPRAISALCOMPONENTID | bigint |  | false | Reference to the Y component score in the individual appraisal. |
| YCOMPONENTID | bigint |  | false | Reference to the Y Score library component. |
| YRATINGID | bigint |  | true | Y discrete score rating. |
| YRATINGADJUSTEDID | bigint |  | true | Y discrete score adjusted rating. |
| YNORMRATINGID | bigint |  | true | Y discrete score rating normalised. |
| YNORMRATINGADJUSTEDID | bigint |  | true | Y discrete score adjusted rating and normalised. |
| YSCORE | decimal |  | true | Numeric Y Score |
| YSCOREADJUSTED | decimal |  | true | Numeric Y Score adjusted. |
| YSCOREPERCENTAGE | decimal |  | true | Y Score expressed as a percentage. |
| YSCOREPERCENTAGEADJUSTED | decimal |  | true | Y Score adjusted as a percentage. |
| YCALIBRATEDRATINGID | bigint |  | true | Y Calibrated score scale value |
| YNORMCALIBRATEDRATINGID | bigint |  | true | Y Normalized calibrated scale value |

## Referenced Tables

| Name | Columns | Comment | Type |
| ---- | ------- | ------- | ---- |
| [HR_APPRAISALREVIEWCOMP_VIEW](HR_APPRAISALREVIEWCOMP_VIEW.md) | 25 |  | VIEW |

## Relations

![er](HR_APPRAISALREVIEWMATRIX_VIEW.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)
