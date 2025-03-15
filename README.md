# Hotel Booking Application

A modern hotel booking application built with Python, FastAPI for the backend, and Streamlit for the frontend.

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Durga099/Hotel_Booking
cd Hotel_Booking
```

### 2. Create and Activate Virtual Environment

#### For Windows:
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
.\venv\Scripts\activate
```

#### For macOS/Linux:
```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate
```

### 3. Install Dependencies

```bash
# Install all required packages
pip install -r requirements.txt
```

## Running the Application

### 1. Start the Backend Server

```bash
# Navigate to the backend directory
cd backend

# Start the FastAPI server
python main.py
```

The backend server will start running at `http://localhost:9000`

You can access the API documentation at:
- Swagger UI: `http://localhost:9000/docs`
- ReDoc: `http://localhost:9000/redoc`

### 2. Start the Frontend Application

Open a new terminal window, activate the virtual environment again, and then:

```bash
# Navigate to the frontend directory
cd frontend

# Start the Streamlit app
streamlit run app.py
```

The frontend application will automatically open in your default web browser at `http://localhost:8501`

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# Backend Configuration
RAPIDAPI_KEY='YOUR_RAPIDAPI_KEY'
