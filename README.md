# Sports-Gear-Recommender-System 

This project delivers real-time personalized sports gear recommendations using machine learning, tailored to individual athletes based on their performance metrics and activity types.

Powered by intelligent algorithms and an interactive UI, it provides dynamic suggestions that enhance athletic performance and shopping experiences.

# ✨ Key Features

- **🎯 Personalized Gear Suggestions**  
  Generates gear recommendations based on user profile, physical attributes, activity type, and historical performance.

- **⚙️ Machine Learning Models**  
  Utilizes classification and ranking models to predict the most suitable gear for various sports and users.

- **🌐 Web-Based Interface**  
  Built with Flask, the system allows users to input data and receive recommendations via a simple and responsive interface.

- **🧠 Data-Driven Predictions**  
  Incorporates user and gear data to improve accuracy using advanced preprocessing and feature extraction techniques.

# Installation Guide

### Prerequisites

1. **🐍 Python 3.8 or higher** – Make sure Python is installed on your system.
2. **📦 Install Dependencies** – Run `pip install -r requirements.txt` to install all required libraries.

# Project Structure

- **`app.py`** → The main application script that runs the Flask server and handles prediction logic.
- **`requirements.txt`** → List of Python packages needed for the app.
- **`models/`** → Directory containing trained ML models.
- **`static/` & `templates/`** → Web assets for the user interface.
- **`data/`** → Sample data used for testing and evaluation.

# Technologies Used

This project is powered by a versatile tech stack:

- **Python** – Core programming language  
- **Scikit-learn** – For training ML models  
- **Pandas & NumPy** – For data manipulation  
- **Flask** – To build the web interface  
- **TensorFlow** – For optional deep learning models  
- **SQLite** – To store user profiles and gear database  
- **HTML/CSS/JavaScript** – For building the UI

# How It Works

- **Input:** Users provide personal and performance details.
- **Processing:** The system processes the input and converts it into model-readable format.
- **Prediction:** A pre-trained ML model predicts and ranks suitable gear.
- **Output:** Recommended gear is presented to the user via a web interface.
