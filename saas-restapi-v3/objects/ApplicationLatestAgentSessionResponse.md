## ApplicationLatestAgentSessionResponse
---
### Description
Response that returns the application latest custom agent session
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentSession |  | agentsessionresource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| messages | List of messages | list |  | false |
### Template
```
{"agentSession":{"agentSessionId":"","createdDate":{},"metadataSessions":[]},"messages":[],"success":true}
```
