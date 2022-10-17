## TeamserverPropertiesResponse
---
### Description
Teamserver Properties Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
|  releaseNotes | Link to the release Notes | string |  | false |
| build | Build | string |  | false |
| date_format | Default Date Format | string |  | false |
| internal_version | Internal Version | string |  | false |
| maxFailedLoginAttempts | Maximum number of failed login attempts | int |  | false |
| messages | List of messages | list |  | false |
| mode | Deployment mode | deploymentmode |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| teamserver_url | Teamserver Url | string |  | false |
| time_format | Default Time Format | string |  | false |
| timezone | Default Timezone | string |  | false |
| version | Version | string |  | false |
### Template
```
{"build":"","date_format":"","time_format":"","timezone":"","internal_version":"","maxFailedLoginAttempts":0,"messages":[],"mode":""," releaseNotes":"","success":true,"teamserver_url":"","version":""}
```
