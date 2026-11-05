## TC-004 — Verify Login with Invalid Credentials
# Application: 
SauceDemo
# Jira ID: 
KAN-6
## Test Type:
Functional Testing — Negative Scenario
## Test Objective
Verify that the application rejects invalid login credentials and displays an appropriate error message.
## Preconditions
- SauceDemo website accessible
- Login page displayed
- User not logged in
## Test Steps
- Open SauceDemo.
- Enter an invalid username.
- Enter an invalid password.
- Click Login.
- Observe the error message.
- Verify the user remains on the login page.
## Expected Result: 
Invalid credentials are rejected.
## Actual Result:
Invalid credentials were rejected and an error message appeared.
## Status: 
PASS
