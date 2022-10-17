## SecurityCheckRequest
---
### Description
Security Check Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agent_language | Agent Language | agentlanguage |  | false |
| application_id | Application ID | string |  | false |
| application_name | Application Name | string |  | false |
| job_start_time | Job Start Time | long |  | false |
| origin | Origin | string |  | false |
| security_check_filter | filter for vulnerabilities | securitycheckfilter |  | false |
### Template
```
{"agent_language":"","application_id":"","application_name":"","job_start_time":0,"origin":"","security_check_filter":{}}
```
