## ProtectionRuleBreakdownItemResource
---
### Description
Protection Rule Breakdown Item Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| blocking_applications | List of applications in BLOCKING mode | list |  | false |
| blocking_perimeter_applications | List of applications in BLOCKING_PERIMETER mode | list |  | false |
| monitor_perimeter_applications | List of applications in MONITOR_PERIMETER mode | list |  | false |
| monitoring_applications | List of applications in MONITORING mode | list |  | false |
| off_applications | List of applications in OFF mode | list |  | false |
| protect_mode | Type of blocking mode applied | blockingmode |  | false |
| total_blocking_apps | Number of applications in BLOCKING mode | integer |  | false |
| total_blocking_perimeter_apps | Number of applications in BLOCKING_PERIMETER mode | integer |  | false |
| total_monitor_perimeter_apps | Number of applications in MONITOR_PERIMETER mode | integer |  | false |
| total_monitoring_apps | Number of applications in MONITORING mode | integer |  | false |
| total_off_apps | Number of applications in OFF mode | integer |  | false |
### Template
```
{"blocking_applications":[],"blocking_perimeter_applications":[],"monitor_perimeter_applications":[],"monitoring_applications":[],"off_applications":[],"protect_mode":"","total_blocking_apps":0,"total_blocking_perimeter_apps":0,"total_monitor_perimeter_apps":0,"total_monitoring_apps":0,"total_off_apps":0}
```
