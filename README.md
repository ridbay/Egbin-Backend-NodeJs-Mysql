This is a Leave Management System Server Built with NodeJs and MySql.

## Available Scripts

In the project directory, you can run:

### `npm install`

Installs the dependencies<br />

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:8081](http://localhost:8081) to view it in the browser.

## Available Routes

### Base Route

    http://localhost:8081,

### User Routes

#### User Sign Up (POST)
    http://localhost:8081/auth/signup

#### User Sign In (POST)
    http://localhost:8081/auth/signin

#### Get All Users (GET)
    http://localhost:8081/auth/allUsers

#### Get One User (GET)
    http://localhost:8081/auth/OneUser

#### Update One Users(PUT)
    http://localhost:8081/auth/OneUser

#### Delete One Users(DELETE)
    http://localhost:8081/auth/OneUser


### Leave Routes

#### Create Leave Request (POST)
    http://localhost:8081/leave/createLeave


#### Get All Leave Requests (GET)
    http://localhost:8081/leave/allLeaves

#### Get All Leave Requests (GET) (A single Logged in User)
    http://localhost:8081/leave/allLeavesOneUser


#### Get One Leave Request (GET)
    http://localhost:8081/leave/OneLeave


#### Update One Leave Request (PUT)
    http://localhost:8081/leave/OneLeave

#### Delete One Leave Request (DELETE)
    http://localhost:8081/leave/OneLeave