## OrganizationLicenseResource
---
### Description
Organization AutoLicense Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| account_id | Account ID | string |  | false |
| api_only | API Only Setting | boolean |  | false |
| app_library_status_enabled | Is application library status org feature enabled | boolean |  | false |
| apps_onboarded | Number of applications onboarded | long |  | false |
| assessment_license | Auto assessment license enabled | boolean |  | false |
| auto_license_assessment | Auto license assessment | boolean |  | false |
| auto_license_protection | Auto license protection | boolean |  | false |
| beta_languages_enabled | Beta Languages Organization feature enabled | boolean |  | false |
| cloudnative_enabled | Cloud Native features enabled | boolean |  | false |
| creation_time | Organization creation date | date |  | false |
| cvss_scoring_type | Version of cvss used for scoring | cvssscoringtype |  | false |
| date_format | Organization date format | string |  | false |
| disa_stig_enabled | DISA STIG feature enabled | boolean |  | false |
| environments | Server Environments | set |  | false |
| freeTrail | Is this a Free Trial organization? | boolean |  | false |
| freeTrialState | Free Trial properties | freetrialstate |  | false |
| freemium | Is this organization freemium? | boolean |  | false |
| guest | Is user guest in this organization? | boolean |  | false |
| harmony_enabled | HARMONY features enabled | boolean |  | false |
| is_superadmin | Is a Superadmon Organization | boolean |  | false |
| locale | Organization locale | string |  | false |
| name | Organization name | string |  | false |
| organization_uuid | Organization ID | string |  | false |
| ossFeature | OSS Feature enabled | boolean |  | false |
| ossInventoryModeFeature | OSS inventory mode feature enabled | boolean |  | false |
| ossLicense | oss license enabled | boolean |  | false |
| properties | Organization properties | map |  | false |
| protect | Has user protect enabled in this organization? | boolean |  | false |
| protection_enabled | Protection enabled | boolean |  | false |
| protection_license | Auto protection license enabled | boolean |  | false |
| rbacEnforceAssess | Is RBAC enforced assess? | boolean |  | false |
| sample_application_id | Sample application ID | string |  | false |
| sample_server_id | Sample server ID | long |  | false |
| sast_enabled | SAST features enabled | boolean |  | false |
| security_standard_report_enabled | Security standard report enabled | boolean |  | false |
| server_environments | List of Server Environments | set |  | false |
| telemetry_enabled | Telemetry enabled | boolean |  | false |
| time_format | Organization time format | string |  | false |
| timezone | Organization time zone | string |  | false |
| user_access | User Access Setting | boolean |  | false |
| vulnerability_auto_verification_enabled | Route-based vulnerability auto-verification enabled | boolean |  | false |
| vulnerability_duplicate_notification_enabled | Vulnerability duplicate notification feature enabled | boolean |  | false |
| vulnerability_trends_graph_enabled | Is vulnerability trends graph enabled | boolean |  | false |
### Template
```
{"api_only":true,"app_library_status_enabled":true,"apps_onboarded":0,"assessment_license":true,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","disa_stig_enabled":true,"environments":[],"freeTrail":true,"freeTrialState":{},"freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossFeature":true,"ossInventoryModeFeature":true,"ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"protection_license":true,"rbacEnforceAssess":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"telemetry_enabled":true,"time_format":"","timezone":"","user_access":true,"vulnerability_auto_verification_enabled":true,"vulnerability_duplicate_notification_enabled":true,"vulnerability_trends_graph_enabled":true}
```
