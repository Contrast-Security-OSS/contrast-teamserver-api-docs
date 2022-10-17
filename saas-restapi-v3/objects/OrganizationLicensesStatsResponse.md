## OrganizationLicensesStatsResponse
---
### Description
Organization Licenses Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assessment | Total number of licenses allocated | int |  | false |
| expiringAssessLicenses | List of expiration date grouped assess licenses | list |  | false |
| expiringProtectLicenses | List of expiration date grouped protect licenses | list |  | false |
| messages | List of messages | list |  | false |
| protection | Total number of licenses allocated | int |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_assessment | Total number of assessment licenses allocated | int |  | false |
| total_protection | Total number of protection licenses allocated | int |  | false |
| unlicensed_apps | Total number of unlicensed applications | int |  | false |
| unlicensed_servers | Total number of unlicensed servers | int |  | false |
### Template
```
{"assessment":0,"expiringAssessLicenses":[],"expiringProtectLicenses":[],"messages":[],"protection":0,"success":true,"total_assessment":0,"total_protection":0,"unlicensed_apps":0,"unlicensed_servers":0}
```
