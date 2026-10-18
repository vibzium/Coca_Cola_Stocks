# Coca-Cola Stock Market Analysis 📈

## About the Project

I created this project to explore how Coca-Cola's stock has performed over time and understand what historical stock data can tell us about market trends, returns, and risk.

Using Python and data analysis techniques, I explored historical prices, compared moving averages, studied daily returns, and built a Random Forest model to experiment with stock price prediction.

This project helped me put my data analytics skills into practice, from working with datasets to creating visualisations and interpreting the results.

## Project Objectives

- Analyse Coca-Cola's historical stock price movements.
- Understand trends using 20-day and 50-day moving averages.
- Calculate daily returns and rolling volatility.
- Explore relationships between stock prices, trading volume, and other features.
- Build a Random Forest regression model to predict closing prices.
- Visualise the findings and communicate meaningful insights.

## Tools & Technologies

- **Python** – Data analysis and modelling
- **Pandas & NumPy** – Data cleaning and manipulation
- **Matplotlib & Seaborn** – Data visualisation
- **Scikit-learn** – Machine learning and model evaluation
- **yfinance** – Downloading historical stock market data
- **Google Colab** – Writing and running Python code
- **Excel & SQL** – Supporting data analysis and querying

## Dataset

The project includes historical Coca-Cola stock data and stock information files.

The dataset contains fields such as:

- Date
- Open, High, Low, and Close prices
- Trading Volume
- Dividends and Stock Splits

The notebook also downloads Coca-Cola stock data using the ticker symbol `KO` for analysis covering 2015–2023.

## What I Worked On

### 1. Data Cleaning

I handled missing values and prepared the stock data for analysis to make it easier to work with.

### 2. Exploratory Data Analysis (EDA)

I explored historical closing prices and created charts to understand how Coca-Cola's stock moved over time.

### 3. Feature Engineering

I calculated additional metrics to get a better understanding of the data:

- 20-day moving average
- 50-day moving average
- Daily percentage returns
- Rolling volatility

### 4. Data Visualisation

I created visualisations to explore:

- Historical closing price trends
- Stock prices compared with moving averages
- Daily returns over time
- Correlations between numerical features
- Actual versus predicted stock prices

### 5. Machine Learning

I used a Random Forest Regressor to experiment with predicting Coca-Cola's closing stock prices.

I evaluated the model using Root Mean Squared Error (RMSE) and compared its predictions with actual values.

## Key Insights

Here are some of the main observations from my analysis:

- Coca-Cola's historical stock price shows a long-term upward trend, with periods of volatility.
- The sharp market movements around March 2020 stand out in the historical price and daily return charts.
- Moving averages help smooth short-term fluctuations and make broader trends easier to identify.
- Opening, high, low, and closing prices are strongly related to one another.
- Trading volume and price movements do not always have a strong direct relationship.
- The Random Forest model provided an opportunity to explore both the potential and the limitations of predicting stock prices from historical data.

## Project Files

```text
Coca-Cola-Stock-Analysis/
│
├── Coca-Cola_stock_history.csv
├── Coca-Cola_stock_info.csv
├── Final coca-cola.ipynb
├── Coca Cola Stock - Live and Updated.pptx
└── README.md
```


## How to Run the Project

You can run this project using Google Colab or a local Python environment.

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the required CSV files or place them in the correct project directory.
4. Install the required Python libraries if they are not already available.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance
```

5. Update the dataset paths in the notebook if necessary.
6. Run the cells in order to reproduce the analysis and visualisations.

## What I Learned

Working on this project gave me practical experience with data cleaning, exploratory data analysis, feature engineering, visualisation, and machine learning.

It also helped me understand that stock prediction is not just about fitting a model. Financial markets are unpredictable, and a model's performance needs to be evaluated carefully before its predictions can be trusted.

## Disclaimer

This project is for educational and analytical purposes only. It is not financial advice, and the model's predictions should not be used as the sole basis for investment decisions.

## Author

**Vaibhav Borkar**

I'm building my skills in data analytics and enjoy working on projects that turn raw data into useful insights.

Thanks for checking out my project! Feel free to explore the files and share any suggestions for improvement.

