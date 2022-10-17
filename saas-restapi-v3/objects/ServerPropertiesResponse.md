## ServerPropertiesResponse
---
### Description
Server Properties Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| serverProperties | Server properties | ServerPropertiesResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"serverProperties":{"app_server_version":"","cpu_architecture":"","custom":"","language_version":"","links":[],"os_name":"","server_id":0},"success":true}
```
