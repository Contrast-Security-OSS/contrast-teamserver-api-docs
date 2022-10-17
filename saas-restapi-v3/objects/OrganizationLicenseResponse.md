## OrganizationLicenseResponse
---
### Description
Organization Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| organization | Organization Resource | OrganizationLicenseResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"organization":{"api_only":true,"app_library_status_enabled":true,"apps_onboarded":0,"assessment_license":true,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","disa_stig_enabled":true,"environments":[],"freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossFeature":true,"ossInventoryModeFeature":true,"ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"protection_license":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"telemetry_enabled":true,"time_format":"","timezone":"","user_access":true,"vulnerability_auto_verification_enabled":true,"vulnerability_duplicate_notification_enabled":true,"vulnerability_trends_graph_enabled":true},"success":true}
```
