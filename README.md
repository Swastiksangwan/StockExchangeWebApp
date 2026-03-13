# Stock Exchange Web Application

A full-stack web application that simulates a basic stock trading platform.  
Users can buy and sell stocks, track their portfolio, and visualize market data through charts.



## Features

- Buy and sell stocks
- Portfolio management
- Transaction tracking
- Interactive stock charts
- Real-time updates of stock data
- Simple and responsive user interface



## Tech Stack

### Backend
- Java
- Custom Web Server
- REST-style API handling

### Frontend
- HTML
- CSS
- JavaScript

### Visualization
- Chart.js (for stock graphs)



## Project Structure
StockExchangeWebApp
│
├── backend
│   │
│   ├── src
│   │   ├── models
│   │   │   ├── Account.java
│   │   │   ├── StockExchange.java
│   │   │   └── Trade.java
│   │   │
│   │   └── server
│   │       ├── WebServer.java
│   │       ├── BuyHandler.java
│   │       ├── SellHandler.java
│   │       ├── PortfolioHandler.java
│   │       └── Util.java
│   │
│   └── out
│       └── compiled class files
│
├── frontend
│   │
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── charts.js
│
├── .gitignore
└── README.md



## How to Run the Project

### 1. Clone the repository

git clone https://github.com/Swastiksangwan/StockExchangeWebApp.git

### 2. Navigate to the project folder

cd StockExchangeWebApp

### 3. Compile the backend

Compile all Java files inside the backend/src directory.

### 4. Start the server

Run the WebServer.java file to start the backend service.

### 5. Open the frontend

Open the following file in your browser:

frontend/index.html



## Author

Swastik Sangwan  
B.Tech Computer Science  
Jaypee Institute of Information Technology

GitHub: https://github.com/Swastiksangwan
