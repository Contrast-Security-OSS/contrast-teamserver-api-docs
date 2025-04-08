## AgentDeploymentApplicationsResponse
---
### Description
Response that returns the applications dashboard information
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| items |  | list |  | false |
| currentPage | Number of current page | integer |  | false |
| totalItems | Total number of applications | long |  | false |
| pageSize | Page size | integer |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| totalPages | Total number of pages | integer |  | false |
| messages | List of messages | list |  | false |
### Template
```
{"currentPage":0,"items":[],"messages":[],"pageSize":0,"success":true,"totalItems":0,"totalPages":0}
```
