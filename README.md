# Task 1 - Iris Dataset Exploration

## Goal

- Load, inspect, and visualize the Iris dataset.
- Practice basic data analysis and visualization.

## Steps

1. **Load Dataset**  
   - Used `pandas` and `seaborn` to load data.

2. **Inspect Data**  
   - Checked shape, columns, first few rows.
   - Used `.info()` and `.describe()` for summaries.

3. **Visualize Data**  
   - Scatter plots for feature relationships.
   - Histograms for feature distributions.
   - Box plots to check for outliers.

## Tools

- Python
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

## How to Run

- Install libraries:

```bash
pip install pandas seaborn matplotlib

# Task 2 - Predict Future Stock Prices

## Objective

Use historical stock data to predict the next day's closing price using regression models.

## Dataset

- Stock market data fetched from Yahoo Finance using `yfinance` library.
- Example stocks: Apple (AAPL), Tesla (TSLA), etc.

## Steps

1. **Data Collection**
   - Fetched historical stock data using `yfinance`.

2. **Data Preparation**
   - Used features: Open, High, Low, Volume.
   - Target: Next day's Close price.

3. **Modeling**
   - Trained Linear Regression and Random Forest models.

4. **Evaluation**
   - Compared actual vs predicted closing prices.
   - Calculated Mean Squared Error and R² score.
   - Visualized predictions using plots.

## Tools Used

- Python
- pandas
- yfinance
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## How to Run

1. Install required libraries:

```bash
pip install yfinance pandas scikit-learn matplotlib seaborn


