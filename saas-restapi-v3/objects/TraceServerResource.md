## TraceServerResource
---
### Description
Trace Server Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agent_version | Agent Version | string |  | false |
| enabled | Is server enabled? | boolean |  | false |
| first_time_seen | Time first seen | long |  | false |
| last_time_seen | Time last seen | long |  | false |
| name | Name | string |  | false |
| server_id | Server ID | long |  | false |
| total_traces_received | Total received traces | long |  | false |
### Template
```
{"agent_version":"","enabled":true,"first_time_seen":0,"last_time_seen":0,"links":[],"name":"","server_id":0,"total_traces_received":0}
```
