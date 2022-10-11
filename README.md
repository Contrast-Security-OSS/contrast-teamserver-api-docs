# Contrast Teamserver API Documentation

## **Notice**
This documentation is for Contrast Teamserver API, please visit [here](https://api.contrastsecurity.com) to view the documentation for the latest APIs.

## Introduction
Contrast offers a HATEOAS-compliant RESTful API that allows you to gather nearly all of the same information that is accessible from the UI. 
You can get vulnerability information, coverage data, download agents, and more through the API. 
Our goal is to offer the capability to allow complete integration with your Continuous Integration (CI), SIEM software, or other business intelligence dashboards.

We're always adding more endpoints, but if you'd like to see something added to the API, [file a ticket](https://support.contrastsecurity.com/hc/en-us/requests/new) and let's talk about it!

## Using the Documentation
Contrast's RESTful API documentation provides resources to understand how to use the endpoints to help you authenticate, navigate, collect data, and take actions on TeamServer programmatically. 
See the list under "APIs" at the bottom of this document to start drilling down into the information for a specific API.

## Accessing the API
To begin using the Contrast API, you need your API key, Username, and Service Key:
1) Log in to TeamServer 
2) Click the top right navigation's down arrow next to your name in the page header 
3) Your API Key and Service Key are at the bottom of the page under YOUR KEYS

Your API key and authorization credentials are required in the request header to successfully call the API.

| Header | Value |
| ----- | ----- |
| API-Key |	The API key in plaintext|
| Authorization | Base64 encoded credential of "username:service-key" |
| Accept | application/xml, application/json |

### Example
Request:
```shell
curl 'https://app.contrastsecurity.com/Contrast/api/ng/libraries/java/a10c06183fe21f3bb3dda3b5946b93db6e2ad5cc?expand=apps&expand=vulns' \
		-HAccept:application/json \
		-HAuthorization:test \
		-HAPI-Key:test
```
Response
```
{
  "success" : true,
  "messages" : [ "Library loaded successfully" ],
  "library" : {
    "grade" : "F",
    "hash" : "a10c06183fe21f3bb3dda3b5946b93db6e2ad5cc",
    "version" : "1.2",
    "custom" : false,
    "libScore" : 0.0,
    "manifest" : [ {
    ...
```

## HATEOAS Links
Starting v2, each API call response includes an array of HATEOAS (Hypermedia as the Engine of Application State) links. 
The beauty of HATEOAS is that it allows you to interact and construct an API flow solely through the hyperlinks we provide. 
You no longer need to hardcode logic into your client in order to use our API. 
We provide HATEOAS links for each call and for transactions within a call, if available.

| Element | Description |
| --- | --- |
| href | URL of the related HATEOAS link you can use for subsequent calls to the API |
| rel | The relation of the link to the current resource you have retrieved. |
| method | The HTTP method to use for the related call |

### Example
```
{
  "links": [
    {
      "href": "https://app.contrastsecurity.com/Contrast/api/applications/c0d6b545-6377-483e-8b0c-f2e2e2aa8684",
      "rel": "self",
      "method": "GET"
    },
    {
      "href": "https://app.contrastsecurity.com/Contrast/api/applications/c0d6b545-6377-483e-8b0c-f2e2e2aa8684/server",
      "rel": "server",
      "method": "GET"
    }
  ]
}
```

## Data Expansion
Starting v2, any of the data enclosed in a HATEOAS link as a GET for a resource can be expanded to be included in the resource result itself. 
To add a Data Expansion to an API call, add the expand parameter to the API Resource call. 
Each of the resources listed in this documentation lists the data available for expansion under the resource being queried.

### Example
Request:
```shell
curl https://app.contrastsecurity.com/Contrast/api/applications/c0d6b545-6377-483e-8b0c-f2e2e2aa8684/?expand=server \
		-HAccept:application/json \
		-HAuthorization:test \
		-HAPI-Key:test
```
Response:
```
[
  {
    "links": [ ... ],
    "app-id": "c0d6b545-6377-483e-8b0c-f2e2e2aa8684",
    "name": "Test Applications",
    "short-name": "Test",
    "group-name": null,
    "path": "/test",
    "language": "Java",
    "license": "Unlicensed",
    "lastSeen": 23472983488,
    "server": {
      "server-id": 1,
      "last-startup-message-received": 2/27/2014 17:30:00,
      ...
    }
  }
]
```
## Paging and Filtering
Contrast API uses pagination to limit the size of response for endpoints that can potentially return large data. 
The returned data set can be sorted by a specified data type and order. 
Filtering is also available. 
In addition to text searching, there are pre-generated filters. 
See the description of API endpoints for details.

## APIs
### [saas-restapi-v1](<./saas-restapi-v1/README.md>)
### [saas-restapi-v2](<./saas-restapi-v2/README.md>)
### [saas-restapi-v3](<./saas-restapi-v3/README.md>)
