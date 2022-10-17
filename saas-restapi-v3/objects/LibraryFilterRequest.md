## LibraryFilterRequest
---
### Description
Library Filter Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| apps | Application IDs | array |  | false |
| environment | Library Environments | array |  | false |
| grades | Library Grades | array |  | false |
| includeUnused | Include unused libraries | boolean |  | false |
| includeUsed | Include used libraries | boolean |  | false |
| languages | Library Language | array |  | false |
| licenses | Library Licenses | array |  | false |
| q | Keyword search | string |  | false |
| quickFilter | Quick Filter | libraryquickfiltertype |  | false |
| servers | Server IDs | array |  | false |
| status | Library Status | set |  | false |
| tags | Tags | array |  | false |
### Template
```
{"apps":[],"environment":[],"grades":[],"includeUnused":true,"includeUsed":true,"languages":[],"licenses":[],"q":"","quickFilter":"","servers":[],"status":[],"tags":[]}
```
