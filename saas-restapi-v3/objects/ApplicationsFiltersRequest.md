## ApplicationsFiltersRequest
---
### Description
Applications Filters Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| appImportances | Application Importance | list |  | false |
| environment | Server Environment | list |  | false |
| filterAppCode | Filter by application code | string |  | false |
| filterCompliance | Filter compliance policies | array |  | false |
| filterLanguages | Filter languages | array |  | false |
| filterServers | Filter servers | array |  | false |
| filterTags | Filter tags | array |  | false |
| filterTechs | Filter techs | array |  | false |
| filterText | Filter Text | string |  | false |
| filterVulnSeverities | Filter vulnerability severities | list |  | false |
| includeArchived | Include archived | boolean |  | false |
| includeOnlyLicensed | Include only licensed applications | boolean |  | false |
| metadataFilters | Custom metadata filter groups selected | list |  | false |
| quickFilter | Quick Filter | applicationquickfiltertype |  | false |
| scoreLetterGrades | Filter by Application score letter grade | list |  | false |
### Template
```
{"appImportances":[],"environment":[],"filterAppCode":"","filterCompliance":[],"filterLanguages":[],"filterServers":[],"filterTags":[],"filterTechs":[],"filterText":"","filterVulnSeverities":[],"includeArchived":true,"includeOnlyLicensed":true,"metadataFilters":[],"quickFilter":"","scoreLetterGrades":[]}
```
