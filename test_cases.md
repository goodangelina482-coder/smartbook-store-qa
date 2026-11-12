
# SmartBook Store — Test Cases

## Authentication Module

### TC-01: Successful Registration
- Open the registration page.
- Enter valid name, email and password.
- Click Register.
- Expected result: Account is successfully created.

### TC-02: Registration with Existing Email
- Enter an email that is already registered.
- Click Register.
- Expected result: Error message is displayed.

### TC-03: Successful Login
- Enter valid email and password.
- Click Login.
- Expected result: User successfully logs in.

### TC-04: Login with Incorrect Password
- Enter a valid email and incorrect password.
- Click Login.
- Expected result: Error message is displayed.

### TC-05: Logout
- Log in to the account.
- Click Logout.
- Expected result: User is logged out.
