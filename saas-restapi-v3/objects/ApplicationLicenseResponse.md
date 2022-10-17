## ApplicationLicenseResponse
---
### Description
Application License Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| license | License | ApplicationLicenseResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"license":{"end":0,"level":"","links":[],"near_expiration":true,"start":0},"messages":[],"success":true}
```
