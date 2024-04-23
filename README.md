# Volatility Change Prediction Using News

This repository contains code for predicting volatility change using news articles. It leverages machine learning techniques to analyze news data and predict the impact on stock market volatility across 11 sectors. The prediction model considers 15 classes of news for more accurate forecasting.

## Libraries Used

The code utilizes several libraries and frameworks to perform various tasks:
- `numpy`: For numerical computations and array operations.
- `pandas`: For data manipulation and analysis.
- `tensorflow`: For building and training machine learning models, specifically the LSTM model for news classification.
- `scikit-learn`: For machine learning algorithms and tools, used for preprocessing and model evaluation.
- `matplotlib` and `seaborn`: For data visualization and plotting graphs to analyze trends and correlations.
- `yahoo_fin`: For extracting historical stock market data from Yahoo Finance.
- `requests` and `beautifulsoup4`: For web scraping news data from the Finviz website.
## Dependencies

Before running this code, ensure you have the following dependencies:
- `Classification_news`: This module is used for classifying news articles into different categories, it is LSTM model trined on news dataset. Make sure to install and run before running the main code.
- `Correlation`: This module calculates the correlation between news categories and stock market sector. Install and configure it properly to ensure accurate predictions.

## Sectors and Classes

The code considers data from 11 sectors of the stock market and 15 classes of news for prediction. These sectors and classes are crucial for accurate forecasting and analysis.

## Usage

1. **Install Dependencies**: Make sure all the required dependencies are installed and configured correctly.

2. **Prepare Data**: The news data for the stock is obtained by Finviz website and the actual historical data is extracted from yahoo finance.

3. **Run Classification_news**: Execute the `Classification_news` module to classify news articles into different categories. This step is crucial for accurate prediction.

4. **Run Correlation**: Run the `Correlation` module to calculate the correlation between news events and stock market volatility. This step provides insights into the relationship between news and market fluctuations.

5. **Run Main Code**: Finally, run the main code for volatility prediction using news. Ensure that the data inputs are correctly provided and processed for accurate forecasting.

## Prediction of Volatility Change 

The main focus of this code is to predict the change in stock market volatility based on news events. The prediction model considers various factors such as news sentiment, sector-specific news, and historical volatility trends to make accurate forecasts.

## Application

This code can be applicalbe to know how the news will influence the stock price, and we could have an upper edge on the market and put sell stop or buy stop, with regards to the movement of the price.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.


