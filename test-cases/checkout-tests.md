# Checkout Test Cases

## TC-CHECKOUT-001
**Title:** Start checkout process  
**Preconditions:** User is logged in and has product in cart  

**Steps:**
1. Go to cart
2. Click "Checkout" button  

**Expected Result:**
- User is redirected to checkout information page  

---

## TC-CHECKOUT-002
**Title:** Checkout with valid customer information  
**Preconditions:** User is on checkout information page  

**Steps:**
1. Enter first name
2. Enter last name
3. Enter postal code
4. Click "Continue"  

**Expected Result:**
- User is redirected to checkout overview page  

---

## TC-CHECKOUT-NEG-001
**Title:** Checkout with empty required fields  
**Preconditions:** User is on checkout information page  

**Steps:**
1. Leave all fields empty
2. Click "Continue"  

**Expected Result:**
- Validation message is displayed
- User remains on checkout information page  

---

## TC-CHECKOUT-003
**Title:** Finish checkout  
**Preconditions:** User is on checkout overview page  

**Steps:**
1. Click "Finish" button  

**Expected Result:**
- Order is completed
- Confirmation page is displayed  

---

## TC-CHECKOUT-004
**Title:** Cancel checkout  
**Preconditions:** User is on checkout overview page  

**Steps:**
1. Click "Cancel" button  

**Expected Result:**
- Checkout is cancelled
- User is redirected to products page  
