## ServerSettingsResource
---
### Description
Server Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Assess | boolean |  | false |
| bot_protection | Bot Protection | boolean |  | false |
| defend | Defend | boolean |  | false |
| environment | Environment | serverenvironment |  | false |
| licensed | Server has a license | boolean |  | false |
| log_level | Log level | string |  | false |
| log_path | Log path | string |  | false |
| name | Server name | string |  | false |
| sampling | Sampling | boolean |  | false |
| sampling_baseline | Sampling baseline | integer |  | false |
| sampling_frequency | Sampling frequency | integer |  | false |
| sampling_profile | Server sampling profile | samplingprofile |  | false |
| sampling_window | Sampling window | integer |  | false |
| server_cleanup_policies | Cleanup policies configured for this server | list |  | false |
| stacktrace_capture_mode | Stacktrace capture mode | string |  | false |
| syslog_connection_type | Syslog connection type | syslogconnectiontype |  | false |
| syslog_enabled | Syslog enabled | boolean |  | false |
| syslog_facility_code | Syslog facility code | integer |  | false |
| syslog_ip_address | Syslog IP address | string |  | false |
| syslog_port_number | Syslog port number | integer |  | false |
| syslog_protocol | Syslog protocol | syslogprotocol |  | false |
| syslog_severity_blocked | Syslog severity blocked | syslogseverity |  | false |
| syslog_severity_blocked_perimeter | Syslog severity blocked perimeter | syslogseverity |  | false |
| syslog_severity_exploited | Syslog severity exploited | syslogseverity |  | false |
| syslog_severity_probed | Syslog severity probed | syslogseverity |  | false |
| syslog_severity_probed_perimeter | Syslog severity probed perimeter | syslogseverity |  | false |
| syslog_severity_suspicious | Syslog severity suspicious | syslogseverity |  | false |
### Template
```
{"assess":true,"bot_protection":true,"defend":true,"environment":"","licensed":true,"links":[],"log_level":"","log_path":"","name":"","sampling":true,"sampling_baseline":0,"sampling_frequency":0,"sampling_profile":"","sampling_window":0,"server_cleanup_policies":[],"stacktrace_capture_mode":"","syslog_connection_type":"","syslog_enabled":true,"syslog_facility_code":0,"syslog_ip_address":"","syslog_port_number":0,"syslog_protocol":"","syslog_severity_blocked":"","syslog_severity_blocked_perimeter":"","syslog_severity_exploited":"","syslog_severity_probed":"","syslog_severity_probed_perimeter":"","syslog_severity_suspicious":""}
```
