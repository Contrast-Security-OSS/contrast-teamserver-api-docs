## NewUserResponse
---
### Description
New User Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| user | User | UserResource |  | false |
### Template
```
{"errors":[],"messages":[],"success":true,"user":{"api_only":true,"api_only_org":true,"beta_languages_enabled":true,"current_user":true,"email":"","enabled":true,"enabled_org":true,"external":true,"first_name":"","groups":[],"invalid_roles":[],"ip_address":"","keys":{"links":[],"service_key":""},"last_name":"","links":[],"login":{"failed_attempts":0,"last_host_address":"","last_login_time":{},"links":[]},"online":true,"org_management":true,"password_reset":true,"preferences":{"date_format":"","language":"","links":[],"time_format":"","time_zone":""},"rasp_enabled":true,"role":{"group_id":0,"links":[],"name":""},"serverless_enabled":true,"signup":{"accept_terms":true,"links":[],"signup_date":{},"signup_token":""},"status":0,"status_description":"","superadmin_role":"","tsv_enabled":true,"user_uid":"","id":""}}
```
