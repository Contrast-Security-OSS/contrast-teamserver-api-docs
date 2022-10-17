## UserSettingsResponse
---
### Description
User Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| adminRole | Admin Role | string |  | false |
| blockSuperAdmin | Is superadmin access blocked | boolean |  | false |
| isImpersonating | Is impersonating | boolean |  | false |
| isToggleEnabled | Is toggle enabled | boolean |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"adminRole":"","blockSuperAdmin":true,"isImpersonating":true,"isToggleEnabled":true,"messages":[],"success":true}
```
