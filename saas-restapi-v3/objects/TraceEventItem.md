## TraceEventItem
---
### Description
Trace Event Item
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| className | [Optional] Class name  | string |  | false |
| lastCustomFrame | Last custom frame | long |  | false |
| method | [Optional] Method | string |  | false |
| object | [Optional] Object | string |  | false |
| objectTracked | Is object tracked | boolean |  | false |
| parameters | List of parameters | list |  | false |
| returnTracked | Is return tracked | boolean |  | false |
| returnValue | [Optional] Return value | string |  | false |
| stacktraces | List of stack traces | list |  | false |
### Template
```
{"className":"","lastCustomFrame":0,"method":"","object":"","objectTracked":true,"parameters":[],"returnTracked":true,"returnValue":"","stacktraces":[]}
```
