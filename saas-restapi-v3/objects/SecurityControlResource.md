## SecurityControlResource
---
### Description
Security Control Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_rules | Apply Security Control to All Rules | boolean |  | false |
| api | API | string |  | false |
| enabled | If Security Control is enabled | boolean |  | false |
| hash | Hash | string |  | false |
| id | Security Control ID | long |  | false |
| language | Language | string |  | false |
| name | Name | string |  | false |
| org | Organization Resource | OrganizationResource |  | false |
| pattern | Pattern | string |  | false |
| rules | Rules to Apply the Security Control | list |  | false |
| type | Type of Security Control | securitycontroltype |  | false |
### Template
```
{"all_rules":true,"api":"","id":0,"enabled":true,"hash":"","language":"","links":[],"name":"","org":{"api_only":true,"apps_onboarded":0,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","freeTrail":true,"freeTrialState":{},"freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"rbacEnforceAssess":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"time_format":"","timezone":"","user_access":true,"vulnerability_trends_graph_enabled":true},"pattern":"","rules":[],"type":""}
```
