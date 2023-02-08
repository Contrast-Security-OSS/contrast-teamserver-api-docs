## TraceBulkBugtrackerRequest
---
### Description
Trace Bulk Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker | Configuration for sending to bugtracker | TraceBugtrackerRequest |  | true |
| filters | Filters that describe the traces to send to bugtracker | OrgTraceBulkFilterRequest |  | true |
### Template
```
{"bugtracker":{"agile_central_fields":[],"assignee":"","bugtracker_issue_type":"","confirmed":true,"epic_id":"","fields":[],"first":true,"github_fields":{"assignees":[],"labels":[],"milestone":0},"httpRequest":true,"intermediate":true,"last":true,"priority":"","recommendation":true,"references":true,"risk":true,"traces":[]},"filters":{"agentSessionId":"","appVersionTags":[],"applicationID":"","applicationIds":[],"applicationImportances":[],"applicationMetadataFilters":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","languages":[],"licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"technologies":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]}}
```
