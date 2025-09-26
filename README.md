🚀 Flask REST API – User Management
📌 Overview

This project is a simple REST API built with Flask for managing user data.
It supports CRUD operations (Create, Read, Update, Delete) and uses an in-memory dictionary as the database.

🔧 Tech Stack

Python 3

Flask

Postman / cURL (for testing)

⚡ Features

GET /users → Fetch all users

GET /users/<id> → Fetch a single user by ID

POST /users → Add a new user

PUT /users/<id> → Update an existing user

DELETE /users/<id> → Delete a user

📂 Installation & Setup

Clone the repo

git clone https://github.com/your-username/flask-rest-api.git
cd flask-rest-api


Create a virtual environment (recommended)

python -m venv venv


Windows:

venv\Scripts\activate


Mac/Linux:

source venv/bin/activate


Install dependencies

pip install flask


Run the Flask app

python app.py


API will start on:

http://127.0.0.1:5000

🧪 API Endpoints
🔹 Get all users
GET /users

🔹 Get user by ID
GET /users/<id>

🔹 Add new user
POST /users
Content-Type: application/json
{
  "name": "Charlie",
  "email": "charlie@example.com"
}

🔹 Update user
PUT /users/<id>
Content-Type: application/json
{
  "email": "new_email@example.com"
}

🔹 Delete user
DELETE /users/<id>

🛠 Testing the API
Using Postman

Import endpoints manually and send requests.

Or use the provided collection (if added to repo).

Using cURL
curl http://127.0.0.1:5000/users

📌 Outcome

Learned Flask basics (routes, request handling, JSON).

Implemented CRUD operations in REST.

Tested API using Postman & curl.

✨ Author: Your Name
