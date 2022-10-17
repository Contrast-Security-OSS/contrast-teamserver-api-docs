## PublicInformationResponse
---
### Description
Public Information Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| http_authentication_enabled | Http Header Authentication Enabled | boolean |  | false |
| messages | List of messages | list |  | false |
| saml_enabled | SAML SSO feature flag and preference | boolean |  | false |
| secret_node_enabled | Secret Node Enabled | boolean |  | false |
| show_forgot_password | If forgot password is showing | boolean |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| tsv_breadcrumbs | If Breadcrumbs for Two-Step Verification should be displayed | boolean |  | false |
| tsv_flag | Two-Step Verification flag | boolean |  | false |
### Template
```
{"http_authentication_enabled":true,"messages":[],"saml_enabled":true,"secret_node_enabled":true,"show_forgot_password":true,"success":true,"tsv_breadcrumbs":true,"tsv_flag":true}
```
