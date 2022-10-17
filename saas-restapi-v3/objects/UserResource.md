## UserResource
---
### Description
User Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| api_only | Is api only | boolean |  | false |
| api_only_org | is api only org | boolean |  | false |
| beta_languages_enabled | Beta Languages Organization feature enabled | boolean |  | false |
| current_user | is user current | boolean |  | false |
| email | Email | string |  | false |
| enabled | Is enabled | boolean |  | false |
| enabled_org | is enabled | boolean |  | false |
| external | Is User External | boolean |  | false |
| first_name | First name | string |  | false |
| groups | Access groups | list |  | false |
| id | the user&#x27;s id | string |  | false |
| invalid_roles | Invalid Roles because of a restriction in an Access Group | list |  | false |
| ip_address | Last IP address from user | string |  | false |
| keys | Keys | UserServiceKeyResource |  | false |
| last_name | Last name | string |  | false |
| login | Login | UserLoginResource |  | false |
| online | Online | boolean |  | false |
| org_management | is organization management | boolean |  | false |
| password_reset | Is password reset needed | boolean |  | false |
| preferences | Preferences | UserPreferencesResource |  | false |
| rasp_enabled | RASP enabled | boolean |  | false |
| role | Organizational role | RoleResource |  | false |
| serverless_enabled | Serverless User feature enabled | boolean |  | false |
| signup | Signup | UserSignUpResource |  | false |
| status | Status | integer |  | false |
| status_description | Status description | string |  | false |
| superadmin_role | SuperAdmin Role | superadminrole |  | false |
| tsv_enabled | Two-Step Verification enabled | boolean |  | false |
| user_uid | User uid | string |  | false |
### Template
```
{"api_only":true,"api_only_org":true,"beta_languages_enabled":true,"current_user":true,"email":"","enabled":true,"enabled_org":true,"external":true,"first_name":"","groups":[],"invalid_roles":[],"ip_address":"","keys":{"links":[],"service_key":""},"last_name":"","links":[],"login":{"failed_attempts":0,"last_host_address":"","last_login_time":{},"links":[]},"online":true,"org_management":true,"password_reset":true,"preferences":{"date_format":"","language":"","links":[],"time_format":"","time_zone":""},"rasp_enabled":true,"role":{"group_id":0,"links":[],"name":""},"serverless_enabled":true,"signup":{"accept_terms":true,"links":[],"signup_date":{},"signup_token":""},"status":0,"status_description":"","superadmin_role":"","tsv_enabled":true,"user_uid":"","id":""}
```
