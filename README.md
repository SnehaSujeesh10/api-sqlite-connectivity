# API SQLite Connectivity

## Project Description
This project demonstrates the integration of FastAPI with an SQLite database to perform CRUD operations on student records.

## Technologies Used
- Python
- FastAPI
- SQLite
- Uvicorn
- Pydantic

## Installation
1. Clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies:

    pip install -r requirements.txt

## Run the Application

    uvicorn main:app --reload

## API Documentation
Open http://127.0.0.1:8000/docs in your browser.

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | / | Home route |
| POST | /students | Create a student |
| GET | /students | Get all students |
| GET | /students/{student_id} | Get a student |
| PUT | /students/{student_id} | Update a student |
| DELETE | /students/{student_id} | Delete a student |

## Database
SQLite stores student records persistently in students.db.

## Author
Sneha Sujeesh
