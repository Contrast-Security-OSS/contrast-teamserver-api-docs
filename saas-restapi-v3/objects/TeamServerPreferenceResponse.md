## TeamServerPreferenceResponse
---
### Description
Teamserver Preference Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| preference | Teamserver preferences | TeamServerPreferenceResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"preference":{"links":[],"name":"","value":""},"success":true}
```
