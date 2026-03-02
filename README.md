# AI-ML-Internship-Tasks
This repository contains the tasks completed as part of my AI/ML Internship.
Each task demonstrates practical implementation of machine learning concepts including data handling, model building, evaluation, and visualization.

🩺 Task 1: General Health Assistant Chatbot
🎯 Objective:To build a conversational chatbot that can answer general health-related questions using a language model API.

📌 Features
      Accepts user input in terminal
      Provides medical guidance for common symptoms
      Handles API errors (quota issues, version errors)
      Exit option for ending conversation

🛠 Technologies Used
      Python
      OpenAI API
      Exception handling

🔍 Key Learning
      Working with APIs
      Handling API version errors
      Managing rate limits and quota issues
      Building interactive CLI applications

📈 Task 2: Stock Price Prediction (Short-Term)
🎯 Objective:To predict the next day's closing price of a stock using historical market data.

📊 Dataset
      Source: Yahoo Finance
      Library Used: yfinance
      Stock Selected: Apple (AAPL)
      Time Period: 2020 – 2024

🧠 Features Used
      Open
      High
      Low
      Volume
🎯 Target Variable:Next Day Closing Price

🤖 Model Applied:Linear Regression

⚙️ Methodology
      Downloaded historical stock data using yfinance
      Created target column using shift(-1)
      Split dataset using time-based 80-20 split
      Trained Linear Regression model

Evaluated using:
      MAE (Mean Absolute Error)
      RMSE (Root Mean Squared Error)
      Plotted Actual vs Predicted prices

🔍 Key Findings
      Model captures overall trend but struggles with volatility.
      Stock prices are noisy and difficult to predict precisely.
      Time-series split is important to prevent data leakage.

🏠 Task 3: House Price Prediction
🎯 Objective: To predict house prices using property features such as square footage, number of bedrooms, and location.

📊 Dataset Used
Source: Kaggle – House Price Prediction Dataset

🧠 Features Used
      Square Footage
      Number of Bedrooms
      Number of Bathrooms
      Location
      Other relevant property features

🤖 Model Applied: Linear Regression

🛠 Tools & Libraries Used
      Python
      Pandas
      NumPy
      Matplotlib
      Scikit-learn
      yfinance
      OpenAI API

📌 Overall Learning Outcomes
    Through these tasks, I gained hands-on experience in:
    Data collection using APIs
    Data preprocessing
    Regression modeling
    Model evaluation techniques
    Visualization of predictions
    Error handling in API-based applications
    Structuring and documenting ML projects

👩‍💻 Author

Irza Malik
AI/ML Internship Project Submission
Year: 2026
