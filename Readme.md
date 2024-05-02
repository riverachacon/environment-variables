# Express Authentication App
This is a simple authentication app using Express, Passport.js, and PostgreSQL. It allows users to register, login, and access a secrets page if authenticated.

## Setup

1. Install Dependencies: Run 'npm i' to install the required packages.
2. Environment Variables: Create a .env file in the root directory with the following variables:

*SESSION_SECRET=your_session_secret_here
*PG_PASSWORD=your_pg_password_here

3. Database Setup: Create a PostgreSQL database named secrets and a table users with columns id (serial, primary key), email (text), and password (text).
Run the App: Start the app with node index.ejs. The server will run on port 3000 (http://localhost:3000).

## Dependencies

* Express: Web framework for Node.js.
* Body-parser: Middleware for parsing request bodies.
* PostgreSQL: PostgreSQL client for Node.js.
* Bcrypt: Library for hashing passwords.
* Passport: Authentication middleware for Node.js.
* Dotenv: Loads environment variables from a .env file.

Please modify and expand this app for your own authentication needs!