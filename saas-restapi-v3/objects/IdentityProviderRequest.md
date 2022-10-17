## IdentityProviderRequest
---
### Description
Identity Provider Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| saml | SAML Settings | ngsamlrequestinformation |  | true |
| secret_node_saml | SAML Settings for Secret Node | ngsamlrequestinformation |  | true |
### Template
```
{"saml":{},"secret_node_saml":{}}
```
