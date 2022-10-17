## ApplicationServerResource
---
### Description
Application Resource for Server
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_id | Application ID | string |  | false |
| app_instrumentation_state | App instrumentation state | boolean |  | false |
| archived | Is application archived | boolean |  | false |
| has_instrumentation_conflict | Application has an instrumentation conflict in this server | boolean |  | false |
| importance | Application Importance | integer |  | false |
| importance_description | Application Importance Description | applicationimportance |  | false |
| language | Application language | string |  | false |
| license_level | The application license level | servicelevel |  | false |
| master | Is application master | boolean |  | false |
| metadataEntities | List of metadata entities | list |  | false |
| name | Application name | string |  | false |
| parentApplicationId | Parent Application ID | string |  | false |
| path | Application path | string |  | false |
| primary | Is application primary | boolean |  | false |
| total_modules | Number of app modules | long |  | false |
### Template
```
{"app_id":"","app_instrumentation_state":true,"archived":true,"has_instrumentation_conflict":true,"importance":0,"importance_description":"","language":"","license_level":"","links":[],"master":true,"metadataEntities":[],"name":"","parentApplicationId":"","path":"","primary":true,"total_modules":0}
```
