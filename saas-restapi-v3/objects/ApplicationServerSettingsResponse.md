## ApplicationServerSettingsResponse
---
### Description
Application Server Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| serverSettingsEnvironment | List of servers settings by environment | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_assessment | Total number of servers with assessment enabled | long |  | false |
| total_protection | Total number of servers with protection enabled | long |  | false |
| total_protection_servers | Total number of servers with protection license | long |  | false |
| total_servers | Total number of servers | long |  | false |
### Template
```
{"messages":[],"serverSettingsEnvironment":[],"success":true,"total_assessment":0,"total_protection":0,"total_protection_servers":0,"total_servers":0}
```
