## SarifAsyncExportResponse
---
### Description
Async export API Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| success | Indicates whether API response was successful or not | boolean |  | true |
| uuid | UUID of the async export request | string |  | false |
| messages | List of messages | list |  | true |
### Template
```
{"messages":[],"success":true,"uuid":""}
```
