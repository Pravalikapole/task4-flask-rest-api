# Task 4: Flask REST API

## 🎯 Objective
Build a REST API with Flask to manage user data.

## 🛠 Tools
- Python
- Flask
- Postman (for testing API endpoints)

## 📌 Features
- **GET** `/users` → Fetch all users
- **GET** `/users/<id>` → Fetch user by ID
- **POST** `/users` → Create a new user
- **PUT** `/users/<id>` → Update a user
- **DELETE** `/users/<id>` → Delete a user

---

## ▶️ How to Run

### 1. Clone the repo
```bash
git clone https://github.com/your-username/task4-flask-rest-api.git
cd task4-flask-rest-api
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Flask app
```bash
python app.py
```

### 4. Test API Endpoints

# Get all users

GET http://127.0.0.1:5000/users


# Get user by ID

GET http://127.0.0.1:5000/users/1


# Create a new user

POST http://127.0.0.1:5000/users


# Update a user

PUT http://127.0.0.1:5000/users/1


# Delete a user
DELETE http://127.0.0.1:5000/users/1
### Outcome
Learned basics of REST API development using Flask

Implemented and tested CRUD operations

Practiced using Postman for API testing

Understood REST API workflow and project structure
### Project structure
task4-flask-rest-api/
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots/
    ├── get-users.png
    ├── post-user.png
    ├── put-user.png
    └── delete-user.png
