# CloudBurst-Prediction-Flask

## Overview
This project is a web application designed to predict cloud bursts using a pre-trained Random Forest model. The application fetches current weather data from a weather API, uses this data to make predictions, and displays the results on a web page rendered with Flask.

## Features
- **Real-time Weather Data**: Fetches current weather data from an external API.
- **Machine Learning Prediction**: Uses a pre-trained Random Forest model to predict the likelihood of a cloud burst.
- **User-Friendly Interface**: Displays predictions and weather data on a clean, responsive HTML page.

## Project Structure

cloud_burst_prediction/
│
├── app.py
├── model/
│   └── random_forest_model.pkl
├── static/
│   └── css/
│       └── styles.css
├── templates/
│   └── index.html
├── README.md
├── requirements.txt
└── config.py
