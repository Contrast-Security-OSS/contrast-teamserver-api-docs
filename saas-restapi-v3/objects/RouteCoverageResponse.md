## RouteCoverageResponse
---
### Description
Application Route Coverage Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| count | Total number of routes coverage | integer |  | false |
| discoveredCount | Total number of discovered routes | integer |  | false |
| errors | List of errors | list |  | false |
| exercisedCount | Total number of exercised routes | integer |  | false |
| global_count | Global total number of routes coverage | integer |  | false |
| messages | List of messages | list |  | false |
| routes | List of routes coverage | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"count":0,"discoveredCount":0,"errors":[],"exercisedCount":0,"global_count":0,"messages":[],"routes":[],"success":true}
```
