E Library Managemnt System Team Members:- 1.Priyanka MS - 4MC23IS082 2.Sanika H - 4MC23IS095 3.Siri SU - 4MC23IS106 4.Spoorthi VS - 4MC23IS107

This project is a Library Management System developed using the Django framework in Python.
It replaces manual record-keeping in traditional libraries with a faster, more accurate, and user-friendly web-based system.

-> Problem Statement Manual library management involves:

Time-consuming record keeping
Frequent data entry errors
Difficulty in tracking issued and returned books
To solve these issues, this project introduces automation using Django.
-> Objectives

Simplify the process of issuing and returning books
Maintain accurate digital records
Provide quick and easy book searches
Save time and reduce human error
Improve overall efficiency and accessibility
-> System Requirements -> Software - Python
- Django Framework
- HTML, CSS, JavaScript
- MySQL or SQLite Database

-> Hardware - Laptop or PC with at least 4 GB RAM

-> Users

 1.Librarian (Admin) → manages books, issues, and returns  
 2.Students → search books, view availability, and track borrowing history  
->Architecture 1.Frontend: HTML, CSS, JavaScript

2.Backend: Django Framework (Python)
3.Database: MySQL / SQLite
The backend handles business logic and data storage, while the frontend provides an interactive interface.
-> Features

User login and authentication
Add, update, or remove books
Issue and return tracking
Search books by title or author
Student borrowing history
Secure and reliable data management
-> Advantages

Saves time and effort
Reduces paperwork
Provides accurate and secure record keeping
Accessible from anywhere
⚙️ How to Setup and Run the Project

Step 1: Clone or Download the Project Go to the GitHub repository: https://github.com/sanika-harish/library_management_system Click the green Code button and select Download ZIP, then extract it on your computer. Or clone it using: git clone https://github.com/sanika-harish/library_management_system.git

Step 2: Open the Project Folder Open the extracted or cloned folder in VS Code or any Python IDE. Make sure the manage.py file is visible inside the folder.

Step 3: Create a Virtual Environment Type the following command: python -m venv venv Then activate it by typing: venv\Scripts\activate (for Windows) or source venv/bin/activate (for macOS/Linux)

Step 4: Install Required Packages Install Django by typing: pip install django

Step 5: Apply Migrations Run the following commands to set up the database: python manage.py makemigrations and python manage.py migrate

Step 6: Run the Development Server Start the local web server using: python manage.py runserver If successful, it will show: Starting development server at http://127.0.0.1:8000/ Open that link in your browser to view the project.

Step 7: Create an Admin Account (Optional) To access the admin panel, type: python manage.py createsuperuser Then open: http://127.0.0.1:8000/admin and log in using your admin credentials.

Step 8: Explore the Project Now your Library Management System is running successfully. You can log in, add books, issue or return them, and explore all features.

-> Future Scope

Development of a mobile application
Adding email/SMS notifications for due dates
Integration of QR code-based book tracking
