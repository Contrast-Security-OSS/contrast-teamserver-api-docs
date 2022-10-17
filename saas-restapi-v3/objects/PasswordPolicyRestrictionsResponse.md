## PasswordPolicyRestrictionsResponse
---
### Description
 Password Policy Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| restrictions | Password Policy Restrictions | PasswordPolicyRestrictionsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"restrictions":{"max_password_changetime":0,"max_diff_chars":0,"max_expiration_days":0,"max_size":0,"max_passwords_retained":0,"max_unused_accounts_days":0,"min_password_changetime":0,"min_diff_chars":0,"min_expiration_days":0,"min_size":0,"min_passwords_retained":0,"min_unused_accounts_days":0},"success":true}
```
