# Profile Page App with Sign-in and Sign-out
This app is designed to provide a personalized user experience by integrating a secure and easy-to-use sign-in and sign-out system. The main feature of the app is the profile page, where users can view and update their personal information.

## Features
- Sign-in: Secure authentication using email/username and password.
- Sign-out: Allows users to safely log out of their account.
- Profile Page: A personalized dashboard where users can:
- View and update personal information (name, email, etc.)
- Upload or change profile picture
- Manage account settings
- Security: Ensures user data privacy and provides secure login.
- Responsive Design: Optimized for different screen sizes and devices (smartphones, tablets, and desktops).

## Installation
To run the app locally, follow the steps below:
```bash
git clone 
cd /path/to/your/project
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
## Usage
- Sign-in: Enter your username or email and password to access your profile.
- Sign-out: Click the "Sign-out" button to securely log out of your account.
- Profile Page: After signing in, you’ll be redirected to your profile page where you can view and update your personal information.


## Security
- Passwords are securely stored and encrypted to ensure the privacy of user data.
- Optionally, the app supports two-factor authentication (2FA) for enhanced security.
- The app automatically logs users out after a period of inactivity.

## Technologies Used
Frontend: HTML5, CSS3
Backend: flask, python
Database: SQLALCHEMY

## Acknowledgements
- Inspired by the need for a secure and personalized user profile management system.
- The project uses various libraries and tools from the open-source community, such as python, SQLALCHEMY, flask.
