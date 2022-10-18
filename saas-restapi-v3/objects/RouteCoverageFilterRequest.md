## RouteCoverageFilterRequest
---
### Description
Route Coverage Filter Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentSessionId | Agent session ID which is the value shared with agents to associated elements to a given session | string |  | false |
| applicationIds | Unique IDs for applications | list |  | false |
| endDate | End Date | long |  | false |
| excludedHashes | A list of route hashes to exclude from the action | list |  | false |
| filterText | Filter Text | string |  | false |
| quickFilter | Route Coverage Quick Filter Type | routecoveragequickfiltertype |  | false |
| sort | Sort by | string |  | false |
| startDate | Start Date | long |  | false |
### Template
```
{"agentSessionId":"","applicationIds":[],"endDate":0,"excludedHashes":[],"filterText":"","quickFilter":"","sort":"","startDate":0}
```
