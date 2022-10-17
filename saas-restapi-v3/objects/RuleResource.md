## RuleResource
---
### Description
Rule Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| category | Category | string |  | false |
| confidence | Confidence | string |  | false |
| customized_confidence | If confidence is customized | boolean |  | false |
| customized_impact | If impact is customized | boolean |  | false |
| customized_likelihood | If likelihood is customized | boolean |  | false |
| cwe | CWE | string |  | false |
| description | Description | string |  | false |
| development_breakdown | Breakdown for development environments | AssessRuleBreakdownResource |  | false |
| enabled | Enabled | boolean |  | false |
| enabled_dev | If the rule is enabled in Development Server | boolean |  | false |
| enabled_prod | If the rule is enabled in Production Server | boolean |  | false |
| enabled_qa | If the rule is enabled in QA Server | boolean |  | false |
| free | Free | boolean |  | false |
| freemium_enabled | Is this rule enabled for freemium? | boolean |  | false |
| impact | Impact | string |  | false |
| languages | List of languages supported | list |  | false |
| likelihood | Likelihood | string |  | false |
| name | Rule name | string |  | false |
| owasp | OWASP | string |  | false |
| production_breakdown | Breakdown for production environments | AssessRuleBreakdownResource |  | false |
| qa_breakdown | Breakdown for QA environments | AssessRuleBreakdownResource |  | false |
| references | List of References | list |  | false |
| serviceLevel | Service level | servicelevel |  | false |
| severity | Severity | string |  | false |
| severityLabel | Translated Severity Value | string |  | false |
| title | Title | string |  | false |
### Template
```
{"category":"","confidence":"","customized_confidence":true,"customized_impact":true,"customized_likelihood":true,"cwe":"","description":"","development_breakdown":{"off_applications":[],"on_applications":[]},"enabled":true,"enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"free":true,"freemium_enabled":true,"impact":"","languages":[],"likelihood":"","links":[],"owasp":"","production_breakdown":{"off_applications":[],"on_applications":[]},"qa_breakdown":{"off_applications":[],"on_applications":[]},"references":[],"name":"","serviceLevel":"","severity":"","severityLabel":"","title":""}
```
