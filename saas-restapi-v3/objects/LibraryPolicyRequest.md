## LibraryPolicyRequest
---
### Description
Library Policy Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| fail_libraries | Fail libraries that violate policies | boolean |  | false |
| libraries_versions_requirements | Libraries versions requirements enabled | boolean |  | false |
| libraries_versions_requirements_all | Libraries versions requirements all | integer |  | false |
| library_versions_requirements | Libraries versions requirements | list |  | false |
| restrict_libraries | Restrict libraries | boolean |  | false |
| restricted_libraries | Restricted libraries SHA1 | list |  | false |
| restricted_licenses | Restricted Library Licenses | list |  | false |
### Template
```
{"fail_libraries":true,"libraries_versions_requirements":true,"libraries_versions_requirements_all":0,"library_versions_requirements":[],"restrict_libraries":true,"restricted_libraries":[],"restricted_licenses":[]}
```
