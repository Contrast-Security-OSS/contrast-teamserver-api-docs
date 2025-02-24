## OrgTraceBulkMarkStatusRequest
---
### Description
Organization Trace Bulk Mark Status Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| filters | Filters that describe the org traces to change status for | OrgTraceBulkFilterRequest |  | true |
| note | Note | string |  | false |
| status | New status | string |  | true |
| substatus | New sub-status | string |  | false |
### Template
```
{"filters":{"agentSessionId":"","appVersionTags":[],"applicationID":"","applicationIds":[],"applicationImportances":[],"applicationMetadataFilters":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","languages":[],"licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"protectStatuses":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"technologies":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]},"note":"","status":"","substatus":""}
```
