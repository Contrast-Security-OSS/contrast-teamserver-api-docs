## VSTSWorkItemTypeResource
---
### Description
VSTS Work Item Type Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| default_field | Default field for severity mapping | VSTSFieldResource |  | false |
| states | List of allowed states for the given work item type | collection |  | false |
| type | Work item type info | workitemtypeinfo |  | false |
### Template
```
{"default_field":{"field":{},"values":[]},"states":[],"type":{}}
```
