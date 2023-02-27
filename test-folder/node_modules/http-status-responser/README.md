# http-status-responser

All the constants values for Http Status Cods

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


## Available http codes in the latest version(1.0.5)

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
  NAUTHORIZED: 401,
  PAYMENT_REQUIRED: 402,
  FORBIDDEN: 403,
  NOT_FOUND: 404,
  METHOD_NOT_ALLOWED: 405,
  NOT_ACCEPTABLE: 406,
  REQUEST_TIMEOUT: 408,
  PROXY_AUTHENTICATION_REQUIRED: 407,
  REQUEST_TOO_LONG: 413,
  REQUEST_URI_TOO_LONG: 414,
  UNSUPPORTED_MEDIA_TYPE: 415,
  INTERNAL_SERVER_ERROR: 500,
  NOT_IMPLEMENTED: 501,
  BAD_GATEWAY: 502,
  HTTP_VERSION_NOT_SUPPORTED: 505,
  NETWORK_AUTHENTICATION_REQUIRED: 511,

```
