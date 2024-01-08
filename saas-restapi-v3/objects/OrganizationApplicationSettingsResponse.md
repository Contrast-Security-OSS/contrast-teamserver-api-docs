## OrganizationApplicationSettingsResponse
---
### Description
Organization Application Settings Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| settings | Organizaion Application settings | OrganizationApplicationSettingsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"settings":{"auto_license":true,"compliance_policies":[],"filter_app_most_recent_session":true,"importance":"","links":[],"prevent_onboarding_failing_applications":true,"remediation_policies":[],"route_expiration_days":0},"success":true}
```
