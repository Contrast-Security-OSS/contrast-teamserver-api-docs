## SbavRouteSessionResponse
---
### Description
Response that returns the agent session information
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentSession |  | sbavsessionresource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| messages | List of messages | list |  | false |
### Template
```
{"agentSession":{"appId":"","sessionId":""},"messages":[],"success":true}
```
