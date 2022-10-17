## OrgTraceBulkEmailRequest
---
### Description
Organization Trace Bulk Email Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| emailAddress | The email address to send traces to | string |  | true |
| filters | Filters that describe the org traces to search for | OrgTraceBulkFilterRequest |  | true |
### Template
```
{"emailAddress":"","filters":{"appVersionTags":[],"applicationID":"","applicationIds":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]}}
```
