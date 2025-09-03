## RouteCoverageMetricsResource
---
### Description
Route Coverage Metrics Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| combinedDiscovered | Total discovered routes including all entry point types | integer |  | false |
| combinedExercised | Total exercised routes including all entry point types | integer |  | false |
| discovered | Total discovered routes | int |  | false |
| discoveredByUrl | Indicates whether routes are discovered by url activity | boolean |  | false |
| entryPointTypeCounts | Counts of entry point types for the application | list |  | false |
| exercised | Total exercised routes | int |  | false |
### Template
```
{"combinedDiscovered":0,"combinedExercised":0,"discovered":0,"discoveredByUrl":true,"entryPointTypeCounts":[],"exercised":0,"links":[]}
```
