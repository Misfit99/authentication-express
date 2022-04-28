# authentication-express
This small project implements authentication and security features for the web application made using Node.

## Packages Used
   - cookie-session: Simple cookie-based session middleware.
   - dotenv: Loads environment variables from .env file
   - express: Fast node.js network app framework.
   - helmet: Help secure Express/Connect apps with various HTTP headers.
   - passport: Simple, unobtrusive authentication for Node.js.
   - passport-google-oauth20: Google (OAuth 2.0) authentication strategy for Passport.
   
## Getting Started
1. Ensure you have Node installed.
2. Create /.env file with these properites.
   - CLIENT_ID
   - CLIENT_SECRET
   - COOKIE_KEY_1
   - COOKIE_KEY_2
4. Installing packages.
```sh
npm install
```
## Running the project
1. On your terminal:
```sh
npm start
```
2. Go to ```https://localhost:3000/ ``` to see the implementation
