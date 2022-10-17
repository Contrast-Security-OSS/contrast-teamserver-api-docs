## ApplicationBulkUpdateRequest
---
### Description
Application Bulk Update Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| environment | Server Environment | list |  | false |
| excludedApplications | Application IDs to Exclude | array |  | false |
| filterCompliance | Filter compliance policies | array |  | false |
| filterLanguages | Filter languages | array |  | false |
| filterServers | Filter servers | array |  | false |
| filterTags | Filter tags | array |  | false |
| filterTechs | Filter techs | array |  | false |
| filterText | Filter Text | string |  | false |
| filterVulnSeverities | Filter vulnerability severities | list |  | false |
| metadataFilters | Custom metadata filter groups selected | list |  | false |
| quickFilter | Quick Filter | applicationquickfiltertype |  | false |
### Template
```
{"environment":[],"excludedApplications":[],"filterCompliance":[],"filterLanguages":[],"filterServers":[],"filterTags":[],"filterTechs":[],"filterText":"","filterVulnSeverities":[],"metadataFilters":[],"quickFilter":""}
```
