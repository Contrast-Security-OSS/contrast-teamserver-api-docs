## ApplicationBulkTagUpdateRequest
---
### Description
Application Bulk Tag Update Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| addTags | List of tags to add | list |  | true |
| filters | Filters that describe the applications to tag | ApplicationBulkUpdateRequest |  | true |
| removeTags | List of tags to remove | list |  | true |
### Template
```
{"addTags":[],"filters":{"environment":[],"excludedApplications":[],"filterCompliance":[],"filterLanguages":[],"filterServers":[],"filterTags":[],"filterTechs":[],"filterText":"","filterVulnSeverities":[],"metadataFilters":[],"quickFilter":""},"removeTags":[]}
```
