## NgAssessmentLicenseBreakdownResponse
---
### Description
Assessment license breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| breakdown | License breakdown | AssessmentLicenseBreakdownResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"breakdown":{"enterpriseApps":0,"expirationUnusedDateLicenses":[],"expirationUsedDateLicenses":[],"links":[],"max_expiration_date":0,"nearing_expiration":0,"total":0,"trialApps":0,"unused":0,"used":0},"messages":[],"success":true}
```
