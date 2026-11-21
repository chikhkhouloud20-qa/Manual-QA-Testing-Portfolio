
# API-TC-020 — Invalid Basic Authentication Credentials

## Objective
Verify that the API rejects a request containing invalid Basic Authentication credentials.

## Test Environment
- Tool: Postman
- HTTP Method: GET
- Endpoint: https://postman-echo.com/basic-auth
- Authentication: Basic Auth
- Test credentials: fictional invalid credentials

## Test Steps
1. Create a GET request to the endpoint.
2. Select Basic Auth in the Authorization tab.
3. Enter the invalid username `wronguser` and password `wrongpassword`.
4. Send the request.
5. Verify the HTTP status using an automated Postman assertion.

## Expected Result
The API returns HTTP 401 Unauthorized.

## Actual Result
The API returned HTTP 401 Unauthorized.

## Postman Assertion
```javascript
pm.test("Invalid Basic Auth credentials return 401", function () {
    pm.response.to.have.status(401);
});
```

## Execution Summary
- Assertions passed: 1
- Assertions failed: 0
- Test status: PASS
- Defects observed: None during this test

## Evidence
Postman execution screenshot attached to the API-TC-020 Jira issue.

## Conclusion
The API rejected the invalid Basic Authentication credentials as expected. The automated status-code assertion passed.
  
