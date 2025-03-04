## TraceNoteResponse
---
### Description
Trace Note Response
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| errors | List of errors | list |  | false |
| messages | List of messages | list |  | false |
| note | Note | TraceNoteResource |  | false |
| success | Indicates whether API response was successful or not | boolean |  | false |
### Template
```
{"errors":[],"messages":[],"note":{"creation":0,"creator":"","creator_uid":"","deletable":true,"hasBugtrackerComment":true,"last_modification":0,"last_updater":"","last_updater_uid":"","links":[],"note":"","id":"","properties":[],"readOnlyPropertyType":""},"success":true}
```
