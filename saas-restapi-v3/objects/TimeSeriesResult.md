## TimeSeriesResult
---
### Description
A set of time series data
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| lastSeenDate | The latest observed date in this time series | long |  | false |
| series | A set of time series data | list |  | true |
| percentageOpenFromLastMonth | Percentage open since last month | double |  | false |
### Template
```
{"lastSeenDate":0,"percentageOpenFromLastMonth":0,"series":[]}
```
