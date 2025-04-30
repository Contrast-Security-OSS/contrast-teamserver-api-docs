## ProtectionRuleResource
---
### Description
Protection Rule Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| can_block | Rule can be blocked | boolean |  | false |
| can_block_at_perimeter | Rule can block at perimeter | boolean |  | false |
| cves | CVEs | list |  | false |
| description | Description | string |  | false |
| development | Rule Configuration for development servers | blockingmode |  | false |
| enabled_dev | Rule Enabled for development servers | boolean |  | false |
| enabled_prod | Rule Enabled for production servers | boolean |  | false |
| enabled_qa | Rule Enabled for qa servers | boolean |  | false |
| id | Rule Type ID | long |  | false |
| is_monitor_at_perimeter | Rule is monitor at perimeter | boolean |  | false |
| name | Rule Name | string |  | false |
| parent_rule_name | Parent rule name | string |  | false |
| parent_rule_uuid | Parent rule unique id | string |  | false |
| production | Rule Configuration for production servers | blockingmode |  | false |
| qa | Rule Configuration for qa servers | blockingmode |  | false |
| type | Rule Type | string |  | false |
| uuid | Rule UUID | string |  | false |
### Template
```
{"can_block":true,"can_block_at_perimeter":true,"cves":[],"description":"","development":"","enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"is_monitor_at_perimeter":true,"links":[],"name":"","parent_rule_name":"","parent_rule_uuid":"","production":"","qa":"","id":0,"type":"","uuid":""}
```
