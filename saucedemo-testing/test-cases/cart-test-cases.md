**Test Case 1: Add product to cart**

**Test Case ID:** TC_CART_001

**Title:** Verify product can be added to cart

**Related Scenario ID:** SC_CART_01

**Preconditions:**

User is logged in

Products page is displayed

**Test Steps:**

1. Click Add to cart button for any product

2. Observe cart icon

**Expected Result:**

Product is added to the cart

Cart icon badge displays count 1

“Add to cart” button changes to “Remove”

--------------------------------------------------------

**Test Case 2: Remove product from cart** (Products page)

**Test Case ID:** TC_CART_002

**Title:** Verify product can be removed from cart from products page

**Related Scenario ID:** SC_CART_01

**Preconditions:**

Product has been added to cart

**Test Steps:**

1. Click Remove button for the added product

2. Observe cart icon

**Expected Result:**

Product is removed from the cart

Cart icon badge is removed or updated correctly

“Remove” button changes back to “Add to cart”
