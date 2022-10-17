## LibrariesStatsResponse
---
### Description
Libraries Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| stats | Stats | LibrariesStatsResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"messages":[],"stats":{"custom_loc":0,"custom_loc_shorthand":"","total":0,"library_loc":0,"library_loc_shorthand":"","num_custom_library":0,"stale":0,"num_third_party_library":0,"unknown":0,"vulnerables":0,"total_library_loc":0,"total_library_loc_shorthand":"","totalVulnerabilities":0},"success":true}
```
