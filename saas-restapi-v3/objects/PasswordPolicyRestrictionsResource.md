## PasswordPolicyRestrictionsResource
---
### Description
Password Policy Restriction Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| max_diff_chars | Maximum number of characters in the new password that must be different from the characters in the old password, | integer |  | false |
| max_expiration_days | Maximum expiration days | integer |  | false |
| max_password_changetime | Maximum password change time | integer |  | false |
| max_passwords_retained | Maximum passwords retained | integer |  | false |
| max_size | Maximum number of characters | integer |  | false |
| max_unused_accounts_days | Maximum unused account days | integer |  | false |
| min_diff_chars | Minimum number of characters in the new password that must be different from the characters in the old password, | integer |  | false |
| min_expiration_days | Minimum expiration days | integer |  | false |
| min_password_changetime | Minimum password change time | integer |  | false |
| min_passwords_retained | Minimum passwords retained | integer |  | false |
| min_size | Minimum number of characters | integer |  | false |
| min_unused_accounts_days | Minimum unused account days | integer |  | false |
### Template
```
{"max_password_changetime":0,"max_diff_chars":0,"max_expiration_days":0,"max_size":0,"max_passwords_retained":0,"max_unused_accounts_days":0,"min_password_changetime":0,"min_diff_chars":0,"min_expiration_days":0,"min_size":0,"min_passwords_retained":0,"min_unused_accounts_days":0}
```
