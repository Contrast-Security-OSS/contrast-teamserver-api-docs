## PasswordPolicyResponse
---
### Description
 Password Policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| policy | Password Policy | PasswordPolicyResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"policy":{"password_check_min_change_time":true,"password_check_diff_chars":true,"lock_unused_accounts":0,"passwords_failed_attempts":0,"min_length":0,"min_lower":0,"min_numbers":0,"min_symbols":0,"min_upper":0,"password_min_change_time":0,"password_min_diff_chars":0,"password_expiration_days":0,"password_history":true,"passwords_retained":0},"success":true}
```
