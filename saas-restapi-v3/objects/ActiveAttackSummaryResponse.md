## ActiveAttackSummaryResponse
---
### Description
Active Attack Summary Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attacks | Total number of active attacks | long |  | false |
| messages | List of messages | list |  | false |
| severity | The most severe attack status for all active attacks | attackstatus |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"attacks":0,"messages":[],"severity":"","success":true}
```
