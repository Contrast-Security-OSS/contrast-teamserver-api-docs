## MetadataConfigurationRequest
---
### Description
Organization Metadata Configuration Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| existing_apps_action | Action to do when the validation fails in existing applications | operation |  | true |
| fields | List of Metadata field configurations | list |  | false |
| new_apps_action | Action to do when the validation fails in new applications | operation |  | true |
### Template
```
{"existing_apps_action":"","fields":[],"new_apps_action":""}
```
