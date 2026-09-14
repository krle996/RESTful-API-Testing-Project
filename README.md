# RESTful-API-Testing-Project

A Postman collection testing the RESTful APIs, covering main API test scenarios.

## Overview

- **API tested:**
  - `https://api.restful-api.dev/objects`
  - `https://api.restful-api.dev/collections`
  - `https://api.restful-api.dev/register`
  - `https://api.restful-api.dev/login`
- **Purpose:** Real REST API for testing purposes
- **Scope:** 15 endpoints covering GET, POST, PUT, PATCH, DELETE HTTP methods

## Tech / Tools Used

- Postman (collection design, test scripts, collection variables)

## What Was Tested

| Category | Description |
|---|---|
| Response Time | Verifies the API responds within an acceptable time threshold |
| Status Code | Verifies the API returns the correct HTTP status code |
| Response Data | Verifies the response body contains the expected fields, values, and structure |

## Repo Structure

```
/collections      → Postman collection JSON file(s)
README.md
```

## How to Import and Run

1. Clone or download this repository.
2. Open Postman → **Import** → select the collection JSON from `/collections`.
3. Set the `baseUrl` variable (and any other required variables) to your own endpoint.
4. Run individual requests, or use **Collection Runner** to execute the full suite.
