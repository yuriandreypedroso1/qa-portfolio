# Bug Report — Checkout Allowed with Empty Cart

## Preconditions
- User is logged in with valid credentials
- Shopping cart is empty

## Environment
- Browser: Firefox
- OS: Ubuntu
- URL: https://www.saucedemo.com

## Steps to Reproduce
1. Access saucedemo.com
2. Log in with valid credentials
3. Do not add any items to the cart
4. Click on the cart icon
5. Click "Checkout"

## Expected Result
System should block the checkout and display a message indicating the cart is empty

## Actual Result
System allows the user to proceed to the checkout form without any items in the cart

## Severity
High

## Severity Justification
Core purchase flow accepts empty orders, which could generate ghost orders in production

## Priority
High

## Type
Bug

## ISO 25010 Category
Functional Suitability

## ISO 25010 Subcategory
Functional Correctness
