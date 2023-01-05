## OrgTraceBulkFilterRequest
---
### Description
Org Trace Bulk Filter Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| appVersionTags | App Versions Tags | array |  | false |
| applicationID | Application ID | string |  | false |
| applicationIds | Application IDs - If applicationID is not provided, the result set will include traces related to submodules (child applications) | array |  | false |
| applicationImportances | List of application importances | list |  | false |
| applicationTags | Filter application tags | array |  | false |
| endDate | End Date | long |  | false |
| environments | Server Environments | array |  | false |
| excludedTraces | List of vulnerability IDs to exclude | array |  | false |
| filterText | Filter Text | string |  | false |
| languages | Filter vulnerabilities by application agent languages | list |  | false |
| licensedOnly | Show vulnerabilities only from licensed apps | boolean |  | false |
| matchRoutePathParams | Look for matching routes with path params | boolean |  | false |
| metadataFilters | Session metadata filter groups selected | list |  | false |
| quickFilter | Quick Filter | vulnerabilityquickfiltertype |  | false |
| routes | Route coverage hashes | array |  | false |
| securityStandards | Security Standards | array |  | false |
| servers | Servers | array |  | false |
| severities | Rule severities | array |  | false |
| sinkValues | Filter traces by vulnerability sink values | array |  | false |
| sinks | Filter traces by vulnerability sink hashes | array |  | false |
| startDate | Start Date | long |  | false |
| status | Vulnerability Status | set |  | false |
| substatus | Vulnerability Substatus | set |  | false |
| tags | Tags | array |  | false |
| technologies | Filter vulnerabilities by application technologies | list |  | false |
| timestampFilter | Timestamp Field used to filter | tracetimestampfield |  | false |
| tracked | Tracked traces | boolean |  | false |
| untracked | Untracked traces | boolean |  | false |
| urls | Urls | array |  | false |
| vulnTypes | Vulnerability Type | array |  | false |
### Template
```
{"appVersionTags":[],"applicationID":"","applicationIds":[],"applicationImportances":[],"applicationTags":[],"endDate":0,"environments":[],"excludedTraces":[],"filterText":"","languages":[],"licensedOnly":true,"matchRoutePathParams":true,"metadataFilters":[],"quickFilter":"","routes":[],"securityStandards":[],"servers":[],"severities":[],"sinkValues":[],"sinks":[],"startDate":0,"status":[],"substatus":[],"tags":[],"technologies":[],"timestampFilter":"","tracked":true,"untracked":true,"urls":[],"vulnTypes":[]}
```
