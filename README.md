# Statistical Analysis of Bitcoin Dataset

This project involves performing an exploratory data analysis (EDA) and statistical analysis on historical Bitcoin data. The analysis includes graphical representations, descriptive statistics, distribution fitting, correlation and regression analysis, and hypothesis testing.

## Dataset Overview

The dataset used in this project contains historical Bitcoin data, specifically the Bitcoin-to-USD exchange rates at a minute-level granularity. The dataset includes the following columns:

- `Timestamp`: The UNIX timestamp representing the date and time.
- `Open`: The opening price of Bitcoin at that minute.
- `High`: The highest price of Bitcoin during that minute.
- `Low`: The lowest price of Bitcoin during that minute.
- `Close`: The closing price of Bitcoin at that minute.
- `Volume`: The trading volume of Bitcoin during that minute.
- `datetime`: The readable date-time format corresponding to the UNIX timestamp.

You can download the dataset from [Kaggle's Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data).


## 📊 Analysis Performed

1. **Data Exploration & Preprocessing**
   - Loaded and explored Bitcoin historical data.
   - Handled missing values by imputing or removing them.
   - Converted UNIX timestamps into readable datetime format.
   - Dropped irrelevant columns (e.g., Timestamp) for numeric/statistical analysis.

2. **Descriptive Statistics**
   - Measures of central tendency: Mean, Median, Mode
   - Measures of dispersion: Range, Standard Deviation, Variance, IQR
   - Measures of Position: Skewness, Kurtosis

3. **Inferential Statistics**
   - **Central Limit Theorem (CLT)**: Simulated sample means from the dataset to demonstrate the CLT.
   - **Confidence Interval**: Calculated 95% confidence intervals for Bitcoin's closing price.
   - **Hypothesis Testing**: Performed a T-test to compare the mean closing price with a hypothetical population mean.
   - **Z-Score**: Calculated Z-scores for the closing price values.

4. **Visualization**
   - **Time Series Plot**: Analyzed Bitcoin's price trends over time.
   - **Boxplot**: Visualized the distribution of Bitcoin's closing prices.
   - **Histogram**: Examined the distribution of Bitcoin's closing prices.
   - **Density Plot**: Estimated the probability density of the closing price.
   - **Correlation Heatmap**: Analyzed the correlation between various numerical columns.
   - **Scatterplot**: Examined the relationship between Open and Close prices.
   
5. **Time-Based Analysis**
   - **Monthly Average**: Resampled the dataset to calculate the average closing price for each month.
   - **Moving Average**: Calculated and visualized a 30-day moving average of Bitcoin's closing price.

## 🛠️ Technologies Used
- Python
  - Pandas for data manipulation
  - NumPy for numerical computations
  - Matplotlib & Seaborn for visualization
  - SciPy for statistical analysis


