## Facet
---
### Description
A categorical classification of data
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| values | Set of values contained by the facet | list |  | true |
| displayName | Human-readable identifier for the facet | string |  | true |
| name | Unique identifier for the facet | string |  | true |
| totalCount | Total number of items considered when calculating the facet values | integer |  | false |
### Template
```
{"displayName":"","name":"","totalCount":0,"values":[]}
```
