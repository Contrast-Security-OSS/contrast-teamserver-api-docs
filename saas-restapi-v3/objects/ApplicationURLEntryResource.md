## ApplicationURLEntryResource
---
### Description
Application URL Entry Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| impact | Impact of related Vulnerability (if one exists) | string |  | false |
| last_time_seen | Last time seen | long |  | false |
| likelihood | Likelihood of related Vulnerability (if one exists) | string |  | false |
| severity | Severity of related Vulnerability (if one exists) | ruleseverity |  | false |
| url | Url | string |  | false |
### Template
```
{"impact":"","last_time_seen":0,"likelihood":"","links":[],"severity":"","url":""}
```
