## OrgTraceBulkTagRequest
---
### Description
Organization Trace Bulk Tag Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| addTags | List of tags to add | list |  | true |
| filters | Filters that describe the org traces to tag | OrgTraceBulkFilterRequest |  | true |
| removeTags | List of tags to remove | list |  | true |
### Template
```
{"addTags":[],"filters":{"agentSessionId":"","appVersionTags":[],"applicationID":"","applicationIds":[],"applicationImportances":[],"applicationMetadataFilters":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","languages":[],"licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"technologies":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]},"removeTags":[]}
```
