
#House Price Prediction System

Author:
-Soham Naik

Date:
- 2024-02-18

Version:
-Initial version


This project implements a web-based system for predicting house prices using Django, a high-level Python web framework. The system utilizes various Python libraries including NumPy, Pandas, and Scikit-learn for data manipulation, analysis, and machine learning model development.

Features:
- User Authentication: Users can create accounts, log in, and log out securely.
- Data Input: Users can input features of a house such as area, number of bedrooms, etc.
- Prediction: The system employs a machine learning model trained on historical housing data to predict the price of the house based on the provided features.
- Visualization: The system provides visualizations such as graphs and charts to display insights from the data and predictions.

Dependencies:
- Django: A high-level Python web framework for rapid development and clean design.
- NumPy: A library for numerical computing in Python, used for handling arrays and matrices.
- Pandas: A library providing data structures and data analysis tools, used for data manipulation and analysis.
- Scikit-learn: A machine learning library in Python, used for building predictive models.

Usage:
1. Install Django and required dependencies using pip:
    pip install django numpy pandas scikit-learn

2. Clone the project repository:
    git clone <repository_url>

3. Navigate to the project directory:
    cd House_Price_Prediction_System

4. Run the Django development server:
    python manage.py runserver

5. Access the web application in a browser at http://localhost:8000/

