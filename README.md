# Assignment 13: Real-Time AI Question Generation

This Flask backend project generates IELTS speaking test questions using OpenAI's API.

## Features
- POST `/api/ai-questions`
- Dynamic AI question generation based on category, difficulty, and count
- Error handling
- Environment variables for API key configuration

## How to Run
- Clone the repo
- Setup `.env` using `.env.example`
- Install dependencies: `pip install -r requirements.txt`
- Run the app: `python app.py`
- Test the endpoint using Postman
