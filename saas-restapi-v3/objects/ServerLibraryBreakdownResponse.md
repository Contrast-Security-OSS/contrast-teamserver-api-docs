## ServerLibraryBreakdownResponse
---
### Description
Server Library Breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total | Total of libraries in the server | long |  | false |
| vulnerable | Total of Vulnerable libraries in the server | long |  | false |
### Template
```
{"messages":[],"success":true,"total":0,"vulnerable":0}
```
