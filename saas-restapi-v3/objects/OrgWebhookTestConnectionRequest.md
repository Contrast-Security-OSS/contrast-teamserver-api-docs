## OrgWebhookTestConnectionRequest
---
### Description
Org Webhook Test Connection Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| integration_key | Integration key for PagerDuty | string |  | false |
| message_type | Message type, only for PagerDuty and VictorOps | string |  | false |
| payload | Webhook Payload to send | string |  | false |
| type | Webhook Type | webhooktype |  | false |
| url | Webhook URL to test | string |  | false |
| use_html | Send the message with HTML Tags | boolean |  | false |
### Template
```
{"integration_key":"","message_type":"","payload":"","type":"","url":"","use_html":true}
```
