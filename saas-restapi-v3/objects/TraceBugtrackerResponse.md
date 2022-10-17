## TraceBugtrackerResponse
---
### Description
Trace Bugtracker Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| bugtracker_attachment_errors | List of errors caused by attachment creation | set |  | false |
| bugtracker_errors | List of bugtracker errors | set |  | false |
| error_code | Error code returned from bugtracker | integer |  | false |
| errors | List of errors | list |  | false |
| fail_msg | Failure message | string |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| success_msg | Success message | string |  | false |
### Template
```
{"bugtracker_attachment_errors":[],"bugtracker_errors":[],"error_code":0,"errors":[],"fail_msg":"","messages":[],"success":true,"success_msg":""}
```
