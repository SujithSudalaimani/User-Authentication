🔐 User Authentication API
This is a RESTful API built with Node.js, Express, MongoDB, and JWT for user authentication and role-based access control. It allows users to register, log in, and restricts certain endpoints to Admin users only.

📦 Tech Stack
Node.js

Express.js

MongoDB (Mongoose)

JWT (JSON Web Token)

bcrypt

dotenv

Postman (for testing)

=> Register a New User
Endpoint:
POST /api/auth/register

📥 Create a New User Endpoint: POST https://user-authentication-1-fj90.onrender.com/api/auth/register

Description: Creates a new User and saves it to the database.




=> Login User
Endpoint:
POST /api/auth/login

📄 Login User Endpoint: POST https://user-authentication-1-fj90.onrender.com/api/auth/login

Description: Login User which data available in the collection.




=> Get All Users (Admin Only)
Endpoint:
GET /api/auth/getUser

🔍 Get User Details based on Roles: GET https://user-authentication-1-fj90.onrender.com/api/auth/getUser

Description: Get User Details based on Roles provided While Registering.
Access Control:
This route is protected by JWT authentication.
Only users with role: "Admin" can access it.

I have also attached the Postman documentation for your reference and support
https://documenter.getpostman.com/view/44752909/2sB2qZF3RH
