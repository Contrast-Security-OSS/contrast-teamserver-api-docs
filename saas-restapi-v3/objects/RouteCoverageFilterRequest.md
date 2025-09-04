## RouteCoverageFilterRequest
---
### Description
Route coverage filter request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applicationIds | Applications ids | list |  | false |
| excludedHashes | A list of route hashes to exclude from the action | list |  | false |
| routeTypes | Route types to filter by | list |  | false |
| startDate | Start date | long |  | false |
| endDate | End date | long |  | false |
| agentSessionId | Agent session ID which is the value shared with agents to associated elements to a given session | string |  | false |
| quickFilter | Route coverage quick filter type | quickfilterenum |  | false |
| discoveredStartDate | Discovered start date | long |  | false |
| sort | Sort by | sortenum |  | false |
| filterText | Filter text | string |  | false |
| discoveredEndDate | Discovered end date | long |  | false |
### Template
```
{"agentSessionId":"","applicationIds":[],"discoveredEndDate":0,"discoveredStartDate":0,"endDate":0,"excludedHashes":[],"filterText":"","quickFilter":"","routeTypes":[],"sort":"","startDate":0}
```
