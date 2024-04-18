# login-registration-form-using-flask

# Expense Tracking Web App

This is a simple expense tracking web application built using Flask and MySQL. It allows users to register, login, create expenses, and view expense statistics.

## Features

- User registration: Users can create an account by providing their name, email, and password.
- User login: Registered users can log in using their email and password.
- Session management: User sessions are managed using Flask's session mechanism.
- Expense creation: Logged-in users can create new expenses.
- Expense statistics: The application displays total earnings and expense amounts in different categories.
- Logout: Users can logout from their accounts.

## Setup Instructions

1. **Clone the repository:**
2. **Install dependencies:**
3. **Database setup:**
- Install XAMPP or another MySQL server.
- Start MySQL server.
- Create a new database named `users_data`.
- Import the SQL dump file `database.sql` provided in the repository to create the necessary tables.

4. **Configure Flask app:**
- Open `main.py` and update the MySQL connection details (host, username, password) if necessary.
- Set the Flask secret key in `app.secret_key`.

5. **Run the application:**
6.  **Access the application:**
- Open your web browser and go to `http://localhost:5000` to access the application.

## File Structure

- `main.py`: The main Flask application file containing route definitions and database connections.
- `login.html`, `register.html`, `home.html`: HTML templates for login, registration, and home pages respectively.
- `static/`: Directory containing static files such as CSS stylesheets and JavaScript files.
- `templates/`: Directory containing HTML templates used by Flask.
- `database.sql`: SQL dump file containing the database schema.
