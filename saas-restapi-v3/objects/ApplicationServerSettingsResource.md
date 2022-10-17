## ApplicationServerSettingsResource
---
### Description
Application Server Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Assessment enabled | boolean |  | false |
| defend | Protection enabled | boolean |  | false |
| has_instrumentation_conflict | An application has an instrumentation conflict with the server | boolean |  | false |
| name | name | string |  | false |
| server_id | Server id | long |  | false |
### Template
```
{"assess":true,"defend":true,"has_instrumentation_conflict":true,"links":[],"name":"","server_id":0}
```
