## AttackMonitorTopAttackerResource
---
### Description
RASP Attack Monitor Top Attacker Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attack_status | Attack status | attackstatus |  | false |
| attack_types | Attack types | set |  | false |
| attack_uuids | Attack UUIDs | list |  | false |
| attacker | Attacker | string |  | false |
| blocked_attacks | Number of Blocked Attacks | long |  | false |
| exploited_attacks | Number of Exploited Attacks | long |  | false |
| probed_attacks | Number of Probed Attacks | long |  | false |
| source_ips | IP Addresses related to attacker | set |  | false |
| source_name | Known source name | string |  | false |
| suspicious_attacks | Number of Suspicious Attacks | long |  | false |
| total_attacks | Number of Total Attacks | long |  | false |
| unknown | Known source name | boolean |  | false |
### Template
```
{"attack_status":"","attack_types":[],"attack_uuids":[],"attacker":"","attackersItems":[],"blocked_attacks":0,"exploited_attacks":0,"probed_attacks":0,"source_ips":[],"source_name":"","suspicious_attacks":0,"total_attacks":0,"unknown":true}
```
