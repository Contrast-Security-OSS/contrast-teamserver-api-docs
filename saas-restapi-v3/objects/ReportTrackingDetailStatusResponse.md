## ReportTrackingDetailStatusResponse
---
### Description
Response schema for report tracking detail status
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| reportType |  | reporttype |  | false |
| success | Indicates whether API response was successful or not | boolean |  | true |
| downloadUrl | URL to download the report if it is available | string |  | false |
| status |  | reportstatus |  | false |
| messages | List of messages | list |  | true |
### Template
```
{"downloadUrl":"","messages":[],"reportType":"","status":"","success":true}
```
