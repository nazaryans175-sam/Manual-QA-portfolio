# Login Test Cases

This document contains manual test cases for a login page.

## TC-001 — Login with valid credentials

**Precondition:** User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click the Login button.

**Expected Result:**  
The user should successfully log in.

---

## TC-002 — Login with incorrect password

**Precondition:** User has a registered account.

**Steps:**
1. Open the login page.
2. Enter a valid username.
3. Enter an incorrect password.
4. Click the Login button.

**Expected Result:**  
An appropriate error message should be displayed.

---

## TC-003 — Login with empty fields

**Steps:**
1. Open the login page.
2. Leave the username and password fields empty.
3. Click the Login button.

**Expected Result:**  
Validation messages should be displayed.
