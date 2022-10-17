## SecurityValidatorResponse
---
### Description
Input Validator Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| validator | Input Validator | ValidatorResource |  | false |
### Template
```
{"errors":[],"messages":[],"success":true,"validator":{"all_rules":true,"api":"","id":0,"enabled":true,"hash":"","language":"","links":[],"name":"","org":{"api_only":true,"apps_onboarded":0,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"time_format":"","timezone":"","user_access":true,"vulnerability_trends_graph_enabled":true},"pattern":"","rules":[],"type":"","validator_id":0}}
```
