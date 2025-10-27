## ApplicationResource
---
### Description
Resource that contains the information about the application object
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| appId |  | string |  | false |
| importance |  | applicationimportance |  | false |
| appName |  | string |  | false |
| appDisplayName |  | string |  | false |
| lastSeen |  | long |  | false |
| appArchived |  | boolean |  | false |
| appContext |  | string |  | false |
| parentAppId |  | string |  | false |
| status |  | string |  | false |
| appLanguage |  | agentlanguage |  | false |
### Template
```
{"appArchived":true,"appContext":"","appDisplayName":"","appId":"","appLanguage":"","appName":"","importance":"","lastSeen":0,"parentAppId":"","status":""}
```
