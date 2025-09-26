# Flask REST API – User Management

## Overview
A simple REST API built with Flask to manage user data. Supports CRUD operations using an in-memory dictionary.

## Tech Stack
- Python 3
- Flask
- Postman / cURL

## Features
- GET /users → Fetch all users
- GET /users/<id> → Fetch a single user
- POST /users → Add new user
- PUT /users/<id> → Update user
- DELETE /users/<id> → Delete user

## Setup
1. Clone repo
   git clone https://github.com/your-username/flask-rest-api.git
   cd flask-rest-api

2. Create virtual environment
   python -m venv venv
   # Windows: venv\Scripts\activate
   # Mac/Linux: source venv/bin/activate

3. Install Flask
   pip install flask

4. Run app
   python app.py

App runs on http://127.0.0.1:5000

## Endpoints Examples
POST /users
{
  "name": "Charlie",
  "email": "charlie@example.com"
}

PUT /users/1
{
  "email": "new_email@example.com"
}

## Testing
- Browser/Postman
- cURL: curl http://127.0.0.1:5000/users

## Outcome
Built and tested a working REST API with Flask.
