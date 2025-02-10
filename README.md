# Stock Price Prediction Using LSTM

## Description
This project uses Long Short-Term Memory (LSTM) models to predict stock prices based on historical data. The goal is to forecast the closing price of a given stock for the next 30 days. The project fetches stock data using the yfinance library, preprocesses it, and applies deep learning techniques to generate accurate predictions.

## Technologies and Libraries Used
- **Python**: The programming language used.
- **TensorFlow/Keras**: The deep learning framework for implementing the LSTM model.
- **yfinance**: To fetch stock data from Yahoo Finance.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: To visualize the stock price predictions.
- **NumPy**: For numerical operations.
- **scikit-learn**: For data scaling or other machine learning utilities.

## Installation and Running the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/krishnaathreyas/Stock-Price-Prediction.git
    cd Stock-Price-Prediction
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the stock prediction script:
    ```bash
    python stock_predictor.py
    ```

## Prerequisites
- Python version 3.6 or higher.
- Required libraries are listed in the `requirements.txt` file.
- Ensure you have an active internet connection to fetch stock data from Yahoo Finance using yfinance.

## Usage Example
Here’s an example to predict the stock price for NVIDIA (NVDA) for the next 30 days:
1. Clone the repo and install dependencies.
2. Run the stock prediction script:
    ```bash
    python stock_predictor.py
    ```

## Contributors
- Krishna Athreyas
