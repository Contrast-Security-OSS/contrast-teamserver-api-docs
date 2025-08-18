## RouteCoverageResponse
---
### Description
Application Route Coverage Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| count | Total number of routes coverage | integer |  | false |
| discoveredCount | Total number of discovered routes | integer |  | false |
| entrypoint_type_counts | Counts of entrypoint types for the routes coverage | list |  | false |
| errors | List of errors | list |  | false |
| exercisedCount | Total number of exercised routes | integer |  | false |
| exercised_count_except_session_metadata_filter | Total number of exercised routes coverage except session metadata filter | integer |  | false |
| global_count | Global total number of routes coverage | integer |  | false |
| messages | List of messages | list |  | false |
| routes | List of routes coverage | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_count_except_session_metadata_filter | Total number of routes coverage except session metadata filter | integer |  | false |
### Template
```
{"count":0,"discoveredCount":0,"entrypoint_type_counts":[],"errors":[],"exercisedCount":0,"global_count":0,"messages":[],"routes":[],"success":true,"total_count_except_session_metadata_filter":0,"exercised_count_except_session_metadata_filter":0}
```
