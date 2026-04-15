# HNG Stage 1 API

A simple REST API built with FastAPI and deployed on Ubuntu with Nginx.

## Run Locally

pip install fastapi uvicorn
uvicorn main:app --reload

## Endpoints

- `GET /` → `{"message": "API is running"}`
- `GET /health` → `{"message": "healthy"}`
- `GET /me` → `{"name": "Teddy Nwabuisi", "email": "nwabuisiteddy@yahoo.com", "github": "https://github.com/Teddy-adim"}`

## Live URL

http://52.90.156.23