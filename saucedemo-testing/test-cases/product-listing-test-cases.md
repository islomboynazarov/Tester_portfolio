**Test Case ID:** TC_PROD_001

**Title:** Verify all products are displayed after successful login

**Related Scenario ID:** SC_PROD_01

**Preconditions:**

User has valid login credentials

User is on the Sauce Demo login page

**Test Steps:**

1. Enter valid username

2. Enter valid password

3. Click the Login button

4. Observe the Products page

**Test Data:**

Username: standard_user

Password: secret_sauce

**Expected Result:**

User is redirected to the Products page

All available products are displayed

Each product shows:

Product name

Product image

Product price

“Add to cart” button

**Actual result**

User is redirected to the Products page

All available products are displayed

Each product shows:

Product name

Product image

Product price

“Add to cart” button

--------------------------------------------------------------------------------------------------------------------

**Test Case ID:** TC_PROD_002

**Title:** Verify total number of products displayed is correct

**Related Scenario ID:** SC_PROD_02

**Preconditions:**

User is logged in successfully

**Test Steps:**

1. User is redirected to the Products page

2. Count the number of products displayed on the Products page

**Expected Result:**

Exactly 6 products are displayed on the Products page

**Actual Results**

Exactly 6 products are displayed on the Products page

--------------------------------------------------------------------------------------------------------------------

**Test Case ID:** TC_PROD_003

**Title:** Verify no product information is missing after login

**Related Scenario ID:** SC_PROD_03

**Preconditions:**

User is logged in successfully

**Test Steps:**

1. Review each product listed on the Products page

Expected Result:

No product is missing name, price, image, or action button

No broken images or empty fields are present

Actual Result:

No product is missing name, price, image, or action button

No broken images or empty fields are present


