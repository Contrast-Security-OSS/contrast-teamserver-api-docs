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
| prevent_onboarding_failing_applications | Boolean flag to prevent onboarding failing applications by app metadata | boolean |  | false |
| protect_environment_displayed_in_vulnerability_grid | String value of the environment to display in the vulnerability grid for protect | string |  | false |
| remediation_policies | Application default remediation policies | list |  | false |
| route_expiration_days | Int value for the number of days to wait before expiring a route where a value &lt;&#x3D; zero means don&#x27;t expire the route | integer |  | false |
### Template
```
{"auto_license":true,"compliance_policies":[],"filter_app_most_recent_session":true,"importance":"","metadata":{"existing_apps_action":"","fields":[],"new_apps_action":""},"prevent_onboarding_failing_applications":true,"protect_environment_displayed_in_vulnerability_grid":"","remediation_policies":[],"route_expiration_days":0}
```
