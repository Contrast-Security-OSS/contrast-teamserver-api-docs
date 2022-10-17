## TraceShortResponse
---
### Description
Trace Short Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| trace | Vulnerability&#x27;s base attributes | TraceShortResource |  | false |
### Template
```
{"links":[],"messages":[],"success":true,"trace":{"app_id":"","first_time_seen":0,"impact":"","license":"","likelihood":"","links":[],"ruleName":"","severity":"","status":"","subStatus":"","sub_status_keycode":"","title":"","uuid":"","visible":true}}
```
