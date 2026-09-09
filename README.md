# Postman API Testing Collection

A hands-on API testing project created using Postman and the JSONPlaceholder REST API.

This project demonstrates API request handling, response validation, HTTP status code validation, JSON validation, and positive/negative API testing.

## API Tested

JSONPlaceholder REST API

## Test Coverage

- GET request validation
- POST request validation
- PUT request validation
- PATCH request validation
- DELETE request validation
- Positive and negative API testing
- HTTP status code validation
- Response body validation
- JSON field validation
- Headers and Content-Type validation

## Test Scenarios

| Test Case | Method | Scenario | Expected Status | Result |
|---|---|---|---|---|
| TC-API-001 | GET | Retrieve existing post | 200 | PASS |
| TC-API-002 | GET | Retrieve non-existing post | 404 | PASS |
| TC-API-003 | POST | Create new post | 201 | PASS |
| TC-API-004 | PUT | Update existing post | 200 | PASS |
| TC-API-005 | PATCH | Partially update post | 200 | PASS |
| TC-API-006 | DELETE | Delete existing post | 200 | PASS |

## HTTP Methods Covered

### GET
Used to retrieve an existing resource.

### POST
Used to create a new resource.

### PUT
Used to update an existing resource.

### PATCH
Used for partial updates.

### DELETE
Used to delete a resource.

## Validation Performed

The API responses were checked for:

- HTTP status codes
- Response body
- JSON structure
- Required fields
- Field values
- Response headers
- Content-Type

## Positive and Negative Testing

Positive scenarios verify that valid requests return the expected responses.

Negative testing includes requesting a non-existing resource and verifying the expected `404 Not Found` response.

## Project Files

- `Postman-API-Testing-Collection.json` — Postman collection
- `API-Test-Cases.xlsx` — API test case documentation
- `Screenshots-Postman/` — API execution evidence

## Tools Used

- Postman
- JSONPlaceholder REST API
- REST APIs
- JSON
- HTTP methods and status codes
