## ProtectionRuleResource
---
### Description
Protection Rule Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| can_block | Rule can be blocked | boolean |  | false |
| can_block_at_perimeter | Can Block at Perimeter | boolean |  | false |
| category | Category | string |  | false |
| cve_shield | CVE shield | boolean |  | false |
| cves | CVEs | list |  | false |
| description | Description | string |  | false |
| displayName | Display name | string |  | false |
| id | Rule ID | long |  | false |
| impact | Attack impact | attackimpact |  | false |
| is_monitor_at_perimeter | Can Monitor at Perimeter | boolean |  | false |
| name | Name | string |  | false |
| uuid | UUID | string |  | false |
### Template
```
{"can_block":true,"can_block_at_perimeter":true,"category":"","cve_shield":true,"cves":[],"description":"","displayName":"","impact":"","is_monitor_at_perimeter":true,"links":[],"name":"","id":0,"uuid":""}
```
