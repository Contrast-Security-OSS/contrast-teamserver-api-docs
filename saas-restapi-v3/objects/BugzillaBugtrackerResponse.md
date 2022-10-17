## BugzillaBugtrackerResponse
---
### Description
Bugzilla Bugtracker Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker | Bugzilla configuration | BugzillaBugtrackerApplicationResource |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"bugtracker":{"all_applications":true,"app_criterion":true,"application_criterion":"","applications":[],"bugtracker_id":0,"keycode":"","type":"","component":"","connection_unavailable":true,"contrast_product":"","full_integration":true,"has_two_way_integration":true,"host":"","importance":[],"links":[],"name":"","priority":"","product":"","serverless_account_ids":[],"serverless_categories":[],"username":"","version":""},"errors":[],"messages":[],"success":true}
```
