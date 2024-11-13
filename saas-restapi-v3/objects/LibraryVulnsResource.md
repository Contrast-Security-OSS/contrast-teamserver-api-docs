## LibraryVulnsResource
---
### Description
Library Vulns Resource
### Fields
| Name | Description | Type | Allowed Values | Required |
| ---- | ----------- | ---- | -------------- | -------- |
| access_complexity | Access complexity | string |  | false |
| access_vector | Access vector | string |  | false |
| authentication | Authentication | string |  | false |
| availability_impact | Availability impact | string |  | false |
| cisa | CISA | boolean |  | false |
| confidentiality_impact | Confidentiality impact | string |  | false |
| cvss_3_severity_value | CVSS3 severity value | double |  | false |
| cvss_3_vector | CVSS3 vector | string |  | false |
| description | Description | string |  | false |
| epss_percentile | EPSS Percentile | double |  | false |
| epss_score | EPSS Score | double |  | false |
| has_cve | Has CVE | boolean |  | false |
| has_cvss3_score | Has a cvss3 score | boolean |  | false |
| integrity_impact | Integrity impact | string |  | false |
| name | Name | string |  | false |
| references | List of references | list |  | false |
| severity_code | Severity code | string |  | false |
| severity_value | Severity value | double |  | false |
| visible | Is Visible | boolean |  | false |
### Template
```
{"access_complexity":"","access_vector":"","authentication":"","availability_impact":"","cisa":true,"confidentiality_impact":"","severity_code":"","cvss_3_severity_value":0,"cvss_3_vector":"","cvssScoringType":"","description":"","epss_percentile":0,"epss_score":0,"has_cve":true,"has_cvss3_score":true,"integrity_impact":"","links":[],"name":"","references":[],"severity_value":0,"visible":true}
```
