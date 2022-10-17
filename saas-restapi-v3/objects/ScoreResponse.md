## ScoreResponse
---
### Description
Score Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| scores | List of score Resources | ScoreResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"scores":{"grade":0,"letter_grade":"","library_scoring_type":"","links":[],"overall_scoring_type":"","platform":{"grade":0,"letter_grade":"","links":[]},"security":{"grade":0,"letter_grade":"","links":[]}},"success":true}
```
