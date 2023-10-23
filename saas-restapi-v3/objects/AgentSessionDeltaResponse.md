## AgentSessionDeltaResponse
---
### Description
Response that returns the agent session information
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| total | total number of vulnerabilities for pagination purposes | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| details | List of message details | list |  | false |
| vulnerabilities | List of vulnerabilities | list |  | false |
| message | Response message | string |  | false |
### Template
```
{"details":[],"message":"","success":true,"total":0,"vulnerabilities":[]}
```
