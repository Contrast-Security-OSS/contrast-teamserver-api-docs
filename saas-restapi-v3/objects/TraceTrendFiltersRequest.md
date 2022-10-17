## TraceTrendFiltersRequest
---
### Description
Vulnerability Trend Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| allApplications | Apply to all applications? | boolean |  | false |
| allRules | Apply to all rules? | boolean |  | false |
| allServers | Apply to all servers? | boolean |  | false |
| appTags | List of Application Tags | set |  | false |
| appVersions | List of Application Versions | set |  | false |
| applicationImportance | List of Application Importance | set |  | false |
| applications | List of Applications | set |  | false |
| ruleSeverities | List of Rule Severities | set |  | false |
| rules | List of Rules | set |  | false |
| securityStandards | List of Security Standards | set |  | false |
| serverEnvironments | List of Server Environments | set |  | false |
| serverTags | List of Server Tags | set |  | false |
| servers | List of Servers | set |  | false |
| vulnTags | List of Vulnerability Tags | set |  | false |
### Template
```
{"allApplications":true,"allRules":true,"allServers":true,"appTags":[],"appVersions":[],"applicationImportance":[],"applications":[],"ruleSeverities":[],"rules":[],"securityStandards":[],"serverEnvironments":[],"serverTags":[],"servers":[],"vulnTags":[]}
```
