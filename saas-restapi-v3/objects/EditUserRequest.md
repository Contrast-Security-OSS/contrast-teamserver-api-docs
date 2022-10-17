## EditUserRequest
---
### Description
Edit User Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| api_only | API only | boolean |  | false |
| date_format | Date format | string |  | true |
| enabled | Enabled | boolean |  | false |
| first_name | First name | string |  | false |
| group_names | List of groups names | list |  | false |
| groups | List of groups IDs | list |  | false |
| last_name | Last name | string |  | false |
| protect | Protect enabled | boolean |  | false |
| role | Organization role | long |  | false |
| role_name | Organization role name | string |  | false |
| time_format | Time format | string |  | true |
| time_zone | Time zone | string |  | true |
### Template
```
{"api_only":true,"date_format":"","enabled":true,"first_name":"","group_names":[],"groups":[],"last_name":"","protect":true,"role":0,"role_name":"","time_format":"","time_zone":""}
```
