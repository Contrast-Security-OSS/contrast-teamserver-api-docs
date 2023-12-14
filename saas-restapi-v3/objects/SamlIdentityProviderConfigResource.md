## SamlIdentityProviderConfigResource
---
### Description
SAML Identity Provider Config
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| access_group | Access Group | AccessGroupBaseResource |  | false |
| auto_add_to_group_enabled | Auto Add To Group Enabled | boolean |  | false |
| auto_remove_from_group_enabled | Auto Remove From Group Enabled | boolean |  | false |
| default_rbac_user_access_group_id | Default RBAC User Access Group Id | string |  | false |
| domains | Accepted Domains | list |  | false |
| identity_provider_name | Name of the IdP being configured | string |  | true |
| metadata_url | IdP Metadata URL | string |  | false |
| metadata_xml | Metadata XML | string |  | false |
| organization | Default Organization | OrganizationBaseResource |  | false |
| provider_key | Provider key | string |  | false |
| provisioning_enabled | User Provisioning Enabled | boolean |  | false |
| role | Organization Role | RoleResource |  | false |
| timeout | Max time to wait for response from IdP before timeout | integer |  | false |
### Template
```
{"access_group":{"access_level":"","group_id":0,"links":[],"name":"","organizations":[],"readonly":true},"auto_add_to_group_enabled":true,"auto_remove_from_group_enabled":true,"default_rbac_user_access_group_id":"","domains":[],"identity_provider_name":"","links":[],"metadata_url":"","metadata_xml":"","organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"provider_key":"","provisioning_enabled":true,"role":{"group_id":0,"links":[],"name":""},"timeout":0}
```
