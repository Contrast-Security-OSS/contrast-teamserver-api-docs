## TraceResponse
---
### Description
Vulnerability Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| trace | Vulnerability resource | TraceResource |  | false |
### Template
```
{"messages":[],"success":true,"trace":{"app_version_tags":[],"application":{},"auto_remediated_expiration_period":0,"bugtracker_tickets":[],"category":"","category_label":"","closed_time":0,"confidence":"","confidence_label":"","default_severity":"","default_severity_label":"","discovered":0,"events":[],"evidence":"","first_time_seen":0,"hasParentApp":true,"impact":"","impact_label":"","instance_uuid":"","language":"","last_time_seen":0,"last_vuln_time_seen":0,"license":"","likelihood":"","likelihood_label":"","links":[],"notes":[],"organization_name":"","parent_application":{},"pending_status":"","pending_status_creation_time":0,"pending_substatus":"","reported_to_bug_tracker":true,"reported_to_bug_tracker_time":0,"request":{"body":"","headers":[],"links":[],"method":"","normalizedUri":"","parameters":[],"port":0,"protocol":"","queryString":"","uri":"","url":"","version":""},"rule_name":"","rule_title":"","server_environments":[],"servers":[],"session_metadata":[],"severity":"","severity_label":"","sink":{"hasSink":true,"hash":0,"label":"","ruleHash":0},"status":"","status_keycode":"","sub_status":"","sub_title":"","sub_status_keycode":"","tags":[],"title":"","total_notes":0,"total_traces_received":0,"uuid":"","violations":[],"visible":true,"vulnerability_instances":[]}}
```
