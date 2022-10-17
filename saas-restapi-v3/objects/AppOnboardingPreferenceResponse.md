## AppOnboardingPreferenceResponse
---
### Description
Application Onboarding Preference Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_onboarding | If the user has finished the application onboarding wizard before | boolean |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"app_onboarding":true,"messages":[],"success":true}
```
