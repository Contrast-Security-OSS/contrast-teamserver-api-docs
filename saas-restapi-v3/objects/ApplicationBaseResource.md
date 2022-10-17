## ApplicationBaseResource
---
### Description
Application Base Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_id | Application id | string |  | false |
| child | Is application child | boolean |  | false |
| language | Application language | string |  | false |
| master | Is application master | boolean |  | false |
| name | Application name | string |  | false |
| parent_app_id | Application parent ID | string |  | false |
| primary | Is application primary | boolean |  | false |
| roles | List of allowed roles | collection |  | false |
| total_modules | Number of app modules | long |  | false |
### Template
```
{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0}
```
