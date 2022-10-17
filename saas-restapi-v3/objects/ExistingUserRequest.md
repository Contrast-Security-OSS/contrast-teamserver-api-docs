## ExistingUserRequest
---
### Description
Existing User Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| api_only | API only | boolean |  | false |
| enabled | Enabled | boolean |  | false |
| groups | List of groups IDs | list |  | false |
| protect | Protect | boolean |  | false |
| role | Organization role | long |  | true |
| username | Username | string |  | true |
### Template
```
{"api_only":true,"enabled":true,"groups":[],"protect":true,"role":0,"username":""}
```
