## ProtectSettings
---
### Description
Protect Settings
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| botProtection | Bot Protection | boolean |  | false |
| syslog | Syslog related settings | SyslogSettings |  | false |
### Template
```
{"botProtection":true,"syslog":{"connectionType":"","facilityCode":0,"ipAddress":"","port":0,"protocol":"","severityBlocked":"","severityBlockedPerimeter":"","severityExploited":"","severityProbed":"","severityProbedPerimeter":"","severitySuspicious":""}}
```
