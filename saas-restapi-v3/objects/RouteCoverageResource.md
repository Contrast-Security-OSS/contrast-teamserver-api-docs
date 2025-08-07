## RouteCoverageResource
---
### Description
Application Route Coverage Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app | NgApplicationResource | ApplicationBaseResource |  | false |
| critical | Number of critical vulnerabilities in the route | int |  | false |
| discovered | Datetime when route was discovered | long |  | false |
| entrypointType | Entry point type of the route | entrypointtype |  | false |
| environments | Servers environments | list |  | false |
| exercised | Last time exercised | long |  | false |
| observations | List of route coverage observations | list |  | false |
| route_hash | Route Hash | string |  | false |
| route_hash_string | Route Hash string. This property will be removed in the upcoming version. Use route_hash instead. | string |  | false |
| server | Servers | list |  | false |
| servers_total | Servers total | long |  | false |
| signature | Signature | string |  | false |
| status | Status of the route | routestatus |  | false |
| total_observations | Number of observations | long |  | false |
| vulnerabilities | Number of vulnerabilities in the route | int |  | false |
### Template
```
{"app":{"app_id":"","language":"","name":"","child":true,"links":[],"master":true,"parent_app_id":"","primary":true,"roles":[],"total_modules":0},"critical":0,"discovered":0,"entrypointType":"","environments":[],"exercised":0,"links":[],"observations":[],"route_hash":"","route_hash_string":"","server":[],"servers_total":0,"signature":"","status":"","total_observations":0,"vulnerabilities":0}
```
