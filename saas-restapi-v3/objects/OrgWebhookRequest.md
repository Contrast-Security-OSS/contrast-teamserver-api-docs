## OrgWebhookRequest
---
### Description
Org Webhook Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| all_applications | All Applications | boolean |  | false |
| applications | Application Id&#x27;s | array |  | false |
| name | Webhook Name | string |  | false |
| payload | Webhook Payload to send | string |  | false |
| product | Contrast Product | contrastproduct |  | false |
| properties | Webhook Properties | map |  | false |
| send_failure_notification | Send failure notification | boolean |  | false |
| serverless_account_ids | List of serverless account ids | list |  | false |
| serverless_rule_severities | List of serverless rule severities | list |  | false |
| type | Webhook Type | webhooktype |  | false |
| url | Webhook URL | string |  | false |
| use_html | Send the message with HTML Tags | boolean |  | false |
### Template
```
{"all_applications":true,"applications":[],"product":"","name":"","payload":"","properties":{},"send_failure_notification":true,"serverless_account_ids":[],"serverless_rule_severities":[],"url":"","use_html":true,"type":""}
```
