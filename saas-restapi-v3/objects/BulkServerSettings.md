## BulkServerSettings
---
### Description
Bulk Server Settings
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Assess related settings | AssessSettings |  | false |
| environment | The deployment environment | serverenvironment |  | false |
| logLevel | The logging level | serverloglevel |  | false |
| protect | Protect related settings | ProtectSettings |  | false |
### Template
```
{"assess":{"sampling":{"baseline":0,"frequency":0,"window":0},"stacktraceCaptureMode":""},"environment":"","logLevel":"","protect":{"botProtection":true,"syslog":{"connectionType":"","facilityCode":0,"ipAddress":"","port":0,"protocol":"","severityBlocked":"","severityBlockedPerimeter":"","severityExploited":"","severityProbed":"","severityProbedPerimeter":"","severitySuspicious":""}}}
```
