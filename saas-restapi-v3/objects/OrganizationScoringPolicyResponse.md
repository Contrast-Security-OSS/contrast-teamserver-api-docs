## OrganizationScoringPolicyResponse
---
### Description
Organization Scoring Policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| failLibrariesPolicy | Fail libraries policy enabled | boolean |  | false |
| libraryScoreType | Library scoring type | libraryscoringtype |  | false |
| messages | List of messages | list |  | false |
| overallScoreLanguages | Overall scoring languages | string |  | false |
| overallScoreType | Overall scoring type | overallscoringtype |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"failLibrariesPolicy":true,"libraryScoreType":"","messages":[],"overallScoreLanguages":"","overallScoreType":"","success":true}
```
