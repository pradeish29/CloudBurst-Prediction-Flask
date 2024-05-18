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

- **app.py**: Main application file that contains the Flask routes and logic for fetching weather data and making predictions.
- **model/random_forest_model.pkl**: Serialized pre-trained Random Forest model.
- **static/css/styles.css**: Stylesheet for the HTML pages.
- **templates/index.html**: Main HTML page to display the weather data and prediction results.
- **README.md**: This file, providing an overview and setup instructions.
- **requirements.txt**: List of required Python packages.
- **config.py**: Configuration file for API keys and other settings.

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/cloud_burst_prediction.git
    cd cloud_burst_prediction
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```
    
### Running the Application

1. **Run the Flask app**:
    ```bash
    python app.py
    ```

2. **Access the application**:
   - Open your web browser and navigate to `http://127.0.0.1:5000`.

## Usage

1. Upon accessing the web application, it will automatically fetch the current weather data using the configured weather API.
2. The fetched data will be used by the pre-trained Random Forest model to predict the likelihood of a cloud burst.
3. The prediction results and current weather conditions will be displayed on the main page.

## Contributing
Feel free to submit issues or pull requests if you have suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

By following these instructions, you should be able to set up and run the cloud burst prediction web application locally. Enjoy predicting cloud bursts with real-time weather data!
