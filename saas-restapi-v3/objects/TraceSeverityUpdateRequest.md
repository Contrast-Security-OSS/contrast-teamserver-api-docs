## TraceSeverityUpdateRequest
---
### Description
Update Trace severity Request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| override | Propagate severity to all vulnerabilities | boolean |  | true |
| severity | New severity | ruleseverity |  | true |
### Template
```
{"override":true,"severity":""}
```
