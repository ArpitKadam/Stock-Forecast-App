# Stock Forecast App

## Overview
This Stock Forecast App is built using Streamlit and leverages the power of Facebook's Prophet for time series forecasting. It allows users to select a stock, view its historical data, and predict future prices over a customizable period. The app is interactive, offering intuitive visualizations using Plotly.

## Features
- **Select Stocks**: Choose from a wide range of stocks including popular tickers like GOOG, AAPL, MSFT, and more.
- **Data Visualization**: View and interact with historical stock price data.
- **Forecasting**: Predict stock prices for up to four years using Prophet.
- **Components Visualization**: Display the forecast components such as trend, yearly, and weekly seasonality.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ArpitKadam/Stock-Forecast-App.git
    cd Stock-Forecast-App
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv myenv
    source myenv/bin/activate  # On Windows: myenv\Scripts\activate
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**
    ```bash
    streamlit run main.py
    ```

## Requirements
The `requirements.txt` required for this project has already been provided


## Usage

1. **Launch the app**: Run the Streamlit app using the command provided above.
2. **Select a stock**: Use the dropdown to select the stock ticker for prediction.
3. **Adjust the forecast period**: Use the slider to set the number of years for the prediction (1 to 4 years).
4. **View predictions**: Explore the raw data, view historical price trends, and examine the forecasted stock prices.

## Example Output

- **Raw Data**: Displays the last few rows of historical stock data.
- **Historical Data Plot**: An interactive plot of the stock's historical prices with a range slider.
- **Forecast Data**: Displays the forecasted stock prices for the selected period.
- **Forecast Plot**: Visualizes the stock price predictions over the chosen forecast period.
- **Forecast Components**: Shows detailed components of the forecast including trend and seasonality.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request if you would like to contribute any improvements.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
- [Streamlit](https://streamlit.io/)
- [Prophet](https://facebook.github.io/prophet/)
- [yfinance](https://pypi.org/project/yfinance/)
- [Plotly](https://plotly.com/)
