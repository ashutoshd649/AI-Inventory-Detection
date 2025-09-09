# AI Inventory Detection System

🚀 A full-stack project using **YOLOv8**, **FastAPI**, **MongoDB Atlas**, and **TailwindCSS** for AI-powered inventory detection.

## Features
- User authentication (JWT)
- Object detection (YOLOv8)
- Store detection history per user (MongoDB Atlas)
- Upload custom images to dataset
- Responsive frontend with TailwindCSS

## Setup Instructions

### Backend
```bash
pip install -r requirements.txt
uvicorn app:app --reload

Frontend
Open index.html in browser.

Mongo DB atlas for storing user and detection history 
