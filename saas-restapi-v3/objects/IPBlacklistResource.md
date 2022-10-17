## IPBlacklistResource
---
### Description
IP Blacklist Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| enabled_dev | If the IP Rule is enabled in Development Server | boolean |  | false |
| enabled_prod | If the IP Rule is enabled in Production Server | boolean |  | false |
| enabled_qa | If the IP Rule is enabled in QA Server | boolean |  | false |
| expiration | Expiration | int |  | false |
| expiration_time | Expiration time | date |  | false |
| ip | IP Source | string |  | false |
| name | Name | string |  | false |
| trusted | Trusted | boolean |  | false |
| uuid | UUID | string |  | false |
### Template
```
{"enabled_dev":true,"enabled_prod":true,"enabled_qa":true,"expiration":0,"expiration_time":{},"ip":"","links":[],"name":"","trusted":true,"uuid":""}
```
