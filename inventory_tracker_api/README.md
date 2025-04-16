# Inventory Tracker API

## Description

A simple CRUD API for managing suppliers and products in an inventory system using FastAPI and MySQL.

## Setup Instructions

1. Clone the repository.
2. Create a virtual environment and activate it.
3. Install dependencies:
pip install -r requirements.txt

4. Update the database URL in `database.py`.
5. Run the application:
   uvicorn app.main:app --reload

📦 Setup Instructions
1. Install Dependencies
Create a virtual environment and install the required packages:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install fastapi uvicorn sqlalchemy mysql-connector-python
2. Database Configuration
Ensure you have a MySQL database named inventory_db. Update the database connection URL in database.py accordingly.

🚀 Running the Application
Start the FastAPI server using Uvicorn:

bash
Copy
Edit
uvicorn app.main:app --reload
Access the interactive API documentation at http://127.0.0.1:8000/docs.

🧪 Testing the API
Use tools like Postman or curl to test the endpoints:

Create Supplier: POST /suppliers/

Get Suppliers: GET /suppliers/

Create Product: POST /products/

Get Products: GET /products/


