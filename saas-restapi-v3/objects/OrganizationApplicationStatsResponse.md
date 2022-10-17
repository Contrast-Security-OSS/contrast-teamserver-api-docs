## OrganizationApplicationStatsResponse
---
### Description
Organization Application Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| current | Number of non-archived Applications | long |  | false |
| high | Number of non-archived high risk Applications | long |  | false |
| languages | Breakdown of applications by server language | list |  | false |
| messages | List of messages | list |  | false |
| previous | Number of non-archived Applications from the previous range | long |  | false |
| scores | Breakdown of applications by score | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| technologies | Breakdown of applications by technology | list |  | false |
### Template
```
{"current":0,"high":0,"languages":[],"messages":[],"previous":0,"scores":[],"success":true,"technologies":[]}
```
