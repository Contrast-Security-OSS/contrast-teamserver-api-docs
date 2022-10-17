## NotificationOrganizationSettingsResponse
---
### Description
Notification Organization Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| mail_enabled | Mail server enabled | boolean |  | false |
| messages | List of messages | list |  | false |
| notifications | Notification Organization Settings | NotificationOrganizationSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"mail_enabled":true,"messages":[],"notifications":{"activity_summary":true,"custom":true,"digest_compliance":true,"digest_library":true,"digest_remediation":true,"links":[],"triggers":[]},"success":true}
```
