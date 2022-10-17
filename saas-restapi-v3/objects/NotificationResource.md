## NotificationResource
---
### Description
Notification Organization Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| message | Notification message | string |  | false |
| messageVariables | Notification message variables | map |  | false |
| notification_id | Notification id | string |  | false |
| properties | Notification properties | list |  | false |
| read | Check if notification status is read | boolean |  | false |
| source_type | Notification source type | notificationsourcetype |  | false |
| timestamp | Notification timestamp | long |  | false |
| type | Notification type | notificationtrigger |  | false |
### Template
```
{"links":[],"message":"","messageVariables":{},"notification_id":"","properties":[],"read":true,"source_type":"","timestamp":0,"type":""}
```
