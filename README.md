# Stock-Price-Prediction
This project is a Streamlit web app for predicting stock prices. Users input a stock ID to fetch 20 years of data via yfinance, which is then processed by a Keras model. The app displays historical data and uses a custom function to plot graphs, aiding in stock analysis and prediction.

## Features
- **Stock Price Prediction:** Utilizes a pre-trained machine learning model to predict future stock prices based on historical data.
- **Interactive Web Interface:** Built with Streamlit, the application offers an interactive web interface where users can input stock IDs (e.g., "GOOG" for Google) to view predictions.
- **Historical Data Analysis:** Integrates with the yfinance library to download historical stock data for analysis.
- **Data Visualization:** Uses Matplotlib for generating plots that visualize the stock's closing prices alongside its moving average over a specified period.

## Technologies Used
- **Python:** The core programming language used for developing the application.
- **Streamlit:** An open-source app framework for Machine Learning and Data Science projects, used to create the web interface.
- **Pandas & NumPy:** Used for data manipulation and analysis.
- **Keras:** Utilized for loading the pre-trained machine learning model.
- **Matplotlib:** For plotting and visualizing data.
- **yfinance:** A library that allows for easy access to financial data.

## Getting Started
To run this project locally, you will need to have Python installed on your machine. Follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the application using Streamlit by executing `streamlit run web_stock_price_predictor.py`.
4. The web interface will open in your browser, where you can start by entering a stock ID to view its price prediction and historical data analysis.

## Contributing
Contributions to the project are welcome. Please ensure to follow the project's coding standards and submit your pull requests for review.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

This README provides a comprehensive overview of the project, its features, technologies used, and instructions on how to get started. Adjustments can be made based on the specific details or additional features of your project.
