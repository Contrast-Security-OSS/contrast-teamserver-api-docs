## RaspTrafficResponse
---
### Description
RASP Traffic Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| agentMessages | List of agent messages | list |  | false |
| blocked | Total number of blocked | long |  | false |
| errors | List of errors | list |  | false |
| exploited | Total number of exploited | long |  | false |
| ineffective | Total number of ineffective | long |  | false |
| messages | List of messages | list |  | false |
| probes | Total number of probes | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"agentMessages":[],"blocked":0,"errors":[],"exploited":0,"ineffective":0,"messages":[],"probes":0,"success":true}
```
