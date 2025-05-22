## TracesResource
---
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| closed-time | Closed time | date |  | false |
| confidence | Confidence | string |  | false |
| events | Trace events | list |  | false |
| evidence | Evidence | string |  | false |
| first-time-seen | First time seen | date |  | false |
| impact | Impact | string |  | false |
| language | Language | string |  | false |
| last-time-seen | Last time seen | date |  | false |
| likelihood | Likelihood | string |  | false |
| reported-to-bug-tracker | Is reported to the bugtracker | boolean |  | false |
| reported-to-bug-tracker-time | Date reported to the bugtracker | date |  | false |
| request | Http request | HttpRequestResource |  | false |
| rule-name | Rule name | string |  | false |
| severity | Severity | string |  | false |
| status | Trace status | string |  | false |
| sub-status | Trace sub-status | string |  | false |
| sub-title | Subtitle | string |  | false |
| title | Title | string |  | false |
| total-traces-received | Total traces received | long |  | false |
| trace-id | Trace ID | long |  | false |
| uuid | Trace UUID | string |  | false |
### Template
```
{"closed-time":{},"confidence":"","events":[],"evidence":"","first-time-seen":{},"impact":"","language":"","last-time-seen":{},"likelihood":"","links":[],"reported-to-bug-tracker":true,"reported-to-bug-tracker-time":{},"request":{"headers":[],"links":[],"method":"","normalizedUri":"","parameters":[],"port":0,"protocol":"","query-string":"","uri":"","version":""},"rule-name":"","severity":"","status":"","sub-status":"","sub-title":"","title":"","total-traces-received":0,"trace-id":0,"uuid":""}
```
