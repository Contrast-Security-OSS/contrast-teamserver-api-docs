## IpDenylistDetailsRequest
---
### Description
Request that contains a list of strings representing IP denylist uuids
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| uuids | A list of IP denylist uuids | list |  | true |
| orgUuid | The uuid for the organization | string |  | true |
### Template
```
{"orgUuid":"","uuids":[]}
```
