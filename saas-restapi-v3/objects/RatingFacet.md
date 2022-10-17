## RatingFacet
---
### Description
A facet with an aggregated grade and score
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| score | The overall numeric score for all items | integer |  | true |
| values | Set of values contained by the facet | list |  | true |
| grade | The overall letter grade for all items | string |  | true |
| displayName | Human-readable identifier for the facet | string |  | true |
| name | Unique identifier for the facet | string |  | true |
| totalCount | Total number of items considered when calculating the facet values | integer |  | false |
### Template
```
{"displayName":"","grade":"","name":"","score":0,"totalCount":0,"values":[]}
```
