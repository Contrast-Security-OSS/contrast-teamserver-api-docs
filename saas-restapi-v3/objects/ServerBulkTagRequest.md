## ServerBulkTagRequest
---
### Description
Server Bulk Tag Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| addTags | List of tags to add | list |  | true |
| filters | Filters that describe the servers to tag | ngserverbulkfilterrequest |  | true |
| removeTags | List of tags to remove | list |  | true |
### Template
```
{"addTags":[],"filters":{},"removeTags":[]}
```
