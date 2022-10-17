## SyslogSettings
---
### Description
Syslog Settings
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| connectionType | Connection type | syslogconnectiontype |  | true |
| facilityCode | Facility code | integer |  | true |
| ipAddress | IP Address | string |  | true |
| port | Port | integer |  | true |
| protocol | Protocol | syslogprotocol |  | false |
| severityBlocked | Severity for blocked attack events | syslogseverity |  | false |
| severityBlockedPerimeter | Severity for blocked @ perimeter attack events | syslogseverity |  | false |
| severityExploited | Severity for exploited attack events | syslogseverity |  | false |
| severityProbed | Severity for probed attack events | syslogseverity |  | false |
| severityProbedPerimeter | Severity for probed @ perimeter attack events | syslogseverity |  | false |
| severitySuspicious | Severity for suspicious attack events | syslogseverity |  | false |
### Template
```
{"connectionType":"","facilityCode":0,"ipAddress":"","port":0,"protocol":"","severityBlocked":"","severityBlockedPerimeter":"","severityExploited":"","severityProbed":"","severityProbedPerimeter":"","severitySuspicious":""}
```
