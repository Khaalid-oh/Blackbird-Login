# BlackBird Login Form xxxxxxxxxxx
        
This project is a login form that includes input validation for email and password fields. The email validation is done using the email-validator library, while the password validation has the following requirements:

- Minimum of 8 characters
- Should contain both uppercase and lowercase letters
- Minimum of 1 numerical digit (0-9)
- Minimum of 1 special character (!@#$%^&*, etc)
- When validation passes, a success message is displayed using the existing success snackbar in the template project. When validation fails, an error message is displayed using the error state from the text-fields Material UI component. The validation logic is unit tested using Jest.

### Usage

To use the login form, enter your email and password in the designated fields. The email field will be validated using email-validator, and the password field will be validated according to the requirements listed above.

If validation passes, a success message will be displayed. If validation fails, an error message will be displayed.

Contributing
Contributions to the project are welcome! Please see the CONTRIBUTING.md file for guidelines on how to contribute.

                        License
                        This project is licensed under the [Insert License] license - see the LICENSE.md file for details.
