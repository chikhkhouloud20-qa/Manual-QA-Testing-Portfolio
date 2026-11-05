## TC-006 — Verify Login with Empty Username
## Application: 
- SauceDemo
- Jira ID: KAN-9
# Test Type: 
Functional Testing — Negative Scenario
# Test Status: 
PASS
# Test Objective
Verify that SauceDemo prevents login when the username field is empty.
## Preconditions
- The SauceDemo website is accessible.
- The login page is displayed.
- The user is logged out.
## Test Steps
- Open https://www.saucedemo.com/
- Leave the username field empty.
- Enter a valid password.
- Click the Login button.
- Verify that an error message appears.
## Expected Result
Login is blocked and an error message indicates that the username is required.
## Actual Result
Login was blocked and the username-required error message appeared.
## Test Status
PASS
