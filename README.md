# LoginRegister
Create a new component (signup) via the Angular CLI. Extend the Login and SignUp components with logic and error messages. Add simple routing to be able to switch between the two components.
1. Create a new component

Create a new component for the registration process using the already known Angular CLI commands.
The SignUp components should contain at least the following elements:
1.1 - User Data
E-mail address (with verification of correctness)
password
Confirm Password
1.2 - Registration
Company (prefilled with FH Technikum Wien) -> cannot be changed. address (consisting of)
Street
City
ZIP code (only numbers allowed)
"Register" button to send a registration to the server.

2. Add logic for login

The form of the login component should check the email address and password entries for the following minimum requirements:
2.1 - Login Username Check
"Username" is an email address and must be checked for correctness.
2.2 - Login Password Functions
"Password" can also be displayed in plain text.
2.3 - Login check
A successful "login" should only be possible with username = test@test.at and password: "12345678" (both without quotation marks). If the login data is incorrect, a "Login failed." should be displayed on the web console. If the login was successful, a "Login successful."
2.4 - Login Mandatory fields
The "Username" and "Password" fields are mandatory. If these fields are not filled out when logging in, an error message should appear.

3. Add logic for SignUp

The registration form should check the entries for the following minimum requirements:
3.1 - SignUp user data check
"Username" is an email address and must be checked for correctness. "Password" and "Confirm password" can also be displayed in plain text.
3.2 - SignUp Password Check The "Password" and "Confirm Password" fields should be checked for equality. If the contents are not the same, an error message is displayed. Passwords should have a minimum length of 8 characters.
3.3 - SignUp address data
The "Address" field should be a TextArea and allow all characters. Only numbers are allowed in the "Zip Code" field.
The "Company" field (prefilled with FH Technikum Wien) must not be changed.
3.4 - SignUp mandatory fields
The fields "Username", "Password" and "Confirm password" are mandatory. If these fields are not filled out when the registration is sent, an error message should appear
