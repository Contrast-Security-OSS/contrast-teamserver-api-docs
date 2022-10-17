## ScoreResource
---
### Description
Score Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| grade | Grade | integer |  | false |
| letter_grade | Letter grade | string |  | false |
| library_scoring_type | Library Scoring Type | libraryscoringtype |  | false |
| overall_scoring_type | Overall Scoring Type | overallscoringtype |  | false |
| platform | Platform Score | ScoreMetricResource |  | false |
| security | Security Score | ScoreMetricResource |  | false |
### Template
```
{"grade":0,"letter_grade":"","library_scoring_type":"","links":[],"overall_scoring_type":"","platform":{"grade":0,"letter_grade":"","links":[]},"security":{"grade":0,"letter_grade":"","links":[]}}
```
