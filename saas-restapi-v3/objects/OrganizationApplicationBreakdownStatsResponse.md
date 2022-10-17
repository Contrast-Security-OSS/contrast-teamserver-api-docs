## OrganizationApplicationBreakdownStatsResponse
---
### Description
Organization Application Breakdown Stats Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| active | Total number of active (non-archived) applications | long |  | false |
| archived | Total number of trial (non-archived) applications | long |  | false |
| archived_with_license | Archived Applications with an applied license | long |  | false |
| critical | Total number of active applications with open criticals | long |  | false |
| enterprise | Total number of enterprise (non-archived) applications | long |  | false |
| expiring_soon | Number of non-archived Applications expiring in two weeks | long |  | false |
| messages | List of messages | list |  | false |
| recently_onboarded_apps | Recently Onboarded Applications | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| total_production | Total number of active (non-archived) applications on production servers | long |  | false |
| trial | Total number of trial (non-archived) applications | long |  | false |
| unprotected | Total number of active (non-archived) applications without protect on production servers | long |  | false |
| unseen_apps | Unseen Applications; apps with offline servers | list |  | false |
### Template
```
{"active":0,"archived":0,"archived_with_license":0,"critical":0,"enterprise":0,"expiring_soon":0,"messages":[],"recently_onboarded_apps":[],"success":true,"total_production":0,"trial":0,"unprotected":0,"unseen_apps":[]}
```
