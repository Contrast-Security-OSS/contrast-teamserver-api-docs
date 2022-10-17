## TraceBreakdownResponse
---
### Description
Vulnerability Breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| trace_breakdown | Trace Breakdown | TraceBreakdownResource |  | false |
### Template
```
{"messages":[],"success":true,"trace_breakdown":{"confirmed":0,"criticals":0,"fixed":0,"highs":0,"links":[],"lows":0,"meds":0,"notProblem":0,"notes":0,"remediated":0,"remediatedAutoVerified":0,"reported":0,"safes":0,"suspicious":0,"traces":0,"triaged":0}}
```
