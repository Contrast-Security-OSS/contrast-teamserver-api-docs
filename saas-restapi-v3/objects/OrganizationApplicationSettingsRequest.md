## OrganizationApplicationSettingsRequest
---
### Description
Organization Application Settings Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| absolute_policy_all_applications | Define if is enabled to all applications | boolean |  | false |
| absolute_policy_applications | Set of application identifiers to which absolute policy applies | set |  | false |
| absolute_policy_coverage_percentage | Integer percentage threshold for absolute policy coverage | integer |  | false |
| absolute_policy_enabled | Define if is enable absolute policy | boolean |  | false |
| absolute_policy_importances | Set of application importance levels for absolute policy | set |  | false |
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
{"absolute_policy_all_applications":true,"absolute_policy_applications":[],"absolute_policy_coverage_percentage":0,"absolute_policy_enabled":true,"absolute_policy_importances":[],"auto_license":true,"compliance_policies":[],"filter_app_most_recent_session":true,"importance":"","metadata":{"existing_apps_action":"","fields":[],"new_apps_action":""},"prevent_onboarding_failing_applications":true,"protect_environment_displayed_in_vulnerability_grid":"","remediation_policies":[],"route_expiration_days":0}
```
