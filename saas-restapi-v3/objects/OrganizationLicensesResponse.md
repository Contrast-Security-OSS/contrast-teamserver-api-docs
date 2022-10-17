## OrganizationLicensesResponse
---
### Description
Organization Licenses Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| enterpriseApps | Number of enterprise applications | int |  | false |
| expirationDateLicenses | List of expiration date grouped licenses | list |  | false |
| expirationUnusedDateLicenses | List of expiration date grouped unused licenses | list |  | false |
| licenses | Number of licenses | integer |  | false |
| messages | List of messages | list |  | false |
| nearExpiration | Number of licenses near expiration | integer |  | false |
| nearing_expiration | Total nearing expiration licenses assigned | int |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| trialApps | Number of trial applications | int |  | false |
| usedLicenses | Number of used licenses | int |  | false |
### Template
```
{"enterpriseApps":0,"expirationDateLicenses":[],"expirationUnusedDateLicenses":[],"licenses":0,"messages":[],"nearExpiration":0,"nearing_expiration":0,"success":true,"trialApps":0,"usedLicenses":0}
```
