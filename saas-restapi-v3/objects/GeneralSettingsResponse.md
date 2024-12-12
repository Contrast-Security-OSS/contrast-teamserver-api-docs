## GeneralSettingsResponse
---
### Description
Base API form Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| restrictedEditRoleEnabled | true if restricted edit role is allowed, false otherwise | boolean |  | false |
| aimlServiceEnabled | true if AIML Service is enabled, false otherwise | boolean |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| isEOP | true if Teamserver is running in EOP mode, false otherwise | boolean |  | false |
| agentUrl | Url for Agent Traffic | string |  | false |
| diagnosticsCollectionEnabled | true if restricted edit role is allowed, false otherwise | boolean |  | false |
| messages | List of messages | list |  | false |
### Template
```
{"agentUrl":"","aimlServiceEnabled":true,"diagnosticsCollectionEnabled":true,"isEOP":true,"messages":[],"restrictedEditRoleEnabled":true,"success":true}
```
