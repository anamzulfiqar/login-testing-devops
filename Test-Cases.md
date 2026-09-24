# Login Page Test Cases

## TC01 - Valid Login

**Scenario:** TS01

### Steps
1. Open Login page.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

### Expected Result
User should be successfully logged in and redirected to the Dashboard.


## TC02 - Invalid Password

**Scenario:** TS02

### Steps
1. Open Login page.
2. Enter valid username.
3. Enter invalid password.
4. Click Login.

### Expected Result
An appropriate error message should be displayed.


## TC03 - Empty Username

**Scenario:** TS03

### Steps
1. Open Login page.
2. Leave username empty.
3. Enter valid password.
4. Click Login.

### Expected Result
Username validation message should be displayed.


## TC04 - Empty Password

**Scenario:** TS04

### Steps
1. Open Login page.
2. Enter valid username.
3. Leave password empty.
4. Click Login.

### Expected Result
Password validation message should be displayed.


## TC05 - Empty Username and Password

**Scenario:** TS05

### Steps
1. Open Login page.
2. Leave username empty.
3. Leave password empty.
4. Click Login.

### Expected Result
Validation messages should be displayed.


## TC06 - Logout

**Scenario:** TS06

### Steps
1. Login with valid credentials.
2. Open Dashboard.
3. Click Logout.

### Expected Result
User should be logged out and redirected to the Login page.
