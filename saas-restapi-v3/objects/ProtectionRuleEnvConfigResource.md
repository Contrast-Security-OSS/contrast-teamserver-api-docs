## ProtectionRuleEnvConfigResource
---
### Description
Protection Rule Breakdown Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| can_block | Rule can be blocked | boolean |  | false |
| can_block_at_perimeter | Rule can block at perimeter | boolean |  | false |
| cves | CVEs | list |  | false |
| description | Description | string |  | false |
| development | Breakdown for development environments | ProtectionRuleBreakdownItemResource |  | false |
| is_monitor_at_perimeter | Rule is monitor at perimeter | boolean |  | false |
| languages | List of languages supported | list |  | false |
| name | Name | string |  | false |
| parent_rule_name | Parent rule name | string |  | false |
| parent_rule_uuid | Parent rule unique id | string |  | false |
| production | Breakdown for production environments | ProtectionRuleBreakdownItemResource |  | false |
| qa | Breakdown for qa environments | ProtectionRuleBreakdownItemResource |  | false |
| ruleId | Rule ID | long |  | false |
| uuid | Rule Uuid | string |  | false |
### Template
```
{"can_block":true,"can_block_at_perimeter":true,"cves":[],"description":"","development":{"blocking_applications":[],"blocking_perimeter_applications":[],"monitor_perimeter_applications":[],"monitoring_applications":[],"off_applications":[],"protect_mode":"","total_blocking_apps":0,"total_blocking_perimeter_apps":0,"total_monitor_perimeter_apps":0,"total_monitoring_apps":0,"total_off_apps":0},"is_monitor_at_perimeter":true,"languages":[],"links":[],"name":"","parent_rule_name":"","parent_rule_uuid":"","production":{"blocking_applications":[],"blocking_perimeter_applications":[],"monitor_perimeter_applications":[],"monitoring_applications":[],"off_applications":[],"protect_mode":"","total_blocking_apps":0,"total_blocking_perimeter_apps":0,"total_monitor_perimeter_apps":0,"total_monitoring_apps":0,"total_off_apps":0},"qa":{"blocking_applications":[],"blocking_perimeter_applications":[],"monitor_perimeter_applications":[],"monitoring_applications":[],"off_applications":[],"protect_mode":"","total_blocking_apps":0,"total_blocking_perimeter_apps":0,"total_monitor_perimeter_apps":0,"total_monitoring_apps":0,"total_off_apps":0},"ruleId":0,"uuid":""}
```
