## NotificationOrganizationSettingsResource
---
### Description
Notification Organization Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| activity_summary | Activity digest status | boolean |  | false |
| custom | Custom organization setting | boolean |  | false |
| digest_compliance | Compliance policy violation digest status | boolean |  | false |
| digest_library | Library policy violation digest status | boolean |  | false |
| digest_remediation | Remediation policy violation digest status | boolean |  | false |
| triggers | List of Notification Triggers | list |  | false |
### Template
```
{"activity_summary":true,"custom":true,"digest_compliance":true,"digest_library":true,"digest_remediation":true,"links":[],"triggers":[]}
```
