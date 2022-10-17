## GetTraceEvent
---
### Description
Get Trace Event
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| codeView | Raw code recreation | itraceeventgenericview |  | false |
| collapsedEvents | List of collapsed events | list |  | false |
| dataView | Data snapshot | itraceeventgenericview |  | false |
| description | Event description | string |  | false |
| dupes | # of duplicated events collapsed | int |  | false |
| extraDetails | Event extra details | string |  | false |
| id | Id | string |  | false |
| important | Is important | boolean |  | false |
| probableStartLocationView | Probable start location | itraceeventgenericview |  | false |
| type | Type | string |  | false |
### Template
```
{"codeView":{},"collapsedEvents":[],"dataView":{},"description":"","dupes":0,"extraDetails":"","id":"","important":true,"probableStartLocationView":{},"type":""}
```
