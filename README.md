This is a full-stack web application built using Flask that allows users to register, log in, and manage personal notes.
The application demonstrates backend development, authentication, and database integration using MySQL.

Features
User Authentication (Sign up, Login, Logout)
Create, Read, and Delete Notes
Secure session management
Data stored in a relational database
User-specific notes (each user sees only their data)


Tech Stack
Backend: Flask
Database: MySQL
ORM: Flask-SQLAlchemy
Authentication: Flask-Login
Frontend: HTML, CSS, Bootstrap


Database Schema
User Table
id (Primary Key)
email (Unique)
password
first_name
Note Table
id (Primary Key)
data
date
user_id (Foreign Key → User.id)


How It Works
Users register and log in securely
Notes are linked to users using a foreign key relationship
All database operations (insert, fetch, delete) are handled via ORM
SQL queries are generated automatically by Flask-SQLAlchemy

Future Improvements
Edit/update notes feature
Search and filter notes
REST API integration
AI-based note summarization (planned)


Learning Outcomes
Built a full-stack web application
Learned database design and relationships
Implemented authentication and session handling
Worked with ORM instead of raw SQL queries
