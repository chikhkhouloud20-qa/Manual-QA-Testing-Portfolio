## TC-001 — Verify Product Added to Shopping Cart
# Application: 
SauceDemo
# Jira ID: 
KAN-3
## Test Type: Functional Testing — Positive Scenario
# Test Objective
Verify that a user can successfully add a product to the shopping cart.
# Preconditions
- The SauceDemo website is accessible.
- The user is logged in with valid credentials.
- The Products page is displayed.
# Test Steps
- Open https://www.saucedemo.com/
- Log in using valid credentials.
- Select a product priced at 29.99.
- Click Add to cart.
- Open the shopping cart.
- Verify the product and its price.
## Expected Result
The selected product appears in the shopping cart with the correct price of 29.99.
## Actual Result
The shopping cart displayed one added product with the expected price of 29.99.
## Test Status
PASS
# Conclusion
The add-to-cart functionality worked as expected during this test execution.
