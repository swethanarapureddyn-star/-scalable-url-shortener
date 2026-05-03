# Scalable URL Shortener Service 🔗

A backend URL shortening service built using FastAPI and SQLAlchemy.

## Features
- Shorten long URLs
- Redirect to original URL
- Unique short code generation
- REST API architecture

## Tech Stack
- Python
- FastAPI
- SQLite
- SQLAlchemy

## Run Locally
pip install -r requirements.txt
uvicorn app.main:app --reload

## API Endpoints
POST /shorten  
GET /{short_code}

## Future Improvements
- Redis caching
- Rate limiting
- Analytics
- Deployment on AWS
