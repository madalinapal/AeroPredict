# AeroPredict

## Overview

The **AeroPredict** project is a web application designed to help users analyze and predict flight ticket prices dynamically. By collecting real-time data through web scraping and applying machine learning algorithms, the application provides insights and predictions to assist users in making cost-effective travel decisions.

## Features

- **Input Travel Details:** Users can input their travel information, including:
  - Origin and destination
  - Travel dates
- **Real-Time Price Scanning:** The application scrapes flight price data from Google Flights
- **Price Report:**
  - Predictions for future price trends

## Technology Stack

- **Frontend:**
  - HTML, CSS, JavaScript
  - Designed for intuitive user experience
- **Backend:**
  - Python
  - Web scraping with libraries like BeautifulSoup and Selenium
- **Machine Learning:**
  - Algorithms for price trend prediction : Random Forest Regressor
  - Libraries such as scikit-learn and pandas
- **Deployment:**
  - Flask for backend framework
