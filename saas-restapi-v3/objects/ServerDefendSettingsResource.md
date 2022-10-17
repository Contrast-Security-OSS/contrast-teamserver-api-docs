## ServerDefendSettingsResource
---
### Description
Server Defend Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bot_protection | Bot Protection | boolean |  | false |
| defend | Defend | boolean |  | false |
| syslog_connection_type | Syslog connection type | syslogconnectiontype |  | false |
| syslog_enabled | Syslog enabled | boolean |  | false |
| syslog_facility_code | Syslog facility code | integer |  | false |
| syslog_ip_address | Syslog IP address | string |  | false |
| syslog_port_number | Syslog port number | integer |  | false |
| syslog_protocol | Protocol | syslogprotocol |  | false |
| syslog_severity_blocked | Syslog severity blocked | syslogseverity |  | false |
| syslog_severity_blocked_perimeter | Syslog severity blocked @ perimeter | syslogseverity |  | false |
| syslog_severity_exploited | Syslog severity exploited | syslogseverity |  | false |
| syslog_severity_probed | Syslog severity probed | syslogseverity |  | false |
| syslog_severity_probed_perimeter | Syslog severity probed @ perimeter | syslogseverity |  | false |
| syslog_severity_suspicious | Severity for suspicious attack events | syslogseverity |  | false |
### Template
```
{"bot_protection":true,"defend":true,"syslog_connection_type":"","syslog_enabled":true,"syslog_facility_code":0,"syslog_ip_address":"","syslog_port_number":0,"syslog_protocol":"","syslog_severity_blocked":"","syslog_severity_blocked_perimeter":"","syslog_severity_exploited":"","syslog_severity_probed":"","syslog_severity_probed_perimeter":"","syslog_severity_suspicious":""}
```
