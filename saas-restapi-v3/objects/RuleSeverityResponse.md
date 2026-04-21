## RuleSeverityResponse
---
### Description
Rule Severity Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| severity | Rule Severity | ruleseverity |  | false |
| severity_label | Rule Severity Label | string |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| vulnerabilities_affected | Vulnerabilities affected | long |  | false |
| vulnerabilities_exceptions | Vulnerabilities with exceptions | long |  | false |
### Template
```
{"messages":[],"severity":"","severity_label":"","success":true,"vulnerabilities_affected":0,"vulnerabilities_exceptions":0}
```
