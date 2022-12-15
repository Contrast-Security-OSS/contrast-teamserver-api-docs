## RuleCustomizationResponse
---
### Description
Rule Customization Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| category | Category | string |  | false |
| confidence_level | Confidence level | string |  | false |
| confidence_level_custom | Confidence level custom | string |  | false |
| cwe | Link to the CWE page | string |  | false |
| description | Description | string |  | false |
| enabled | Enabled | boolean |  | false |
| enabled_custom | Enabled custom | boolean |  | false |
| impact | Impact | string |  | false |
| impact_custom | Impact custom | string |  | false |
| likelihood | Likelihood | string |  | false |
| likelihood_custom | Likelihood custom | string |  | false |
| messages | List of messages | list |  | false |
| name | Rule Name | string |  | false |
| owasp | Link to the OWASP page | string |  | false |
| recommendation | Recommendation | string |  | false |
| references | List of references | list |  | false |
| risk | Risk | string |  | false |
| severity | Rule severity | ruleseverity |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| title | Rule Title | string |  | false |
### Template
```
{"category":"","confidence_level":"","confidence_level_custom":"","cwe":"","description":"","enabled":true,"enabled_custom":true,"impact":"","impact_custom":"","likelihood":"","likelihood_custom":"","messages":[],"name":"","owasp":"","recommendation":"","references":[],"risk":"","severity":"","success":true,"title":""}
```
