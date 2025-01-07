## OrganizationServerSettingsResource
---
### Description
Organization Server Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Assess | boolean |  | false |
| auto_license_protection | Automatically apply protect licenses to new servers | boolean |  | false |
| bot_protection | Bot Protection | boolean |  | false |
| default_environment | Organization&#x27;s Default Server Environment | serverenvironment |  | false |
| defend | Defend | boolean |  | false |
| environment | Environment | serverenvironment |  | false |
| log_level | Log level | string |  | false |
| retain_library_data | If we should retain library data | boolean |  | false |
| sampling | Sampling | boolean |  | false |
| sampling_baseline | Sampling baseline | integer |  | false |
| sampling_frequency | Sampling frequency | integer |  | false |
| sampling_window | Sampling window | integer |  | false |
| server_cleanup_enhanced | Enable server cleanup enhanced feature | boolean |  | false |
| server_cleanup_policy | Cleanup policy configured for this server | ServerCleanupPolicyResource |  | false |
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
| telemetry_enabled | If Telemetry is enabled | boolean |  | false |
### Template
```
{"assess":true,"auto_license_protection":true,"bot_protection":true,"default_environment":"","defend":true,"environment":"","links":[],"log_level":"","retain_library_data":true,"sampling":true,"sampling_baseline":0,"sampling_frequency":0,"sampling_window":0,"server_cleanup_enhanced":true,"server_cleanup_policy":{"environment":"","links":[],"timeframe":0,"unit":""},"stacktrace_capture_mode":"","syslog_connection_type":"","syslog_enabled":true,"syslog_facility_code":0,"syslog_ip_address":"","syslog_port_number":0,"syslog_protocol":"","syslog_severity_blocked":"","syslog_severity_blocked_perimeter":"","syslog_severity_exploited":"","syslog_severity_probed":"","syslog_severity_probed_perimeter":"","syslog_severity_suspicious":"","telemetry_enabled":true}
```
