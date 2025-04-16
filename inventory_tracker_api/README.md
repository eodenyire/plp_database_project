# Inventory Tracker API

## Description

A simple CRUD API for managing suppliers and products in an inventory system using FastAPI and MySQL.

## Setup Instructions

1. Clone the repository.
2. Create a virtual environment and activate it.
3. Install dependencies:<br>
   pip install -r requirements.txt
4. Update the database URL in `database.py`.
5. Run the application:<br>
   uvicorn app.main:app --reload

📦 Setup Instructions<br>
1. Install Dependencies<br>
Create a virtual environment and install the required packages:<br>
python -m venv venv<br>
source venv/bin/activate  # On Windows: venv\Scripts\activate<br>
pip install fastapi uvicorn sqlalchemy mysql-connector-python<br>
2. Database Configuration<br>

Ensure you have a MySQL database named inventory_db. Update the database connection URL in database.py accordingly.<br>

🚀 Running the Application<br>
Start the FastAPI server using Uvicorn:<br>
uvicorn app.main:app --reload<br>
Access the interactive API documentation at http://127.0.0.1:8000/docs.<br>

🧪 Testing the API<br>
Use tools like Postman or curl to test the endpoints:<br>

> Create Supplier: POST /suppliers/<br>
> Get Suppliers: GET /suppliers/<br>
> Create Product: POST /products/<br>
> Get Products: GET /products/<br>


