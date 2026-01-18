**Test Case ID:** TC_SORT_001

**Title:** Verify products are sorted by name from A to Z

**Related Scenario ID:** SC_PROD_SORT_01

**Preconditions:**

User is logged in

Products page is displayed

**Test Steps:**

1. Click the sort dropdown

2. Select “Name (A to Z)”

Observe the product list order

**Expected Result:**

Products are displayed in alphabetical order (A → Z) by product name

----------------------------------------------------------------------

**Test Case ID:** TC_SORT_002

**Title:** Verify products are sorted by name from Z to A

**Related Scenario ID:** SC_PROD_SORT_02

**Preconditions:**

User is logged in

Products page is displayed

**Test Steps:**

1. Click the sort dropdown

2. Select “Name (Z to A)”

3. Observe the product list order

**Expected Result:**

Products are displayed in reverse alphabetical order (Z → A)

----------------------------------------------------------------------

**Test Case ID:** TC_SORT_003

**Title:** Verify products are sorted by price from low to high

**Related Scenario ID:** SC_PROD_SORT_03

**Preconditions:**

User is logged in

Products page is displayed

**Test Steps:**

1. Click the sort dropdown

2. Select “Price (low to high)”

3. Observe product prices in sequence

**Expected Result:**

Products are displayed in ascending order of price

Each subsequent product price is equal to or higher than the previous one

----------------------------------------------------------------------

**Test Case ID:** TC_SORT_004

**Title:** Verify products are sorted by price from high to low

**Related Scenario ID:** SC_PROD_SORT_04

**Preconditions:**

User is logged in

Products page is displayed

**Test Steps:**

1. Click the sort dropdown

2. Select “Price (high to low)”

3. Observe product prices in sequence

**Expected Result:**

Products are displayed in descending order of price

Each subsequent product price is equal to or lower than the previous one
