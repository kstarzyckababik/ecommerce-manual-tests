# Login Test Cases

## TC-LOGIN-001
**Title:** Login with valid credentials  
**Preconditions:** User is on login page  
**Steps:**
1. Enter valid username
2. Enter valid password
3. Click Login button  

**Expected Result:**
- User is logged in
- User is redirected to products page  

---

## TC-LOGIN-NEG-001
**Title:** Login with invalid password  
**Preconditions:** User is on login page  
**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click Login button  

**Expected Result:**
- Error message is displayed
- User is not logged in  

---

## TC-LOGIN-NEG-002
**Title:** Login with empty fields  
**Preconditions:** User is on login page  
**Steps:**
1. Leave username empty
2. Leave password empty
3. Click Login button  

**Expected Result:**
- Validation message is displayed
- Login is blocked  
