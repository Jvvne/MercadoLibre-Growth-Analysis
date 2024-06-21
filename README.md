
<img width="809" alt="Screenshot 2024-06-20 at 10 35 06 PM" src="https://github.com/Jvvne/MercadoLibre-Growth-Analysis/assets/148028363/b7d664d9-6857-42ad-b43c-fe4399ae9612">

Project Structure
Finding Unusual Patterns in Hourly Google Search Traffic

Analyze search traffic during May 2020.
Visualize and compare traffic to monthly medians.
Identify unusual patterns.
Mining the Search Traffic Data for Seasonality

Group and visualize average hourly traffic by day.
Create a heatmap for daily traffic patterns.
Examine weekly seasonal trends.
Relating the Search Traffic to Stock Price Patterns

Plot stock price data.
Analyze the relationship between search traffic and stock prices.
Create columns for Lagged Search Trends, Stock Volatility, and Hourly Stock Return.
Creating a Time Series Model with Prophet

Set up and estimate a Prophet forecasting model.
Plot forecasts and individual time series components.
Answer key questions about traffic trends.
(Optional) Forecasting Revenue by Using Time Series Models

Apply a Prophet model to historical sales data.
Forecast next quarter's revenue and identify seasonal patterns.
Files
notebook.ipynb: Jupyter notebook with analysis and visualizations.
README.md: This summary file.
search_data.csv: Google Search traffic data.
stock_price_data.csv: Stock price data.
sales_data.csv: Historical sales data.
Findings
Search Traffic: Significant increase during financial results release in May 2020.
Seasonality: Peak search traffic in evenings and during winter holidays.
Stock Price Relationship: Potential predictive relationship between lagged search traffic and stock volatility/returns.
Prophet Model: Near-term forecast shows increased popularity. Peak traffic in evenings, especially on Mondays.
Running the Notebook
Open the Jupyter notebook in Google Colab or any Jupyter environment.
Run the initial setup cells to install dependencies.
Follow the steps in the notebook to perform the analysis.
Review comments and markdown cells for detailed explanations.
Conclusion
Using Google Search traffic data can help predict stock price movements and optimize marketing strategies for MercadoLibre. The Prophet model offers valuable insights into future trends, aiding in data-driven decision-making.
