# Income Expense Tracker

![GitHub stars](https://img.shields.io/github/stars/Synghutkarsh19/Income_Expense?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/Synghutkarsh19/Income_Expense?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Synghutkarsh19/Income_Expense?style=flat-square)
![GitHub license](https://img.shields.io/github/license/Synghutkarsh19/Income_Expense?style=flat-square)

## Overview

Income Expense Tracker is a simple web application to help users track their income and expenses. It provides a user-friendly interface for managing financial transactions, categorizing them, and generating insights into spending habits.

## Features

- **Expense Tracking:** Record your daily expenses and income effortlessly.
- **Categories:** Categorize your transactions for better financial analysis.
- **Insights:** Visualize your spending patterns with interactive charts and graphs.
- **Responsive Design:** Access the application from various devices with ease.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Synghutkarsh19/Income_Expense.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Income_Expense
   ```
3. Navigate to the backend:

   ```bash
   cd backend
   ```
   1. Initialize the project backend and set entry point as "app.js":

      ```bash
      npm init
      ```
   2. Install required packages:
      
      ```bash
      npm install express mongoose cors nodemon dotenv
      ```
   3. Create database using MongoDB Atlas and put the connection url in the ".env" file.
   4. In packahe.json -> scripts -> "start": "nodemon app.js"
   5. Run backend:

      ```bash
      npm start
      ```
4. Navigate to the frontend:
   ```bash
   cd frontend
   ```
   1. Install required packages:
      ```bash
      npm install axios chart.js moment react-chartjs-2 styled-components
      ```
   2. Run frontend:
      ```bash
      npm start
      ```
