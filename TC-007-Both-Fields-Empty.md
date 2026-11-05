## TC-007 — Verify Login with Both Fields Empty
# Application:
SauceDemo
# Jira ID: 
KAN-10
# Test Type:
Functional Testing — Negative Scenario
## Test Status: 
PASS
## Test Objective
Verify that SauceDemo prevents login when both the username and password fields are empty.
## Preconditions
- The SauceDemo website is accessible.
- The login page is displayed.
- The user is logged out.
## Test Steps
- Open https://www.saucedemo.com/
- Leave the username field empty.
- Leave the password field empty.
- Click the Login button.
- Observe the error message.
## Expected Result
Login is blocked and a username-required error message appears.
## Actual Result
Login was blocked and the username-required error message appeared.
# Test Status
PASS
# Conclusion
The login validation worked as expected when both fields were empty.
