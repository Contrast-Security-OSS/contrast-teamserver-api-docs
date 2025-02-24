## ServerSettingsResponse
---
### Description
Server Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| settings | Server settings | ServerSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"settings":{"assess":true,"bot_protection":true,"defend":true,"environment":"","licensed":true,"links":[],"log_level":"","log_path":"","name":"","sampling":true,"sampling_baseline":0,"sampling_frequency":0,"sampling_window":0,"server_cleanup_policies":[],"stacktrace_capture_mode":"","syslog_connection_type":"","syslog_enabled":true,"syslog_facility_code":0,"syslog_ip_address":"","syslog_port_number":0,"syslog_protocol":"","syslog_severity_blocked":"","syslog_severity_blocked_perimeter":"","syslog_severity_exploited":"","syslog_severity_probed":"","syslog_severity_probed_perimeter":"","syslog_severity_suspicious":""},"success":true}
```
