# Bug Report

**ID:** BUG-001  
**Title:** Checkout can be started with empty cart  

## Environment
- Browser: Firefox
- Environment: https://www.saucedemo.com/

## Preconditions
- User is logged in
- Cart is empty  

## Steps to Reproduce
1. Go to products page
2. Click cart icon
3. Click "Checkout" button  

## Actual Result
- User is able to start checkout process with empty cart  

## Expected Result
- Checkout process should be blocked
- User should be informed that the cart is empty  

## Severity
Medium  

## Priority
Medium  

## Notes
This behavior may lead to user confusion and incorrect order flow.
