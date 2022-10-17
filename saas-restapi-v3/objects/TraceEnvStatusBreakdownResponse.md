## TraceEnvStatusBreakdownResponse
---
### Description
Vulnerability Environment Status Breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_vulnerabilities | Number of vulnerabilities | int |  | false |
| traces_breakdown | Vulnerabilities Breakdown | list |  | false |
### Template
```
{"messages":[],"success":true,"total_vulnerabilities":0,"traces_breakdown":[]}
```
