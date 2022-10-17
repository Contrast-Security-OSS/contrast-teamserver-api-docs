## NgProtectionLicenseBreakdownResponse
---
### Description
Protection license breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| breakdown | License breakdown | ProtectionLicenseBreakdownResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"breakdown":{"expirationUnusedDateLicenses":[],"expirationUsedDateLicenses":[],"links":[],"max_expiration_date":0,"nearing_expiration":0,"total":0,"unlicensedServers":0,"unused":0,"used":0},"messages":[],"success":true}
```
