## NotificationUserSettingsResource
---
### Description
Notification User Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| activity_summary | Activity digest status | boolean |  | false |
| all_apps | Enabled for all applications | boolean |  | false |
| apps | List of apps configured | list |  | false |
| digest_compliance | Compliance policy violation digest status | boolean |  | false |
| digest_library | Library policy violation digest status | boolean |  | false |
| digest_remediation | Remediation policy violation digest status | boolean |  | false |
| triggers | List of Notification Types | list |  | false |
### Template
```
{"activity_summary":true,"all_apps":true,"apps":[],"digest_compliance":true,"digest_library":true,"digest_remediation":true,"links":[],"triggers":[]}
```
