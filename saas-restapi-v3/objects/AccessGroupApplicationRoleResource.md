## AccessGroupApplicationRoleResource
---
### Description
EAC Group Application Role Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application Resource | ApplicationIdentityResource |  | false |
| groups | groups | list |  | false |
| noAccess | If No Access is enabled | boolean |  | false |
| role | Role | string |  | true |
### Template
```
{"application":{"context_path":"","app_id":"","language":"","name":"","child":true,"first_seen":0,"importance":0,"importance_description":"","last_seen":0,"license_level":"","links":[],"master":true,"metadataEntities":[],"organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"parent_app_id":"","primary":true,"roles":[],"servers":[],"status":"","total_modules":0},"groups":[],"links":[],"noAccess":true,"role":""}
```
