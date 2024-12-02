## CVEFilterResponse
---
### Description
Response containing CVE information along with impacted libraries, servers and applications Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| cve | The cve object detailing all attributes relating to a CVE | artifactvulnerability |  | false |
| libraries | A list of libraries that are impacted by the CVE | list |  | false |
| serverAppRisk | A list of servers that are impacted by the CVE along with the specific applications on each of those servers that are impacted by the CVE | list |  | false |
### Template
```
{"cve":{},"libraries":[],"serverAppRisk":[]}
```
