# Cart Test Cases

## TC-CART-001
**Title:** Add product to cart  
**Preconditions:** User is logged in and on products page  

**Steps:**
1. Click "Add to cart" button for any product  

**Expected Result:**
- Product is added to cart
- Cart icon shows 1 item  

---

## TC-CART-002
**Title:** Remove product from cart  
**Preconditions:** Product is added to cart  

**Steps:**
1. Click "Remove" button for product  

**Expected Result:**
- Product is removed from cart
- Cart icon is updated  

---

## TC-CART-003
**Title:** View cart contents  
**Preconditions:** Product is added to cart  

**Steps:**
1. Click cart icon  

**Expected Result:**
- User is redirected to cart page
- Added product is displayed  

---

## TC-CART-004
**Title:** Continue shopping from cart  
**Preconditions:** User is on cart page  

**Steps:**
1. Click "Continue Shopping" button  

**Expected Result:**
- User is redirected to products page  

---

## TC-CART-NEG-001
**Title:** Checkout with empty cart  
**Preconditions:** Cart is empty  

**Steps:**
1. Click "Checkout" button  

**Expected Result:**
- Checkout process is blocked
- User is informed that the cart is empty  
