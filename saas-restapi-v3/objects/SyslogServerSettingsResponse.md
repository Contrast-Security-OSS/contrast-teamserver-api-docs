## SyslogServerSettingsResponse
---
### Description
Syslog server Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| settings | Syslog server settings | ServerSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"settings":{"syslog_connection_type":"","syslog_enabled":true,"syslog_facility_code":0,"syslog_ip_address":"","syslog_port_number":0,"syslog_protocol":"","syslog_severity_blocked":"","syslog_severity_blocked_perimeter":"","syslog_severity_exploited":"","syslog_severity_probed":"","syslog_severity_probed_perimeter":"","syslog_severity_suspicious":""},"success":true}
```
