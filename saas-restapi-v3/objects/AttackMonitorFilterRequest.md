## AttackMonitorFilterRequest
---
### Description
Attack Monitor Filter Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applicationIds | List of application ids | list |  | false |
| attackers | List of attackers | list |  | false |
| endDate | End date | long |  | false |
| environments | List of environments | set |  | false |
| live | Show live attacks | boolean |  | false |
| probed | Show probed attacks | boolean |  | false |
| ruleSeverities | Rule Severities | list |  | false |
| ruleUuids | List of rule uuid | list |  | false |
| startDate | Start date | long |  | false |
| timePeriod | Time Period | rasptimeunit |  | false |
### Template
```
{"applicationIds":[],"attackers":[],"endDate":0,"environments":[],"live":true,"probed":true,"ruleSeverities":[],"ruleUuids":[],"startDate":0,"timePeriod":""}
```
