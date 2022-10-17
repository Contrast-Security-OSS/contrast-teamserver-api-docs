## AccessGroupOrganizationRoleResource
---
### Description
EAC Group Organization Role Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| noAccess | If No access is enabled | boolean |  | false |
| organization | Organization Resource | OrganizationBaseResource |  | false |
| role | Role | string |  | false |
### Template
```
{"links":[],"noAccess":true,"organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"role":""}
```
