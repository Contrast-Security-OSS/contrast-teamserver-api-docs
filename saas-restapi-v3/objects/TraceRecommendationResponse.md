## TraceRecommendationResponse
---
### Description
Trace Recommendation Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| custom_recommendation | Custom Recommendation | isnippet |  | false |
| custom_rule_references | Custom Rule references | isnippet |  | false |
| cwe | CWE | string |  | false |
| messages | List of messages | list |  | false |
| owasp | OWASP | string |  | false |
| recommendation | Recommendation | isnippet |  | false |
| rule_references | Rule references | isnippet |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"custom_recommendation":{},"custom_rule_references":{},"cwe":"","messages":[],"owasp":"","recommendation":{},"rule_references":{},"success":true}
```
