# Secure Authentication System

A secure user authentication system built using **Flask**, **SQLite**, and **Flask-Bcrypt**. This project allows users to register, log in securely, access a protected dashboard, and log out.

## Features

- User Registration
- Secure Password Hashing using Flask-Bcrypt
- User Login Authentication
- Session Management
- Protected Dashboard
- Logout Functionality
- SQLite Database Integration

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- Flask-Bcrypt
- SQLite
- HTML

## Project Structure

```
Secure-Authentication/
│── templates/
│   ├── dashboard.html
│   ├── index.html
│   ├── login.html
│   └── register.html
│
│── app.py
│── config.py
│── models.py
│── requirements.txt
│── .gitignore
│── README.md
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/anushkateotia3/Secure-Authentication.git
```

2. Navigate to the project folder

```bash
cd Secure-Authentication
```

3. Create a virtual environment

```bash
python -m venv .venv
```

4. Activate the virtual environment

Windows:

```bash
.venv\Scripts\activate
```

5. Install the required packages

```bash
pip install -r requirements.txt
```

6. Run the application

```bash
python app.py
```

7. Open your browser and visit

```
http://127.0.0.1:5000
```

## Future Improvements

- Password Reset
- Email Verification
- JWT Authentication
- User Profile Page
- Remember Me Functionality

## Author

**Anushka Teotia**

GitHub: https://github.com/anushkateotia3