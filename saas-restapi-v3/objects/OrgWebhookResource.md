## OrgWebhookResource
---
### Description
Org Webhook Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | All applications | boolean |  | false |
| applications | Applications in Webhook | list |  | false |
| contrast_product | Contrast Product | contrastproduct |  | false |
| id | Id | long |  | false |
| name | Name | string |  | false |
| payload | Webhook Payload | string |  | false |
| properties | Webhook Properties | list |  | false |
| serverless_account_ids | List of serverless account ids | list |  | false |
| serverless_rule_severities | List of serverless rule severities | list |  | false |
| url | Url | string |  | false |
| use_html | Send the message with HTML Tags | boolean |  | false |
| valid | Webhook valid | boolean |  | false |
| webhook_type | Webhook Type | webhooktype |  | false |
### Template
```
{"all_applications":true,"applications":[],"contrast_product":"","links":[],"name":"","payload":"","properties":[],"serverless_account_ids":[],"serverless_rule_severities":[],"url":"","use_html":true,"valid":true,"id":0,"webhook_type":""}
```
