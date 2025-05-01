Job Application Form (Flask App)
This is a simple Flask web application that allows users to submit a job application form. Submitted data is stored in a SQLite database, and a confirmation email is sent to the applicant upon successful submission.

Features
Collects user data: First name, last name, email, start date, and occupation

Stores form submissions using SQLAlchemy and SQLite

Sends confirmation emails using Flask-Mail and Gmail SMTP

Uses Bootstrap for responsive and styled frontend

Flash message support for user feedback

Technologies Used
Python 3.10+

Flask

Flask-Mail

Flask-SQLAlchemy

Bootstrap 5

SQLite

Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/job-application-form.git
cd job-application-form
Create and activate a virtual environment

bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Set environment variable for email password
Create an App Password if using Gmail:

bash
Copy
Edit
export SUB_FORM=your_gmail_app_password  # On Linux/macOS
set SUB_FORM=your_gmail_app_password     # On Windows
Run the application

bash
Copy
Edit
python app.py
Visit the app
Open your browser and go to: http://localhost:5001

License
MIT License

