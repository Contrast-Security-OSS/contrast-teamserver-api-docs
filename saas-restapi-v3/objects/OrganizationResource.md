## OrganizationResource
---
### Description
Organization Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| account_id | Account ID | string |  | false |
| api_only | API Only Setting | boolean |  | false |
| apps_onboarded | Number of applications onboarded | long |  | false |
| auto_license_assessment | Auto license assessment | boolean |  | false |
| auto_license_protection | Auto license protection | boolean |  | false |
| beta_languages_enabled | Beta Languages Organization feature enabled | boolean |  | false |
| cloudnative_enabled | Cloud Native features enabled | boolean |  | false |
| creation_time | Organization creation date | date |  | false |
| cvss_scoring_type | Version of cvss to use for scoring | cvssscoringtype |  | false |
| date_format | Organization date format | string |  | false |
| freeTrail | Is this a Free Trial organization? | boolean |  | false |
| freeTrialState | Free Trial properties | freetrialstate |  | false |
| freemium | Is this organization freemium? | boolean |  | false |
| guest | Is user guest in this organization? | boolean |  | false |
| harmony_enabled | Harmony features enabled | boolean |  | false |
| is_superadmin | Is a Superadmon Organization | boolean |  | false |
| locale | Organization locale | string |  | false |
| name | Organization name | string |  | false |
| organization_uuid | Organization ID | string |  | false |
| ossLicense | Auto oss license enabled | boolean |  | false |
| properties | Organization properties | map |  | false |
| protect | Has user protect enabled in this organization? | boolean |  | false |
| protection_enabled | Protection enabled | boolean |  | false |
| sample_application_id | Sample application ID | string |  | false |
| sample_server_id | Sample server ID | long |  | false |
| sast_enabled | SAST features enabled | boolean |  | false |
| security_standard_report_enabled | Security standard report enabled | boolean |  | false |
| server_environments | List of Server Environments | set |  | false |
| time_format | Organization time format | string |  | false |
| timezone | Organization time zone | string |  | false |
| user_access | User Access Setting | boolean |  | false |
| vulnerability_trends_graph_enabled | Is vulnerability trends graph enabled | boolean |  | false |
### Template
```
{"api_only":true,"apps_onboarded":0,"auto_license_assessment":true,"auto_license_protection":true,"beta_languages_enabled":true,"cloudnative_enabled":true,"creation_time":{},"cvss_scoring_type":"","date_format":"","freeTrail":true,"freeTrialState":{},"freemium":true,"account_id":"","guest":true,"harmony_enabled":true,"is_superadmin":true,"links":[],"locale":"","name":"","organization_uuid":"","ossLicense":true,"properties":{},"protect":true,"protection_enabled":true,"sample_application_id":"","sample_server_id":0,"sast_enabled":true,"security_standard_report_enabled":true,"server_environments":[],"time_format":"","timezone":"","user_access":true,"vulnerability_trends_graph_enabled":true}
```
