## SarifRequest
---
### Description
SARIF file generation request
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| metadataFilters | Custom metadata filter groups selected | list |  | false |
| toolTypes | Tool types | list |  | false |
| severities | Vulnerability severities | list |  | false |
### Template
```
{"metadataFilters":[],"severities":[],"toolTypes":[]}
```
