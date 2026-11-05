## TC-005 — Verify Login with Empty Password
# Applications:
SauceDemo
# Jira ID: 
KAN-8
# Test Type:
Functional Testing — Negative Scenario
## Test Objective: 
Verify that SauceDemo prevents login when the password field is empty.
## Preconditions: 
- Website accessible.
- Login page displayed. 
- User logged out.
## Test Steps: 
- Enter a valid username. 
- Leave the password empty. 
- Click Login and check the error.
## Expected Result: 
Login is blocked and a password-required message appears.
## Actual Result: 
Login was blocked and the password-required message appeared.
## Status:
PASS
