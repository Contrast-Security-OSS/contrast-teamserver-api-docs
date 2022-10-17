## SecurityScoreMetricResponse
---
### Description
Security Score Metric Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| score | Score Resource | ScoreMetricResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"score":{"grade":0,"letter_grade":"","links":[]},"success":true}
```
