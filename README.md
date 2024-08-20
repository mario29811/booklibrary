# Book Library Project

## Overview
This project is a full-stack web application for managing a book library. It allows users to view, add, and delete books from a library catalog.

## Structure
The project is divided into two main parts:
1. Backend: A Django REST API
2. Frontend: A React.js application

## Backend (Django)
The backend is built with Django and Django REST Framework. It provides API endpoints for managing book data.

### Features
- RESTful API for CRUD operations on books
- PostgreSQL database for data storage
- Containerized with Docker for easy deployment

### API Endpoints
- GET /api/books/: List all books
- POST /api/books/: Add a new book
- DELETE /api/books/{id}/: Delete a specific book

## Frontend (React)
The frontend is a single-page application built with React.js. It provides a user interface for interacting with the book library.

### Features
- Display list of books
- Add new books to the library
- Delete books from the library
- Responsive design for mobile and desktop

## Getting Started
1. Clone the repository
2. Set up the backend:
   - Navigate to the `backend` directory
   - Install dependencies: `pip install -r requirements.txt`
   - Run migrations: `python manage.py migrate`
   - Start the server: `python manage.py runserver`
3. Set up the frontend:
   - Navigate to the `book-library-frontend` directory
   - Install dependencies: `npm install`
   - Start the React app: `npm start`

## Technologies Used
- Backend: Django, Django REST Framework, PostgreSQL
- Frontend: React.js, Axios for API calls
- Deployment: Docker, AWS (planned)

## Future Enhancements
- User authentication and authorization
- Book search functionality
- Integration with external book APIs for additional information

## Contributor
- Daniel Wang

