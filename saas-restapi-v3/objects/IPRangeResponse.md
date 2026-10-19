## IPRangeResponse
---
### Description
IP Range Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| githubAppIpExemptionEnabled | Whether this organization&#x27;s GitHub App service account is exempt from IP checks | boolean |  | false |
| ipRanges | List of IP ranges | list |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"githubAppIpExemptionEnabled":true,"ipRanges":[],"messages":[],"success":true}
```
