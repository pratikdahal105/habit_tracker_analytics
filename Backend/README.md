# Backend - Flask API

This directory contains the Flask REST API server for the habit tracker analytics application.

## Technology Stack

- **Flask** - Python web framework
- **SQLAlchemy** - Database ORM
- **Flask-CORS** - Cross-Origin Resource Sharing
- **Flask-JWT-Extended** - JWT authentication
- **SQLite/PostgreSQL** - Database

## Setup Instructions

1. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:

   ```bash
   # Windows
   venv\Scripts\activate

   # macOS/Linux
   source venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:

   ```bash
   # Create .env file with:
   FLASK_APP=app.py
   FLASK_ENV=development
   SECRET_KEY=your-secret-key
   DATABASE_URL=sqlite:///app.db
   ```

5. Initialize the database:

   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

6. Run the application:
   ```bash
   flask run
   ```

## API Endpoints

- `GET /api/health` - Health check
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/habits` - Get user habits
- `POST /api/habits` - Create new habit
- `PUT /api/habits/<id>` - Update habit
- `DELETE /api/habits/<id>` - Delete habit

## Build Instructions

For production deployment:

````bash
pip install gunicorn
gunicorn -w 4 -b 0.0.0.0:5000 app:app
``` directory will contain the server-side application.

## Technology Stack

TBD

## Setup Instructions

1. TBD
2. TBD
3. TBD

## API Documentation

TBD
````
