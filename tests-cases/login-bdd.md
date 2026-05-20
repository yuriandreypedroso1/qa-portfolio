# Test Cases — Login (BDD Format)

## Scenario 1 — Valid Login
**Given** the user is on the login page  
**When** they enter valid credentials  
**Then** they should be redirected to the products page  

## Scenario 2 — Invalid Password
**Given** the user is on the login page  
**When** they enter a valid username and an invalid password  
**Then** the system should display an error message indicating invalid credentials  

## Scenario 3 — Empty Fields
**Given** the user is on the login page  
**When** they click login without filling any fields  
**Then** the system should display an error message requiring both username and password
