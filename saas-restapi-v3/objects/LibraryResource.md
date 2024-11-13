## LibraryResource
---
### Description
Library Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agePenalty | Library age penalty | double |  | false |
| app_language | Application language | string |  | false |
| apps | List of applications | list |  | false |
| bugtracker_tickets | List of bugtracker tickets created | list |  | false |
| class_count | Number of total classes | long |  | false |
| classes_used | Number of classes used | long |  | false |
| critical_vulnerabilities | Number of total critical vulnerabilities | integer |  | false |
| custom | Is custom | boolean |  | false |
| file_name | File name | string |  | false |
| file_version | Application file version | string |  | false |
| grade | Grade | string |  | false |
| group | Application library group/package | string |  | false |
| hash | Hash | string |  | false |
| high_vulnerabilities | Number of total High vulnerabilities | integer |  | false |
| invalid_version | This Library is using an invalid version | boolean |  | false |
| latest_release_date | Latest release date | long |  | false |
| latest_version | Latest version | string |  | false |
| libScore | Library score | int |  | false |
| library_class_usage_counts | A list of class usage counts for each application ID | list |  | false |
| license_violation | In violation of Organization&#x27;s license restriction | boolean |  | false |
| licenses | Library licenses | set |  | false |
| loc | Lines of code | long |  | false |
| loc_shorthand | Lines of code shorthand | string |  | false |
| merge_apps | List of applications | list |  | false |
| months_outdated | Months out of date | long |  | false |
| ossEnabled | OSS Permission | boolean |  | false |
| release_date | Release date | long |  | false |
| remediation_guidance | Remediation guidance for vulnerable libraries | nglibraryremediationguidance |  | false |
| restricted | This Library is restricted | boolean |  | false |
| servers | List of servers | list |  | false |
| tags | List of tags | list |  | false |
| total_vulnerabilities | Number of total vulnerabilities | long |  | false |
| version | Version | string |  | false |
| versionPenalty | Library version penalty | double |  | false |
| version_restriction | This Library must be within this version | integer |  | false |
| versions_behind | Versions behind | int |  | false |
| vulns | List of vulnerabilities | list |  | false |
### Template
```
{"agePenalty":0,"app_language":"","apps":[],"bugtracker_tickets":[],"class_count":0,"classes_used":0,"critical_vulnerabilities":0,"custom":true,"file_name":"","file_version":"","grade":"","group":"","hash":"","high_vulnerabilities":0,"invalid_version":true,"latest_release_date":0,"latest_version":"","library_class_usage_counts":[],"license_violation":true,"licenses":[],"links":[],"loc":0,"loc_shorthand":"","merge_apps":[],"months_outdated":0,"ossEnabled":true,"release_date":0,"remediation_guidance":{},"restricted":true,"libScore":0,"servers":[],"tags":[],"total_vulnerabilities":0,"version":"","versionPenalty":0,"version_restriction":0,"versions_behind":0,"vulns":[]}
```
