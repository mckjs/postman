# postman

### Install and setup
1. Open up postman
2. Click on > File > Import
3. Drag and Drop file "mckjspostman.postman_collection"

### Execute tests
When you have postman open you will see a collection folder called "mckjspostman"
Click on the > 
Click Run

### Test Scenarios
Public API 
- https://reqres.in/api/register
- https://reqres.in/api/login

#### Register
- Verify user is unable to login with "Missing password"
- Verify user is unable to login with "Missing email"
- Verify user is able to login "Register successful"

#### Login
- Invalid login with only email address provided
- Invalid login with only password provided
- Valid login with valid details
