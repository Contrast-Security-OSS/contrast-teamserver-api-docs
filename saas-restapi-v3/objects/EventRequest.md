## EventRequest
---
### Description
Event Request (Event Filter Form)
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| applications | Filter applications | array |  | false |
| attackUuid | Attack UUID | string |  | false |
| attackers | Filter attackers | array |  | false |
| endDate | End date | long |  | false |
| environments | Filter servers environments | array |  | false |
| events | List of attack events | list |  | false |
| includeBotBlockers | Include bot blocking events | boolean |  | false |
| includeIpBlacklist | Include IP blacklist events | boolean |  | false |
| includeSuppressed | Include suppressed events | boolean |  | false |
| keyword | Keyword | string |  | false |
| live | Active Attacks | boolean |  | false |
| quickFilter | Quick Filter | eventquickfiltertype |  | false |
| results | Filter results | array |  | false |
| rules | Filter rules | array |  | false |
| servers | Filter servers | array |  | false |
| severities | Attack Severities | list |  | false |
| sourceNameIDs | Filter by source name IDs | collection |  | false |
| startDate | Start date | long |  | false |
| statuses | Attack Statuses | list |  | false |
| tags | Filter tags | array |  | false |
### Template
```
{"applications":[],"attackUuid":"","attackers":[],"endDate":0,"environments":[],"events":[],"includeBotBlockers":true,"includeIpBlacklist":true,"includeSuppressed":true,"keyword":"","live":true,"quickFilter":"","results":[],"rules":[],"servers":[],"severities":[],"sourceNameIDs":[],"startDate":0,"statuses":[],"tags":[]}
```
