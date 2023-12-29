# User Registration and Login App

This is a simple web application for user registration and login built with Node.js, Express, and PostgreSQL.


### Registration

1. Open your web browser and go to [Register Site](http://localhost:3000/register).
2. Fill in the registration form with your desired username and password.
3. Click the "Register" button.

   

### Login

1. Go to [Login Site](http://localhost:3000/login).
2. Enter your registered username and password.
3. Click the "Login" button.

### Dashboard

After a successful login, you will be redirected to the dashboard at [http://localhost:3000/dashboard](Dashboard Site).

## Handling Errors

- If there is a registration error (e.g., username already exists), you will be redirected back to the registration page with an error message.

- If there is a login error (e.g., incorrect username or password), you will be redirected back to the login page with an error message.

## Technologies Used

- Node.js
- Express
- PostgreSQL
- Bcrypt for password hashing
- Session management with Express Session


