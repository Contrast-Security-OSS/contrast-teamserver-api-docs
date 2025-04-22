## ServerBulkSettingsRequest
---
### Description
Server Bulk Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| serverIds | IDs of servers to be updated | list |  | true |
| settings | The settings to be updated | BulkServerSettings |  | true |
### Template
```
{"serverIds":[],"settings":{"assess":{"sampling":{"baseline":0,"frequency":0,"window":0},"samplingProfile":"","stacktraceCaptureMode":""},"environment":"","logLevel":"","protect":{"botProtection":true,"syslog":{"connectionType":"","facilityCode":0,"ipAddress":"","port":0,"protocol":"","severityBlocked":"","severityBlockedPerimeter":"","severityExploited":"","severityProbed":"","severityProbedPerimeter":"","severitySuspicious":""}}}}
```
