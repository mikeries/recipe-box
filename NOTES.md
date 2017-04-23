# Recipe Box
## A simple web app for creating, storing, and retrieving your favorite recipes

## Notes
User visits home page, and will be provided with a welcome screen describing
the program, and including links to signup or login in to being.

Signup page will allow user to create a login, then log the user in
* Login information will include name, email, and password.  Secure password
storage is a requirement of the assignment, so use has_secure_password in the user class.
* Validition checks:
  * Include second password field and make sure it is identical
  * Verify that name, email and password are not empty or blank.
  * Check to make sure it is not a duplication of an existing user.
  * If invalid, route user back to login page, but include appropriate error message

Login page will ask for user email and password.
* 