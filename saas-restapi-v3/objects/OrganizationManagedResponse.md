## OrganizationManagedResponse
---
### Description
Organization Managed Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| managed | If user accounts are managed by Contrast | boolean |  | false |
| messages | List of messages | list |  | false |
| organization | Organization Resource | OrganizationResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"managed":true,"messages":[],"organization":{"api_only":true,"apps_onboarded":0,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"time_format":"","timezone":"","user_access":true,"vulnerability_trends_graph_enabled":true},"success":true}
```
