## TraceEventDetailsResponse
---
### Description
Trace Event Details Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| event | Event | TraceEventItem |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"event":{"className":"","lastCustomFrame":0,"method":"","object":"","objectTracked":true,"parameters":[],"returnTracked":true,"returnValue":"","stacktraces":[]},"messages":[],"success":true}
```
