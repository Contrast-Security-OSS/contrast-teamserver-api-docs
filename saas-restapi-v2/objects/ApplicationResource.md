## ApplicationResource
---
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app-backend-components | AppBackend Resource component | list |  | false |
| appID | Application ID | string |  | false |
| first_seen | Application first time seen | long |  | false |
| groupName | Application group name | string |  | false |
| language | Application language | string |  | false |
| lastSeen | Last seen | long |  | false |
| libraries | Application libraries | list |  | false |
| license | Application license | string |  | false |
| name | Application name | string |  | false |
| path | Application path | string |  | false |
| platformVersion | Application platform version | string |  | false |
| platformVulnerabilities | Application plataform vulnerabilities | list |  | false |
| servers | Application servers | list |  | false |
| shortName | Application short name | string |  | false |
| sitemap-activity | Sitemap activity | SiteMapActivityResource |  | false |
| stats | Application statistics | ApplicationStatsResource |  | false |
| technology | Technology | list |  | false |
| views | Total views | long |  | false |
### Template
```
{"appID":"","app-backend-components":[],"first_seen":0,"groupName":"","language":"","lastSeen":0,"libraries":[],"license":"","links":[],"name":"","path":"","platformVersion":"","platformVulnerabilities":[],"servers":[],"shortName":"","sitemap-activity":{"entries":[],"links":[],"newest-entry-age":0,"oldest-entry-age":0,"url-count":0},"stats":{"coverage-grade":"","coverage-score":0,"criticals":0,"custom-classes-loc":0,"custom-views-accessible":0,"custom-views-count":0,"custom-views-loc":0,"expiration":{},"highs":0,"last-seen":{},"libraries-count":0,"libraries-stale":0,"libraries-unknown":0,"libraries-vulnerable":0,"links":[],"lows":0,"mediums":0,"notes":0,"overall-grade":"","overall-score":0,"platform-grade":"","platform-score":0,"security-grade":"","security-score":0,"servers-count":0,"traces-count":0},"technology":[],"views":0}
```
