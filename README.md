# User-Authentication

## Description
This project provides Authentication services to the user by providing Signup/Register and Login/Logout APIs. It has various layers of authorization and authentication to provide maximum possible security. Featureincludes login, logout, register, email or username validation and user authentication using PassportJS. Can be used as starter for other Node.JS applications using Node.js, Express, Passport, Mongoose, and more.

## Usage
### Install All Packages
```bash
  npm install express ejs mongoose bcryptjs connect-flash cookie-parser express-session memorystore passport passport-local
```
### Install Nodemon for Development
```bash
  npm install -D nodemon
```

## User signup & login

- Check for the valid email id and username when user register.
- Login form allows users to login to the website after they have created their account using the signup form.
- PassportJS used for authenciationg the user

## End Points
**POST** - http://localhost:8000/signup

**POST** - http://localhost:8000/login

## Parameters
| Parameter         | type        |      description                                    |
| -----------------  | ----------- | ---------------------------------------------------- |
| username | string | username of the user |
| email | string | email id of the user |
| password | string | user password |
| confirmpassword | string | confirm user password |


## API

| Method | URI               | Middleware |
| ------ | ----------------- | ---------- |
| POST   | /signup           |            |
| POST   | /login            |            |
| POST   | /logout           |  auth      |
| POST   | /profile          |  auth      |






