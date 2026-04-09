# User Creation API Testing

## Overview
This project tests a User Creation API endpoint using positive, negative, and edge test scenarios.

## Endpoint
POST /signup

## Test Coverage
- Valid user creation
- Duplicate user validation
- Invalid email formats
- Weak password handling
- Incorrect data types
- HTTP method validation (GET, PUT, DELETE, PATCH)
- Content-Type validation

## Sample Test Cases

| Test Case ID | Scenario | Expected Result |
|-------------|--------|----------------|
| TC_01 | Valid email and password | User created successfully |
| TC_02 | Duplicate user | Error message returned |
| TC_03 | Invalid email format | Error message returned |
| TC_04 | Weak password | Error message returned |
| TC_05 | Wrong HTTP method | Method not allowed |

## Tools Used
- Postman
- Manual testing

## Key Findings
- API correctly prevents duplicate users
- Invalid inputs return appropriate error messages
- Some edge cases resulted in failures, indicating potential validation gaps

## Files
- user_api_test_cases.xlsx

Then click:
API testing project with structured test cases and validation scenarios
