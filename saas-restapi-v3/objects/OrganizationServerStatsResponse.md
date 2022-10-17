## OrganizationServerStatsResponse
---
### Description
Organization Server Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Number of servers with assess | long |  | false |
| current | Total number of servers | long |  | false |
| defend | Number of servers with defend | long |  | false |
| deleted | Number of servers recently deleted | long |  | false |
| dev | Number of Development servers | long |  | false |
| messages | List of messages | list |  | false |
| offline | Number of offline servers | long |  | false |
| offline_servers | Offline servers | list |  | false |
| onboarded | Number of servers recently onboarded | long |  | false |
| previous | Number of servers from the previous range | long |  | false |
| prod | Number of Production servers | long |  | false |
| qa | Number of QA servers | long |  | false |
| recently_deleted | Recently deleted servers | list |  | false |
| recently_onboarded | Recently onboarded servers | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"assess":0,"current":0,"defend":0,"deleted":0,"dev":0,"messages":[],"offline":0,"offline_servers":[],"onboarded":0,"previous":0,"prod":0,"qa":0,"recently_deleted":[],"recently_onboarded":[],"success":true}
```
