# FinSight - Cloud-Based Personal Finance Analytics Platform

FinSight is a cloud-based personal finance analytics web application that helps users track income, expenses, budgets, savings, financial health, and spending patterns. The application uses Flask for the web layer, Snowflake for cloud data storage, AWS Lambda for serverless financial calculations and forecasting, and Gemini AI for custom financial assistance.

## Features

- User registration and login
- Secure password validation and authentication
- Add, view, delete, and export financial transactions
- Category-wise budget management
- Dashboard with income, expenses, savings, and savings rate
- Financial health score and cash flow status
- Category-wise spending analysis
- Monthly income and expense trend charts
- Budget warnings and personalized recommendations
- Serverless report generation using AWS Lambda
- Regression-based expense and savings forecasting
- AI finance assistant using Gemini API
- Interactive charts using Chart.js
- Snowflake cloud database integration

## Tech Stack

- Python
- Flask
- Flask-Login
- Flask-SQLAlchemy
- Snowflake
- AWS Lambda
- Boto3
- Gemini API
- HTML
- CSS
- JavaScript
- Chart.js

## Architecture
Frontend: HTML, CSS, JavaScript, Chart.js
        ↓
Backend: Flask
        ↓
Serverless Logic: AWS Lambda
        ↓
Database: Snowflake
        ↓
AI Assistant: Gemini API
