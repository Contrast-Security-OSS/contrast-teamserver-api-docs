## IpBlacklistResponse
---
### Description
IP Blacklist Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| address | IP Address | IPBlacklistResource |  | false |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"address":{"enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"expiration":0,"expiration_time":{},"ip":"","links":[],"name":"","trusted":true,"uuid":""},"errors":[],"messages":[],"success":true}
```
