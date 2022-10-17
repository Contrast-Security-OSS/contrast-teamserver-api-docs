## TimeSeries
---
### Description
A single time series
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| values | Set of time series values | list |  | true |
| name | Human-readable identifier for the series | string |  | true |
| id | Unique identifier for the series | string |  | true |
| fields | Set of fields that map to each individual time series data | list |  | true |
### Template
```
{"fields":[],"id":"","name":"","values":[]}
```
