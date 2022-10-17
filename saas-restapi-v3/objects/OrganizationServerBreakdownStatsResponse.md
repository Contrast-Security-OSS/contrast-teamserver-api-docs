## OrganizationServerBreakdownStatsResponse
---
### Description
Organization Server Breakdown Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| assess | Number of servers with assess | long |  | false |
| containers | Breakdown of servers by container name and version | list |  | false |
| defend | Number of servers with defend | long |  | false |
| deployed | Total number of enabled servers | long |  | false |
| environments | Breakdown of servers by environment | list |  | false |
| messages | List of messages | list |  | false |
| online | Total number of online servers | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"assess":0,"containers":[],"defend":0,"deployed":0,"environments":[],"messages":[],"online":0,"success":true}
```
