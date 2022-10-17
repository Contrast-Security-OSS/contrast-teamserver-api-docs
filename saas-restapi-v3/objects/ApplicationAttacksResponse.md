## ApplicationAttacksResponse
---
### Description
Application Attacks Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attacks | List of attacks | list |  | false |
| importance | Application Importance | string |  | false |
| messages | List of messages | list |  | false |
| status | Attack status | attackstatus |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"attacks":[],"importance":"","messages":[],"status":"","success":true}
```
