## TimeoutsResponse
---
### Description
Timeouts Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| absolute_timeout | Absolute timeout | int |  | false |
| idle_timeout | Idle timeout | int |  | false |
| messages | List of messages | list |  | false |
| min_absolute_timeout | Minimum absolute timeout | int |  | false |
| min_idle_timeout | Minimum idle timeout | int |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"absolute_timeout":0,"idle_timeout":0,"min_absolute_timeout":0,"min_idle_timeout":0,"messages":[],"success":true}
```
