## FacetValue
---
### Description
A discrete value of a facet
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| displayLabel | Additional human-readable identifier for the facet value | string |  | false |
| displayName | Human-readable identifier for the facet value | string |  | true |
| count | The number of items that meet the qualification of the facet value | integer |  | false |
| value | Unique identifier for the facet value | string |  | true |
### Template
```
{"count":0,"displayLabel":"","displayName":"","value":""}
```
