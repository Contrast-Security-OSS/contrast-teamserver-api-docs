## TraceNoteResource
---
### Description
Trace Note Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| creation | Creation Time | long |  | false |
| creator | Creator | string |  | false |
| creator_uid | Creator uid | string |  | false |
| deletable | Deletable | boolean |  | false |
| hasBugtrackerComment | Indicates if this note has related comments in a bug tracker | boolean |  | false |
| id | Note id | string |  | false |
| last_modification | Time last modified | long |  | false |
| last_updater | Last updater | string |  | false |
| last_updater_uid | Last updater uid | string |  | false |
| note | Note | string |  | false |
| properties | Read Only Properties | list |  | false |
| readOnlyPropertyType | Type of read only properties used | string |  | false |
### Template
```
{"creation":0,"creator":"","creator_uid":"","deletable":true,"hasBugtrackerComment":true,"last_modification":0,"last_updater":"","last_updater_uid":"","links":[],"note":"","id":"","properties":[],"readOnlyPropertyType":""}
```
