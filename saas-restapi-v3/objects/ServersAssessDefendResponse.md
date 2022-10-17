## ServersAssessDefendResponse
---
### Description
Servers Assess Defend Mode Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | If assessment is enabled on at least one server | boolean |  | false |
| defend | If defense is enabled on at least one server | boolean |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"assess":true,"defend":true,"messages":[],"success":true}
```
