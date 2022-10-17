## ServerBulkDeleteRequest
---
### Description
Server Bulk Delete Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| deleteVulnerabilities | Should related vulnerabilities be deleted | boolean |  | true |
| filters | Filters for specifying the servers to delete | ngserverbulkfilterrequest |  | true |
### Template
```
{"deleteVulnerabilities":true,"filters":{}}
```
