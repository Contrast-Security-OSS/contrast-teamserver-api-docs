## ApplicationResource
---
### Description
Application Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| active_attacks | Total number of active attacks | long |  | false |
| app_id | Application ID | string |  | false |
| archived | Is application archived | boolean |  | false |
| assess | Is assessment enabled | boolean |  | false |
| assessPending | Is assessment pending for at least one of this application&#x27;s server | boolean |  | false |
| attack_label | Attack status label | string |  | false |
| attack_status | Attack status | attackstatus |  | false |
| code | Custom classes LoC | long |  | false |
| code_shorthand | Custom classes LoC shorthand | string |  | false |
| created | Time created | long |  | false |
| defend | Is defense enabled | boolean |  | false |
| defendPending | Is defense pending for any of this application&#x27;s servers | boolean |  | false |
| first_seen | Application first time seen | long |  | false |
| importance | Application Importance | integer |  | false |
| importance_description | Application Importance Description | applicationimportance |  | false |
| language | Application language | string |  | false |
| last_reset | Time last reset | long |  | false |
| last_seen | Time last seen | long |  | false |
| license | Application licenses | ApplicationLicenseResource |  | false |
| master | Is application master | boolean |  | false |
| metadataEntities | List of metadata entities | list |  | false |
| missingRequiredFields | List of missing required metadata fields | list |  | false |
| modules | Application child modules | list |  | false |
| name | Application name | string |  | false |
| notes | Application notes | string |  | false |
| onboarded_time | Time when the application was onboarded (this doesn&#x27;t include parent or modules) | long |  | false |
| override_url | Override url | string |  | false |
| parentApplicationId | Parent Application ID | string |  | false |
| path | Application path | string |  | false |
| policies | List of violated compliance policies | list |  | false |
| primary | Is application primary | boolean |  | false |
| production_protected | Application Production Protected counts | ApplicationServerProtectionResource |  | false |
| protect | Application data related to Protect | ApplicationProtectResource |  | false |
| roles | List of Allowed Roles | collection |  | false |
| routes | Application Route Coverage Metrics | RouteCoverageMetricsResource |  | false |
| routingFrameworks | Application routing frameworks data | ApplicationRoutingFrameworkResource |  | false |
| scores | Application scores | ScoreResource |  | false |
| serversWithoutDefend | Has servers without protection enabled | boolean |  | false |
| short_name | Short name | string |  | false |
| size | Total LoC | long |  | false |
| size_shorthand | Total LoC shorthand | string |  | false |
| status | Application status | string |  | false |
| tags | List of tags | list |  | false |
| techs | List of techs | list |  | false |
| total_modules | Number of app modules | long |  | false |
| trace_breakdown | Application vulnerability breakdown | TraceBreakdownResource |  | false |
| trace_severity_breakdown | Application vulnerability severity breakdown | collection |  | false |
| validationErrorFields | List of fields with validation errors | list |  | false |
### Template
```
{"active_attacks":0,"app_id":"","archived":true,"assess":true,"assessPending":true,"attack_label":"","attack_status":"","created":0,"code":0,"code_shorthand":"","defend":true,"defendPending":true,"first_seen":0,"importance":0,"importance_description":"","language":"","last_reset":0,"last_seen":0,"license":{"end":0,"level":"","links":[],"near_expiration":true,"start":0},"links":[],"master":true,"metadataEntities":[],"missingRequiredFields":[],"modules":[],"name":"","notes":"","onboarded_time":0,"override_url":"","parentApplicationId":"","path":"","policies":[],"primary":true,"production_protected":{"links":[],"protect":0,"total":0},"protect":{"isCompletelyUninstrumented":true},"roles":[],"routes":{"discovered":0,"discoveredByUrl":true,"entryPointTypeCounts":[],"exercised":0,"links":[]},"routingFrameworks":{"frameworks":[],"supported":true},"scores":{"grade":0,"letter_grade":"","library_scoring_type":"","links":[],"overall_scoring_type":"","platform":{"grade":0,"letter_grade":"","links":[]},"security":{"grade":0,"letter_grade":"","links":[]}},"serversWithoutDefend":true,"short_name":"","status":"","tags":[],"techs":[],"total_modules":0,"size":0,"size_shorthand":"","trace_breakdown":{"confirmed":0,"criticals":0,"fixed":0,"highs":0,"links":[],"lows":0,"meds":0,"notProblem":0,"notes":0,"remediated":0,"remediatedAutoVerified":0,"reported":0,"safes":0,"suspicious":0,"traces":0,"triaged":0},"trace_severity_breakdown":[],"validationErrorFields":[]}
```
