## TraceFilterResponse
---
### Visibility
PUBLIC
### Description
Trace Filter Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| count | Count | long |  | false |
| licensedCount | Number of Traces from a licensed app | long |  | false |
| messages | List of messages | list |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
| traces | List of traces | list |  | false |
### Template
```
{"count":0,"licensedCount":0,"links":[],"messages":[],"success":true,"traces":[]}
```
