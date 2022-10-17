## UserFeatureAccess
---
### Description
User Feature Access Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| raspAccess | User access status for RASP | boolean |  | false |
| serverlessAccess | User access status for Serverless | boolean |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"raspAccess":true,"serverlessAccess":true,"success":true}
```
