
# API-TC-012 — Combined API Validation

## Test Information

- **Project:** Junior QA Tester Portfolio
- **Test Type:** API Automated Testing
- **Tool:** Postman
- **API:** JSONPlaceholder
- **Method:** GET
- **Endpoint:** https://jsonplaceholder.typicode.com/users/1
- **Execution Status:** PASS
- **Jira Status:** Done

## Test Objective

Verify that the User Details API returns the expected HTTP status, user information, valid basic email format, and response time.

## Preconditions

- Postman is available.
- The API endpoint is accessible.
- Automated assertions are configured.

## Test Steps

1. Open Postman.
2. Send a GET request to the endpoint.
3. Verify the HTTP status code is 200.
4. Verify the user ID equals 1.
5. Verify the username equals "Bret".
6. Verify the email is a string with a valid basic format.
7. Verify the response time is below 1000 ms.
8. Review the automated test results.

## Test Execution Results

| Validation | Expected Result | Status |
|---|---|---|
| HTTP Status | 200 | PASS |
| User ID | 1 | PASS |
| Username | Bret | PASS |
| Email Format | Valid basic format | PASS |
| Response Time | Below 1000 ms | PASS |

## Execution Summary

- **Automated Tests:** 5
- **Passed:** 5
- **Failed:** 0
- **Observed Response Time:** 23 ms
- **Overall Status:** PASS
- **Defects Observed:** None during this execution

## Test Evidence

Postman execution screenshot attached to the Jira issue API-TC-012.

## Conclusion

All five automated Postman tests passed successfully.

The API response satisfied the validation criteria during this execution. No defects were observed.

The response-time threshold is illustrative and was used for training purposes.
