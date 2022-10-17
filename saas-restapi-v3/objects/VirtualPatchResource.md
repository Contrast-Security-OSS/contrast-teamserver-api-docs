## VirtualPatchResource
---
### Description
Virtual Patch Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application_mode | Application mode | int |  | false |
| applications | List of applications | list |  | false |
| criterias | List of criterias | list |  | false |
| description | Description | string |  | false |
| enabled | Enabled | boolean |  | false |
| enabled_dev | If the Virtual Patch is enabled in Development Server | boolean |  | false |
| enabled_prod | If the Virtual Patch is enabled in Production Server | boolean |  | false |
| enabled_qa | If the Virtual Patch is enabled in QA Server | boolean |  | false |
| languages | List of languages | list |  | false |
| name | Name | string |  | false |
| technology | List of application technologies | list |  | false |
| triggered | Total number of triggered | long |  | false |
| uuid | UUID | string |  | false |
### Template
```
{"application_mode":0,"applications":[],"languages":[],"criterias":[],"description":"","enabled":true,"enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"links":[],"name":"","technology":[],"triggered":0,"uuid":""}
```
