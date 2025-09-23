## TraceResource
---
### Description
Trace Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| app_version_tags | List of application version tags | list |  | false |
| application | Application | ngapplicationtracebaseresource |  | false |
| auto_remediated_expiration_period | Period of Remediation Policy that Auto-Remediated this trace | long |  | false |
| bugtracker_tickets | List of bugtracker tickets created | list |  | false |
| category | Category | string |  | false |
| category_label | Translated Category Value | string |  | false |
| closed_time | Time closed | long |  | false |
| confidence | Confidence | string |  | false |
| confidence_label | Translated Confidence Value | string |  | false |
| default_severity | Default Severity | ruleseverity |  | false |
| default_severity_label | Default Severity Translated value | string |  | false |
| discovered | Instance discovered time | long |  | false |
| events | List of events | list |  | false |
| evidence | Evidence | string |  | false |
| first_time_seen | Vulnerability time first seen | long |  | false |
| hasParentApp | Has Parent App | boolean |  | false |
| impact | Impact | string |  | false |
| impact_label | Translated Impact Value | string |  | false |
| instance_uuid | Vulnerability instance uuid | string |  | false |
| language | Language | string |  | false |
| last_time_seen | Vulnerability time last seen | long |  | false |
| last_vuln_time_seen | Instance last received time | long |  | false |
| license | License | servicelevel |  | false |
| likelihood | Likelihood | string |  | false |
| likelihood_label | Translated Likelihood Value | string |  | false |
| notes | List of notes | list |  | false |
| organization_name | Organization Name | string |  | false |
| parent_application | Parent Application ID | ngapplicationtracebaseresource |  | false |
| pending_status | Pending status | string |  | false |
| pending_status_creation_time | Pending status creation time | long |  | false |
| pending_substatus | Pending substatus | string |  | false |
| reported_to_bug_tracker | Is reported to bug tacker | boolean |  | false |
| reported_to_bug_tracker_time | Time reported to bug tracker | long |  | false |
| request | Request | TraceHttpRequestResource |  | false |
| rule_name | Rule name | string |  | false |
| rule_title | Rule title | string |  | false |
| server_environments | List of servers environments | list |  | false |
| servers | List of servers | list |  | false |
| session_metadata | Session metadata associated to this vulnerability | list |  | false |
| severity | Severity | string |  | false |
| severity_label | Translated Severity Value | string |  | false |
| sink | Object that includes the sink information for the vulnerability | VulnerabilitySinkResource |  | false |
| status | Status | string |  | false |
| status_keycode | Status keycode | string |  | false |
| sub_status | Substatus | string |  | false |
| sub_status_keycode | Substatus Keycode | vulnerabilitysubstatus |  | false |
| sub_title | Subtitle | string |  | false |
| tags | List of tags | list |  | false |
| title | Title | string |  | false |
| total_notes | Total of notes | long |  | false |
| total_traces_received | Total traces received | long |  | false |
| uuid | Uuid | string |  | false |
| violations | Remediation policy violations | list |  | false |
| visible | Is visible | boolean |  | false |
| vulnerability_instances | List of all the vulnerability instances associated to this vulnerability | list |  | false |
| vulnerability_uuid | Vulnerability uuid | string |  | false |
### Template
```
{"app_version_tags":[],"application":{},"auto_remediated_expiration_period":0,"bugtracker_tickets":[],"category":"","category_label":"","closed_time":0,"confidence":"","confidence_label":"","default_severity":"","default_severity_label":"","discovered":0,"events":[],"evidence":"","first_time_seen":0,"hasParentApp":true,"impact":"","impact_label":"","instance_uuid":"","language":"","last_time_seen":0,"last_vuln_time_seen":0,"license":"","likelihood":"","likelihood_label":"","links":[],"notes":[],"organization_name":"","parent_application":{},"pending_status":"","pending_status_creation_time":0,"pending_substatus":"","reported_to_bug_tracker":true,"reported_to_bug_tracker_time":0,"request":{"body":"","headers":[],"links":[],"method":"","normalizedUri":"","parameters":[],"port":0,"protocol":"","queryString":"","uri":"","url":"","version":""},"rule_name":"","rule_title":"","server_environments":[],"servers":[],"session_metadata":[],"severity":"","severity_label":"","sink":{"hasSink":true,"hash":0,"label":"","ruleHash":0},"status":"","status_keycode":"","sub_status":"","sub_title":"","sub_status_keycode":"","tags":[],"title":"","total_notes":0,"total_traces_received":0,"uuid":"","violations":[],"visible":true,"vulnerability_instances":[],"vulnerability_uuid":""}
```
