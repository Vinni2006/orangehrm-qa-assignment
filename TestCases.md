# Test Cases

## TC001 - Valid Login

**Precondition:** User has valid credentials.

**Steps:**
1. Open OrangeHRM.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

**Expected Result:**
User should successfully login and navigate to Dashboard.

---

## TC002 - Invalid Login

**Precondition:** User enters invalid credentials.

**Steps:**
1. Open OrangeHRM.
2. Enter invalid username/password.
3. Click Login.

**Expected Result:**
Error message should be displayed.

---

## TC003 - Logout Functionality

**Precondition:** User is logged in.

**Steps:**
1. Click Profile icon.
2. Select Logout.

**Expected Result:**
User should be redirected to Login page.