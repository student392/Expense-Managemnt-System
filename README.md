# **Expense Management System**<br>
A full-stack Expense Management System built with a Streamlit frontend and a FastAPI backend to help users track and manage their expenses efficiently.

## **🧠Overview**<br>
This project lets you record, view, and analyze personal expenses through an interactive web app powered by Streamlit, while FastAPI handles backend APIs and logic. It is ideal for learning modern Python web development and building practical financial tools.

## **🚀Features**<br>
✅ Add new expense entries<br>
✅ View a list of your expenses<br>
✅ Categorize and filter expenses<br>
✅ Fast API backend for data handling<br>
✅ Simple and user-friendly UI with Streamlit<br>

## **🧱 Project Structure**<br>
├── frontend/      # Streamlit frontend application<br>
├── backend/       # FastAPI backend server<br>
├── tests/         # Test cases for frontend and backend<br>
├── requirements.txt # Python dependencies<br>
├── README.md      # Project documentation<br>
└── LICENSE        # LicenseApache-2.0 <br>

## **📌 Technologies Used**<br> 
Python<br>
Streamlit<br>
FastAPI<br>
REST APIs<br>
Unit Testing<br>

## **⚙️Installation**<br> 
Install dependencies<br>
pip install -r requirements.txt<br>

## **▶️ Run the Backend**<br> 
Start the FastAPI server:<br>
uvicorn backend.server:app --reload<br>
This will run the API at http://localhost:8000.<br>

## **▶️ Run the Frontend**<br> 
In a new terminal:<br>
streamlit run frontend/app.py<br>
The Streamlit UI will open in your browser.<br>

## **🧪 Testing**<br> 
Run all tests using:<br>
pytest<br>

## **📄 License**<br> 
This project is licensed under the Apache-2.0 License — see the LICENSE file for details.
