## OrganizationApplicationSettingsRequest
---
### Description
Organization Application Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| auto_license | Automatically apply assess licenses to new applications | boolean |  | false |
| compliance_policies | Application default compliance policies | list |  | false |
| filter_app_most_recent_session | Boolean flag to filter app by most recent session | boolean |  | false |
| importance | Application default importance | applicationimportance |  | true |
| metadata | Configuration of the agent metadata | MetadataConfigurationRequest |  | false |
| remediation_policies | Application default remediation policies | list |  | false |
### Template
```
{"auto_license":true,"compliance_policies":[],"filter_app_most_recent_session":true,"importance":"","metadata":{"existing_apps_action":"","fields":[],"new_apps_action":""},"remediation_policies":[]}
```
