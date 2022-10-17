## ApplicationServerSettingsEnvironmentResponse
---
### Description
Application Server Settings Environment Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assessment | Assessment enabled for all servers | boolean |  | false |
| environment | Environment name | serverenvironment |  | false |
| messages | List of messages | list |  | false |
| protection | Protection enabled for all servers | boolean |  | false |
| servers | List of servers settings | list |  | false |
| servers_assessment | Number of servers with assessment enabled | long |  | false |
| servers_protection | Number of servers with protection enabled | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_servers | Number of servers | long |  | false |
### Template
```
{"assessment":true,"environment":"","messages":[],"protection":true,"servers":[],"servers_assessment":0,"servers_protection":0,"success":true,"total_servers":0}
```
