## TraceHttpRequestDetailsResponse
---
### Description
Trace HTTP request Details Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| http_request | HTTP request | TraceHttpRequestResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"http_request":{"body":"","headers":[],"links":[],"method":"","parameters":[],"port":0,"protocol":"","queryString":"","uri":"","url":"","version":""},"messages":[],"success":true}
```
