## RouteCoverageBySessionIDAndMetadataRequest
---
### Description
Route Coverage By Session ID And Metadata Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| metadata | Metadata label values. If &#x27;sessionID&#x27; is empty, this property must have at least one element. | list |  | false |
| sessionID | Session ID. If &#x27;metadata&#x27; property is empty, this property must have a value. | string |  | false |
### Template
```
{"metadata":[],"sessionID":""}
```
