## PasswordPolicyResource
---
### Description
Password Policy Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| lock_unused_accounts | Lock unused accounts | int |  | false |
| min_length | Minimum length | int |  | false |
| min_lower | Minimum lower letters | int |  | false |
| min_numbers | Minimum numbers | int |  | false |
| min_symbols | Minimum symbols | int |  | false |
| min_upper | Minimum upper letters | int |  | false |
| password_check_diff_chars | Check minimum differnt characters | boolean |  | false |
| password_check_min_change_time | Check password change in a time | boolean |  | false |
| password_expiration_days | Password expiration days | int |  | false |
| password_history | Retain passwords | boolean |  | false |
| password_min_change_time | Minimum days to password change | int |  | false |
| password_min_diff_chars | Minimum number of characters in the new password that must be different from the characters in the old password, | int |  | false |
| passwords_failed_attempts | Number of maximum failed login attempts | integer |  | false |
| passwords_retained | Number of passwords retained | int |  | false |
### Template
```
{"password_check_min_change_time":true,"password_check_diff_chars":true,"lock_unused_accounts":0,"passwords_failed_attempts":0,"min_length":0,"min_lower":0,"min_numbers":0,"min_symbols":0,"min_upper":0,"password_min_change_time":0,"password_min_diff_chars":0,"password_expiration_days":0,"password_history":true,"passwords_retained":0}
```
