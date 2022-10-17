## AttackServerResource
---
### Description
Attack Server Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| enabled | Is server enabled? | boolean |  | false |
| environment | Server environment | serverenvironment |  | false |
| last_event_time | Last event time | long |  | false |
| name | Server name | string |  | false |
| server_id | Server ID | long |  | false |
| serverpath | Server path | string |  | false |
| total_events | Total number of events | long |  | false |
### Template
```
{"enabled":true,"environment":"","server_id":0,"last_event_time":0,"name":"","serverpath":"","total_events":0}
```
