**Expense Management System**

A full-stack Expense Management System built with a Streamlit frontend and a FastAPI backend to help users track and manage their expenses efficiently.

🧠 Overview

This project lets you record, view, and analyze personal expenses through an interactive web app powered by Streamlit, while FastAPI handles backend APIs and logic. It is ideal for learning modern Python web development and building practical financial tools.

🚀 Features

✅ Add new expense entries
✅ View a list of your expenses
✅ Categorize and filter expenses
✅ Fast API backend for data handling
✅ Simple and user-friendly UI with Streamlit

🧱 Project Structure
/
├── frontend/         # Streamlit app code
├── backend/          # FastAPI server source
├── tests/            # Test cases
├── requirements.txt  # Python dependencies
├── LICENSE           # Apache-2.0 License
└── README.md
``` :contentReference[oaicite:2]{index=2}

## ⚙️ Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/student392/Expense-Managemnt-System.git
   cd Expense-Managemnt-System


Install dependencies

pip install -r requirements.txt

▶️ Run the Backend

Start the FastAPI server:

uvicorn backend.server:app --reload


This will run the API at http://localhost:8000.

▶️ Run the Frontend

In a new terminal:

streamlit run frontend/app.py


The Streamlit UI will open in your browser.

🧪 Testing

Run all tests using:

pytest

📄 License

This project is licensed under the Apache-2.0 License — see the LICENSE file for details.
