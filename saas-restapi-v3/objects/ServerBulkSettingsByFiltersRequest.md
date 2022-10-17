## ServerBulkSettingsByFiltersRequest
---
### Description
Server Bulk Settings By Filters Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| filters | Filters for specifying the servers to update | ngserverbulkfilterrequest |  | true |
| settings | The settings to be updated | BulkServerSettings |  | true |
### Template
```
{"filters":{},"settings":{"assess":{"sampling":{"baseline":0,"frequency":0,"window":0},"stacktraceCaptureMode":""},"environment":"","logLevel":"","protect":{"botProtection":true,"syslog":{"connectionType":"","facilityCode":0,"ipAddress":"","port":0,"protocol":"","severityBlocked":"","severityBlockedPerimeter":"","severityExploited":"","severityProbed":"","severityProbedPerimeter":"","severitySuspicious":""}}}}
```
