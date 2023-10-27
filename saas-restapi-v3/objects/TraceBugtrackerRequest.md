## TraceBugtrackerRequest
---
### Description
Trace Bugtracker Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| confirmed | Confirmed | boolean |  | true |
| first | First | boolean |  | true |
| httpRequest | HTTP request | boolean |  | true |
| intermediate | Intermediate | boolean |  | true |
| last | Last | boolean |  | true |
| recommendation | Recommendation | boolean |  | true |
| references | References | boolean |  | true |
| risk | Risk | boolean |  | true |
| traces | Vulnerability/Instance UUIDs | list |  | true |
### Template
```
{"agile_central_fields":[],"assignee":"","bugtracker_issue_type":"","confirmed":true,"epic_id":"","fields":[],"first":true,"github_fields":{"assignees":[],"labels":[],"milestone":0},"httpRequest":true,"intermediate":true,"last":true,"priority":"","recommendation":true,"references":true,"risk":true,"traces":[]}
```
