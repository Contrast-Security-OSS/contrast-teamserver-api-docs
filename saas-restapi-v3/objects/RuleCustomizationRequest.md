## RuleCustomizationRequest
---
### Description
Rule Customization Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| confidence_level | Confidence level | string |  | false |
| impact | Impact | string |  | false |
| likelihood | Likelihood | string |  | false |
| override | Override severity in all vulnerabilities | boolean |  | false |
| recommendation | Recommendation | string |  | false |
| references | List of References | list |  | false |
| risk | Risk | string |  | false |
### Template
```
{"confidence_level":"","impact":"","likelihood":"","override":true,"recommendation":"","references":[],"risk":""}
```
