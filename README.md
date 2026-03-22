# Fast-API-SpeedRide-Rental-Service


A FastAPI-based backend project for managing a car rental service.
This project allows users to browse cars, filter/search/sort them, create rentals, and manage returns.
About the Project
This project is a backend system built using FastAPI as part of my internship training. It simulates a real-world car rental service where users can view cars, book rentals, and manage returns.

The goal of this project was to apply all the concepts learned during the training — including API design, validation, workflows, and data handling.

What This Project Does
View all available cars
Get details of a specific car
Book a car for rental
Calculate rental cost with discounts, insurance, and driver options
Return a rented car
Search, filter, and sort cars
Pagination for large data
View active rentals and rental history
Technologies Used
Python
FastAPI
Uvicorn
Pydantic
Project Structure
project/ │── main.py │── requirements.txt │── README.md │── screenshots/

▶️ How to Run the Project
Install dependencies:
pip install -r requirements.txt

🛠️ Tech Stack
⚡ FastAPI
🐍 Python 3.9+
📦 Pydantic
🚀 Uvicorn
📂 Project Structure
project/
│── main.py        # FastAPI app
│── README.md      # Project documentation
▶️ How to Run
1️⃣ Install dependencies
pip install fastapi uvicorn
2️⃣ Run server
uvicorn main:app --reload
3️⃣ Open in browser
Swagger UI 👉 http://127.0.0.1:8000/docs

Run the server:
uvicorn main:app --reload

Key Features Implemented
GET APIs for retrieving data
POST APIs with Pydantic validation
CRUD operations for cars
Helper functions for business logic
Multi-step workflow (Rent → Return)
Search functionality
Sorting and filtering
Pagination
Combined browsing endpoint
Learning Outcome
Through this project, I learned how to:

Design structured APIs using FastAPI
Handle validations using Pydantic
Implement real-world workflows
Work with filtering, sorting, and pagination
Build a complete backend system from scratch
Dasari Bhanu Prakash

