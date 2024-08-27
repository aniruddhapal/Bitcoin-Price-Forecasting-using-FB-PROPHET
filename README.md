# Bitcoin-Price-Forecasting-using-FB-PROPHET

**`fbprophet`**, now known as **`prophet`**, is a forecasting tool developed by Facebook's Core Data Science team. It is designed for time series data and is particularly well-suited for cases where the data exhibits strong seasonal patterns and trends. Prophet is known for its simplicity, robustness, and ability to handle missing data and outliers effectively.

## Key Features
- **Automatic Handling of Seasonality**: Prophet automatically detects and models daily, weekly, and yearly seasonality, making it ideal for time series data with regular seasonal effects.
- **Trend Detection**: The model can capture linear or logistic growth trends, allowing it to adjust to changing trends over time.
- **Holiday Effects**: Users can incorporate custom holiday effects to account for special events or anomalies in the data.
- **Robust to Missing Data**: Prophet can handle missing data points without requiring complex imputation methods.
- **Intuitive Parameter Tuning**: It offers a straightforward interface for adjusting model parameters, making it accessible for users with varying levels of expertise.

## Why fbprophet for Bitcoin Closing Price Forecasting?

**1. Handling Seasonality and Trends**
   - Bitcoin prices often exhibit seasonal patterns and trends, influenced by market cycles and external factors. Prophet’s ability to model and adjust for these seasonality components makes it a strong candidate for capturing such patterns in Bitcoin closing prices.

**2. Ease of Use**
   - Prophet is designed to be user-friendly and requires minimal parameter tuning. Its intuitive interface allows you to quickly fit the model and generate forecasts, which is ideal for both exploratory analysis and production forecasting.

**3. Robustness**
   - The tool’s robustness to missing data and outliers is particularly useful in financial time series, where such issues are common. This ensures that the model remains effective even if the dataset has irregularities.

**4. Flexibility**
   - Prophet can easily incorporate holiday effects and special events, which may impact Bitcoin prices. This flexibility can enhance the accuracy of forecasts by accounting for significant market events or news.

**5. Visualization**
   - Prophet provides built-in tools for visualizing forecast components (trend, seasonality, and holidays), which helps in understanding the model's behavior and interpreting the results effectively.

## Summary
**`fbprophet`** is a powerful and user-friendly tool for time series forecasting, making it well-suited for predicting Bitcoin closing prices. Its ability to handle seasonality, trends, and missing data, combined with its ease of use, makes it a strong choice for developing reliable forecasts.
