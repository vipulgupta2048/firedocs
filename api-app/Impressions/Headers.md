# Headers

## Overview
Request headers are typically used for authentication and to provide information about the body of the request. The authentication headers could be anything from basic auth credentials to an API key or a token for OAuth2 security.

API Headers contain information regarding the request made to the API. Typically being used for authentication, specifying body type and tracking issues. HTTP Headers represent the metadata associated with API requests and responses. Headers carry information for:

- Request and Response Body
- Request Authorization
- Response Caching
- Response Cookies
- HTTP connection types and more

Firecamp allows you to create and configure headers right from the `Header` tab available in the request panel of the API app. Where headers can be added to requests in key-value pairs and the use of variables can also be done in the `value` field with the help of environmental snippets.

You will have to set the request headers before sending the request for testing an API. Some of the popular headers are mentioned below:

- **Authorization**: Carries credentials or UUID keys containing the authentication information of the client for the resource being requested.

- **Content-Type**: Indicates media type (text/html or text/JSON etc.) of the response sent to the client by the server, this will help the client in processing the response body correctly.

- **Accept-Charset**: Indicates character sets acceptable by the client to the server.

- **Cache-Control**: Indicates cache policy defined by the server, a cached response can be stored by the client and re-used till the time defined by the Cache-Control header.
