## ApplicationServersBreakdownResponse
---
### Description
Application Servers Breakdown Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| count | Total Applications | long |  | false |
| development | Number of servers in development | long |  | false |
| messages | List of messages | list |  | false |
| production | Number of servers in production | long |  | false |
| protected_development | Number of protected servers in development | long |  | false |
| protected_production | Number of protected servers in production | long |  | false |
| protected_qa | Number of protected servers in qa | long |  | false |
| qa | Number of servers in qa | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"count":0,"development":0,"messages":[],"production":0,"protected_development":0,"protected_production":0,"protected_qa":0,"qa":0,"success":true}
```
