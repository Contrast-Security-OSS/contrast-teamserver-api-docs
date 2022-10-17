## AttackMonitorStatsResponse
---
### Description
Attack Monitor Statistics Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| apps | Total number of applications | long |  | false |
| errors | List of errors | list |  | false |
| highRiskApps | Total number of applications with open critical or high vulnerabilities | long |  | false |
| messages | List of messages | list |  | false |
| protectedApps | Total number of applications with protection enabled | long |  | false |
| requestsPerSecond | Average number of requests seen by all apps each second | long |  | false |
| servers | Total number of servers | long |  | false |
| serversProtected | Total number of protected servers | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| totalProductionApps | Total number of applications on production servers | long |  | false |
| totalProductionServers | Total number of production servers | long |  | false |
### Template
```
{"apps":0,"errors":[],"highRiskApps":0,"messages":[],"protectedApps":0,"requestsPerSecond":0,"servers":0,"serversProtected":0,"success":true,"totalProductionApps":0,"totalProductionServers":0}
```
