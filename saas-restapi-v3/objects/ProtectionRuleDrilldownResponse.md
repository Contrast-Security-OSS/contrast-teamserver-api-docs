## ProtectionRuleDrilldownResponse
---
### Description
Protection Rule Drilldown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applications | List of Applications | list |  | false |
| can_block | Rule can be blocked | boolean |  | false |
| can_block_at_perimeter | Rule can be blocked at perimeter | boolean |  | false |
| description | Rule Description | string |  | false |
| is_monitor_at_perimeter | Rule Is Monitor at Perimeter | boolean |  | false |
| messages | List of messages | list |  | false |
| name | Rule name | string |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"applications":[],"can_block":true,"can_block_at_perimeter":true,"description":"","is_monitor_at_perimeter":true,"messages":[],"name":"","success":true}
```
