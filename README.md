# http-status-responser

The "http-status-responser" package is an npm package that provides a simple way to access all the HTTP response code constants values. This package defines a set of constants that represent the different HTTP status codes that can be returned by a server in response to a client request, such as 200 for "OK", 404 for "NOT_FOUND", and 500 for "INTERNAL_SERVER_ERROR". By using this package, developers can easily reference these constants in their code instead of hardcoding the status codes, which can help to make the code more readable and maintainable.

## Installation

Install http-status-codes with npm

```bash
  npm i http-status-responser
```

## Usage/Examples

```javascript
import httpStatusResponser from "http-status-responser";

const login = async (req, res) => {
    //body
    res.status(httpStatusResponser.OK).json({ user });
}


## Available http codes in latest version(1.0.5)

  OK: 200,
  CREATED: 201,
  ACCEPTED: 202,
  NON_AUTHORITATIVE_INFORMATION: 203,
  NO_CONTENT: 204,
  RESET_CONTENT: 205,
  PARTIAL_CONTENT: 206,
  MULTI_STATUS: 207,
  MULTIPLE_CHOICES: 300,
  MOVED_PERMANENTLY: 301,
  MOVED_TEMPORARILY: 302,
  SEE_OTHER: 303,
  NOT_MODIFIED: 304,
  BAD_REQUEST: 400,
  UNAUTHORIZED: 401,
  PAYMENT_REQUIRED: 402,
  FORBIDDEN: 403,
  NOT_FOUND: 404,
  METHOD_NOT_ALLOWED: 405,
  NOT_ACCEPTABLE: 406,
  PROXY_AUTHENTICATION_REQUIRED: 407,
  REQUEST_TIMEOUT: 408,
  CONFLICT: 409,
  REQUEST_TOO_LONG: 413,
  REQUEST_URI_TOO_LONG: 414,
  UNSUPPORTED_MEDIA_TYPE: 415,
  INTERNAL_SERVER_ERROR: 500,
  NOT_IMPLEMENTED: 501,
  BAD_GATEWAY: 502,
  SERVICE_UNAVAILABLE: 503,
  HTTP_VERSION_NOT_SUPPORTED: 505,
  NETWORK_AUTHENTICATION_REQUIRED: 511,

```
