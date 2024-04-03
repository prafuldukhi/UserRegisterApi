# UserRegisterApi

Node.js/MongoDB user registration API: Users register with name, email, password, profile pic.
Data stored in MongoDB, confirmation email sent. Key tasks: RESTful '/register' endpoint, 
request validation, password hashing, profile pic upload, error handling.

## install the npm packages using npm install

## .env Configuration

Configure the following environment variables in your .env file:
# MongoDB connection URL
MONGODB_URI=add url of your database
# Port number
PORT=Add Your Port Number
jwtSecret=Add Your jwt secrent
EMAIL_USER=Add Your Email Id
EMAIL_PASS=Add Your Password
## Running the Server

Use `nodemon app.js` to run the server.

## Testing the API

Use Postman and send a POST request to `http://localhost:3000/api/register` to interact with the API.
