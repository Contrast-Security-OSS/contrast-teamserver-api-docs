## VirtualPatchResponse
---
### Description
Virtual Patch Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| patch | Virtual Patch Resource | VirtualPatchResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"errors":[],"messages":[],"patch":{"application_mode":0,"applications":[],"languages":[],"criterias":[],"description":"","enabled":true,"enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"links":[],"name":"","technology":[],"triggered":0,"uuid":""},"success":true}
```
