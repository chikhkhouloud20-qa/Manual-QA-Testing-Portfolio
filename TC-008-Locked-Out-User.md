## TC-008 — Verify Login with Locked-Out User
# Application:
SauceDemo
# Jira ID:
KAN-11
# Test Type:
Functional Testing — Negative Scenario
# Test Status:
PASS
# Test Objective
Verify that SauceDemo prevents a locked-out user from accessing the application.
## Preconditions
- The SauceDemo website is accessible.
- The login page is displayed.
- The user is logged out.
- The locked-out test account is available.
## Test Steps
- Open https://www.saucedemo.com/
- Enter the username locked_out_user.
- Enter the password secret_sauce.
- Click the Login button.
- Observe the error message.
- Verify that the user cannot access the Products page.
## Expected Result
The application prevents login and displays the following error message:
"Epic sadface: Sorry, this user has been locked out."
## Actual Result
The application prevented login, displayed the locked-out user error message, and denied access to the Products page.
## Conclusion
The application correctly restricted access for the locked-out user account.
