## WebhookResponse
---
### Description
Webhook Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| webhook | Webhook | OrgWebhookResource |  | false |
### Template
```
{"messages":[],"success":true,"webhook":{"all_applications":true,"applications":[],"contrast_product":"","links":[],"name":"","payload":"","properties":[],"serverless_account_ids":[],"serverless_rule_severities":[],"url":"","use_html":true,"valid":true,"id":0,"webhook_type":""}}
```
