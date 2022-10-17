## OrganizationSettingsResponse
---
### Description
Organization Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| settings | Organization settings | OrganizationSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"settings":{"diagnostics_collection_enabled":true,"links":[]},"success":true}
```
