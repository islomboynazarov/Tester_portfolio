Test Case ID: TC_LOGIN_001

Title: Verify login with valid credentials

Related Scenario ID: SC_LOGIN_01

Preconditions:
- User is on the login page

Test Steps:
1. Enter valid username
2. Enter valid password
3. Click Login

Preconditions:
Valid URL Test Data

Test Data: 
username - standard_user
password - secret_sauce

Post Condition: 
User should be able to the home page

Expected Result:
- User is logged in successfully

Actual Result:
- User is logged in successfully
--------------------------------------------------------
Test Case ID: TC_LOGIN_002

Title: Verify login with invalid username and a valid password

Related Scenario ID: SC_LOGIN_01

Preconditions:
- User is on the login page

Test Steps:
1. Enter an invalid username
2. Enter a valid password
3. Click on the Login button

Preconditions:
Valid URL Test Data

Test Data: 
username - testuser
password - secret_sauce

Post Condition: 
User should be able to see the home page

Expected Result:
- Error message pops up saying "Username and password do not match any user in this service"

Actual Result:
- Error message pops up saying "Username and password do not match any user in this service"
------------------------------------------------------------------------------------------------------------------------------

Test Case ID: TC_LOGIN_003

Title: Verify login with a valid username and an invalid password

Related Scenario ID: SC_LOGIN_01

Preconditions:
- User is on the login page

Test Steps:
1. Enter a valid username
2. Enter an invalid password
3. Click on the Login button

Preconditions:
Valid URL Test Data

Test Data: 
username - standart_user
password - madeup_password

Post Condition: 
User should be able to see the home page

Expected Result:
- Error message pops up saying "Username and password do not match any user in this service"

Actual Result:
- Error message pops up saying "Username and password do not match any user in this service"
------------------------------------------------------------------------------------------------------------------------------

Test Case ID: TC_LOGIN_004

Title: Verify login with an invalid username and an invalid password

Related Scenario ID: SC_LOGIN_01

Preconditions:
- User is on the login page

Test Steps:
1. Enter an invalid username
2. Enter an invalid password
3. Click on the Login button

Preconditions:
Valid URL Test Data

Test Data: 
username - test_user
password - madeup_password

Post Condition: 
User should be able to see the home page

Expected Result:
- Error message pops up saying "Username and password do not match any user in this service"

Actual Result:
- Error message pops up saying "Username and password do not match any user in this service"
------------------------------------------------------------------------------------------------------------------------------

Test Case ID: TC_LOGIN_005

Title: Verify login with an empty fields

Related Scenario ID: SC_LOGIN_01

Preconditions:
- User is on the login page

Test Steps:
1. Leave username spot empty
2. Leave password spot empty
3. Click on the Login button

Preconditions:
Valid URL Test Data

Test Data: 
no data

Post Condition: 
User should be able to see the home page

Expected Result:
- Error message pops up saying "Username is required"

Actual Result:
- Error message pops up saying "Username is required"
------------------------------------------------------------------------------------------------------------------------------

