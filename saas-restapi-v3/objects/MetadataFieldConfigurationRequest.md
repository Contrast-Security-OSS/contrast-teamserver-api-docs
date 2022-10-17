## MetadataFieldConfigurationRequest
---
### Description
Organization Metadata Field Configuration Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentLabel  | Agent Label of the field | string |  | false |
| children_types | Children objects included in a parent field | list |  | false |
| displayLabel | Display label of the field | string |  | false |
| id | Metadata field Id | long |  | false |
| required | Indicates if the field is required | boolean |  | false |
| type | Type of Metadata field | metadatafieldtype |  | true |
| unique | Indicates if the field is unique | boolean |  | false |
### Template
```
{"agentLabel ":"","children_types":[],"displayLabel":"","id":0,"required":true,"type":"","unique":true}
```
