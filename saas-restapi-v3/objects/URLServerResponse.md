## URLServerResponse
---
### Description
URL Server Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| attack_urls | Total Number of Attack URLs | long |  | false |
| avgUrlsHour | Average number of urls per hour | long |  | false |
| avgUrlsMinute | Average number of urls per minute | long |  | false |
| end | End Date | long |  | false |
| messages | List of messages | list |  | false |
| start | Start Date | long |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| urls | Number of URLs | long |  | false |
| vuln_urls | Total Number of Vuln URLs | long |  | false |
### Template
```
{"attack_urls":0,"avgUrlsHour":0,"avgUrlsMinute":0,"end":0,"messages":[],"start":0,"success":true,"urls":0,"vuln_urls":0}
```
