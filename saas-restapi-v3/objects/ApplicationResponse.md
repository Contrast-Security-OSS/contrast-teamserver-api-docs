## ApplicationResponse
---
### Description
Response that returns the application information
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| success | Indicates whether API response was successful or not | boolean |  | false |
| application |  | applicationresource |  | false |
| messages | List of messages | list |  | false |
### Template
```
{"application":{"appArchived":true,"appContext":"","appDisplayName":"","appId":"","appLanguage":"","appName":"","importance":"","lastSeen":0,"parentAppId":"","status":""},"messages":[],"success":true}
```
