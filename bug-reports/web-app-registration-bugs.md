# Title
Registration form allows invalid company identifier and phone number

## Preconditions
User is on a web application registration page

## Steps to Reproduce
1. Click on "Register"
2. Enter "123456" as company name
3. Enter "11111111111111" as company identifier
4. Enter "1111111111" as phone number
5. Click "Next"
   
## Expected Result
System should validate company identifier and phone number format and prevent invalid input

## Actual Result
System accepts invalid data and allows progression to the next step

## Severity
High

## Priority
High

## Type
Bug
