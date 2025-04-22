## AssessSettings
---
### Description
Assess Settings
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| sampling | Sampling related settings | SamplingSettings |  | false |
| samplingProfile | Server sampling profile | samplingprofile |  | false |
| stacktraceCaptureMode | The logging level | serverstacktracemode |  | false |
### Template
```
{"sampling":{"baseline":0,"frequency":0,"window":0},"samplingProfile":"","stacktraceCaptureMode":""}
```
