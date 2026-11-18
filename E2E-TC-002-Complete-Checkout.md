## E2E-TC-002 — Verify Complete Checkout Process
# Project:
SauceDemo E-Commerce Application
# Test Type:
End-to-End Functional Testing
## Test Status:
PASS
## Preconditions
- The SauceDemo website is accessible.
- Valid login credentials are available.
- The shopping cart is initially empty.
## Test Data
- Username: standard_user
- Product: Sauce Labs Backpack
- Quantity: 1
- First Name: Test
- Last Name: User
- Postal Code: 12345
## Test Steps
- Open https://www.saucedemo.com/
- Log in using valid credentials.
- Add Sauce Labs Backpack to the shopping cart.
- Open the shopping cart and verify the product and quantity.
- Click Checkout.
- Enter the required customer information.
- Click Continue.
- Verify the order summary.
- Click Finish.
- Verify the order confirmation page.
## Expected Result
The user should successfully complete the checkout process and receive an order confirmation.
## Actual Result
- The user successfully added Sauce Labs Backpack to the cart with a quantity of 1.
- The checkout information page appeared, and the application accepted the entered customer information.
- The order overview displayed:
- Product: Sauce Labs Backpack
- Quantity: 1
- Item Price: $29.99
- Tax: $2.40
- Total: $32.39
- After clicking Finish, the order confirmation page appeared and displayed the dispatch confirmation message.
## Test Execution Result
- Status: PASS
- All checkout steps passed.
- The actual results matched the expected results.
- Defects Observed
- No defects were observed during this execution.
