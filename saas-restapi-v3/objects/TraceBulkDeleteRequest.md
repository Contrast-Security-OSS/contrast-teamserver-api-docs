## TraceBulkDeleteRequest
---
### Description
Trace Bulk Delete Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| filters | Filters that describe the traces to delete | OrgTraceBulkFilterRequest |  | true |
### Template
```
{"filters":{"appVersionTags":[],"applicationID":"","applicationIds":[],"applicationImportances":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","languages":[],"licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"technologies":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]}}
```
