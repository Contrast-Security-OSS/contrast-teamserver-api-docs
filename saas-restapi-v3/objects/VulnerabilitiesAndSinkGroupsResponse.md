## VulnerabilitiesAndSinkGroupsResponse
---
### Description
List of items containing vulnerabilities and sink groups
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| licensedVulnerabilityCount | Count of licensed vulnerabilities returned. Vulnerabilities from sink groups are not included | long |  | false |
| items | List of vulnerabilities or sink groups | list |  | true |
| success | Indicates whether API response was successful or not | boolean |  | false |
| count | Total items returned. A sink group counts as 1 item | long |  | false |
| messages | List of messages | list |  | true |
### Template
```
{"count":0,"items":[],"licensedVulnerabilityCount":0,"messages":[],"success":true}
```
