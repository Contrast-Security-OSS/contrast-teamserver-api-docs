## OrganizationApplicationSettingsResource
---
### Description
Organization Application Settings Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| auto_license | Automatically apply assess licenses to new applications | boolean |  | false |
| compliance_policies | Application default compliance policies | list |  | false |
| filter_app_most_recent_session | Boolean flag to filter app by most recent session | boolean |  | false |
| importance | Application default importance | applicationimportance |  | false |
| remediation_policies | Application default remediation policies | list |  | false |
### Template
```
{"auto_license":true,"compliance_policies":[],"filter_app_most_recent_session":true,"importance":"","links":[],"remediation_policies":[]}
```
