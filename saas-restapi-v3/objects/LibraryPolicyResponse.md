## LibraryPolicyResponse
---
### Description
Libraries Policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| fail_libraries | Fail libraries that violate policies | boolean |  | false |
| libraries_versions_requirements | Libraries versions requirements enabled | boolean |  | false |
| libraries_versions_requirements_all | Libraries versions requirements all | integer |  | false |
| library_versions_requirements | Libraries versions requirements | list |  | false |
| oss_enabled | oss enabled | boolean |  | false |
| restrict_libraries | Restrict libraries enabled | boolean |  | false |
| restricted_libraries | Restricted libraries SHA1 | list |  | false |
| restricted_licenses | Restricted Library Licenses | list |  | false |
### Template
```
{"count":0,"fail_libraries":true,"libraries":[],"library_versions_requirements":[],"libraries_versions_requirements_all":0,"libraries_versions_requirements":true,"messages":[],"oss_enabled":true,"restrict_libraries":true,"restricted_libraries":[],"restricted_licenses":[],"success":true}
```
