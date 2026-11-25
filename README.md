# Secrets — Authentication Practice App

A web app where users register, log in and view a private "secrets" page. Built to learn how user authentication and data protection work in a Node.js app.

## Features
- Register / login with user accounts stored in **MongoDB**
- Password field encrypted at rest with `mongoose-encryption`
- Credentials and encryption key kept in environment variables (`.env`), not in code
- Server-rendered views with **EJS** partials

## Tech
Node.js · Express · EJS · MongoDB Atlas · Mongoose

## Run locally
```bash
npm install
# .env
# DB_USER=<mongodb user>
# DB_PASS=<mongodb password>
# SECRET=<encryption key>
node app.js
```
