## SamlIdentityProviderConfigResponse
---
### Description
SAML Identity Provider Config Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| config | SAML Identity Provider Config | SamlIdentityProviderConfigResource |  | false |
| messages | List of messages | list |  | false |
| secret_config | Secret Node SAML Identity Provider Config | SamlIdentityProviderConfigResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"config":{"access_group":{"access_level":"","group_id":0,"links":[],"name":"","organizations":[],"readonly":true},"auto_add_to_group_enabled":true,"auto_remove_from_group_enabled":true,"default_rbac_user_access_group_id":"","domains":[],"identity_provider_name":"","links":[],"metadata_url":"","metadata_xml":"","organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"provider_key":"","provisioning_enabled":true,"role":{"group_id":0,"links":[],"name":""},"timeout":0},"messages":[],"secret_config":{"access_group":{"access_level":"","group_id":0,"links":[],"name":"","organizations":[],"readonly":true},"auto_add_to_group_enabled":true,"auto_remove_from_group_enabled":true,"default_rbac_user_access_group_id":"","domains":[],"identity_provider_name":"","links":[],"metadata_url":"","metadata_xml":"","organization":{"api_only":true,"date_format":"","impersonation_enabled":true,"links":[],"name":"","protection_enabled":true,"time_format":"","timezone":"","user_access":true,"organization_uuid":""},"provider_key":"","provisioning_enabled":true,"role":{"group_id":0,"links":[],"name":""},"timeout":0},"success":true}
```
