**Test Case ID:** TC_CHECKOUT_001

**Title:** Verify user can complete checkout with valid information

**Related Scenario ID:** SC_CHECKOUT_01

**Preconditions:**

User is logged in

At least one product is added to the cart

**Test Steps:**

1. Navigate to Cart

2. Click Checkout

3. Enter valid First Name

4. Enter valid Last Name

5. Enter valid Postal Code

6. Click Continue

7. Click Finish

**Test Data:**

First Name: John

Last Name: Doe

Postal Code: 12345

**Expected Result:**

Checkout completes successfully

Order confirmation page is displayed

Confirmation message “Thank you for your order!” is shown

-----------------------------------------------------------------------

**Test Case ID:** TC_CHECKOUT_002

**Title:** Verify error message when First Name is missing

**Related Scenario ID:** SC_CHECKOUT_01

**Preconditions:**

User is logged in

Product exists in cart

**Test Steps:**

1. Navigate to Cart → Checkout

2. Leave First Name field empty

3. Enter Last Name and Postal Code

4. Click Continue

**Expected Result:**

Error message is displayed

Message indicates First Name is required

User remains on checkout information page

-----------------------------------------------------------------------

**Test Case ID:** TC_CHECKOUT_003

**Title:** Verify error message when Last Name is missing

**Related Scenario ID:** SC_CHECKOUT_01

**Preconditions:**

User is logged in

Product exists in cart

**Test Steps:**

1. Navigate to Cart → Checkout

2. Enter First Name

3. Leave Last Name field empty

4. Enter Postal Code

5. Click Continue

**Expected Result:**

Error message is displayed indicating Last Name is required

-----------------------------------------------------------------------

**Test Case ID:** TC_CHECKOUT_004

**Title:** Verify correct product and price details on checkout overview page

**Related Scenario ID:** SC_CHECKOUT_02

**Preconditions:**

User is logged in

Product added to cart

Checkout information entered successfully

**Test Steps:**

1. Proceed to Checkout Overview page

2. Review product name, quantity, and price

3. Review item total, tax, and total amount

**Expected Result:**

Product details match items in cart

Item total is calculated correctly

Tax and total amount are displayed correctly

