## ApplicationResponse
---
### Description
Application Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| application | Application Resource | ApplicationResource |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"application":{"active_attacks":0,"app_id":"","archived":true,"assess":true,"assessPending":true,"attack_label":"","attack_status":"","created":0,"code":0,"code_shorthand":"","defend":true,"defendPending":true,"first_seen":0,"importance":0,"importance_description":"","language":"","last_reset":0,"last_seen":0,"license":{"end":0,"level":"","links":[],"near_expiration":true,"start":0},"links":[],"master":true,"metadataEntities":[],"missingRequiredFields":[],"modules":[],"name":"","notes":"","onboarded_time":0,"override_url":"","parentApplicationId":"","path":"","policies":[],"primary":true,"production_protected":{"links":[],"protect":0,"total":0},"protect":{"isCompletelyUninstrumented":true},"roles":[],"routes":{"discovered":0,"discoveredByUrl":true,"exercised":0,"links":[]},"routingFrameworks":{"frameworks":[],"supported":true},"scores":{"grade":0,"letter_grade":"","library_scoring_type":"","links":[],"overall_scoring_type":"","platform":{"grade":0,"letter_grade":"","links":[]},"security":{"grade":0,"letter_grade":"","links":[]}},"serversWithoutDefend":true,"short_name":"","status":"","tags":[],"techs":[],"total_modules":0,"size":0,"size_shorthand":"","trace_breakdown":{"confirmed":0,"criticals":0,"fixed":0,"highs":0,"links":[],"lows":0,"meds":0,"notProblem":0,"notes":0,"remediated":0,"remediatedAutoVerified":0,"reported":0,"safes":0,"suspicious":0,"traces":0,"triaged":0},"trace_severity_breakdown":[],"validationErrorFields":[]},"messages":[],"success":true}
```
