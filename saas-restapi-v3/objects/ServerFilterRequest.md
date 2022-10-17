## ServerFilterRequest
---
### Description
Server Filter Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentVersions | Agent Versions | array |  | false |
| applicationsIds | Application IDs | array |  | false |
| logLevels | Log Levels | array |  | false |
| q | Name, Hostname or Server Path | string |  | false |
| quickFilter | Quick Filter | serverquickfiltertype |  | false |
| serverEnvironments | Server Environments | array |  | false |
| tags | Tags | array |  | false |
### Template
```
{"agentVersions":[],"applicationsIds":[],"logLevels":[],"q":"","quickFilter":"","serverEnvironments":[],"tags":[]}
```
