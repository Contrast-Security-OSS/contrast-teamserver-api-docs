## RouteCoverageFilterRequest
---
### Description
Route coverage filter request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| excludedHashes | A list of route hashes to exclude from the action | list |  | false |
| applicationIds | Applications ids | list |  | false |
| startDate | Start date | long |  | false |
| endDate | End date | long |  | false |
| agentSessionId | Agent session ID which is the value shared with agents to associated elements to a given session | string |  | false |
| quickFilter | Route coverage quick filter type | quickfilterenum |  | false |
| sort | Sort by | sortenum |  | false |
| filterText | Filter text | string |  | false |
### Template
```
{"agentSessionId":"","applicationIds":[],"endDate":0,"excludedHashes":[],"filterText":"","quickFilter":"","sort":"","startDate":0}
```
