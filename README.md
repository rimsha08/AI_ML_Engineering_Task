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

- Install libraries


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

1. Install required libraries

# Task 3 - Heart Disease Prediction

## Objective

Predict whether a person is at risk of heart disease using health-related data.

## Dataset

- UCI Heart Disease Dataset (from Kaggle)
- Target: 1 = disease, 0 = no disease

## Steps

1. **Data Cleaning**
   - Checked and handled missing values.

2. **Exploratory Data Analysis**
   - Explored feature distributions and relationships.
   - Plotted correlation heatmap and other EDA visuals.

3. **Modeling**
   - Used Logistic Regression and optionally Decision Tree.
   - Trained using 80-20 train-test split.

4. **Evaluation**
   - Accuracy score
   - Confusion Matrix
   - ROC Curve & AUC score

5. **Feature Importance**
   - Identified key predictors of heart disease.

## Tools Used

- Python
- pandas
- matplotlib, seaborn
- scikit-learn

## How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ronitf/heart-disease-uci).
2. Install dependencies-- pip install pandas matplotlib seaborn scikit-learn

# Task 4 - General Health Query Chatbot (Prompt-Based)

## Objective

Build a chatbot that answers health-related questions using a Large Language Model (LLM) and prompt engineering.

## Tools

- OpenAI GPT-3.5 via API
- Python

## Features

- Friendly and clear responses using prompt engineering
- Built-in safety response for sensitive or medical-risk questions
- Simple function-based chatbot

## Sample Queries

- "What causes a sore throat?"
- "Is paracetamol safe for children?"

## How to Use

1. Install OpenAI-- pip install openai


# Task 6 - House Price Prediction

## Objective

Build a regression model to predict house prices based on property features.

## Dataset

- House price dataset (from Kaggle or similar)
- Features: size, number of bedrooms, location, etc.

## Steps

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical features (e.g., location)
   - Scaled features for linear regression

2. **Modeling**
   - Used Linear Regression and Gradient Boosting
   - Trained using 80-20 train/test split

3. **Evaluation**
   - Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)
   - Plotted actual vs predicted prices

## Tools Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## How to Run

1. Download the dataset from Kaggle.
2. Install dependencies-- pip install pandas numpy scikit-learn matplotlib seaborn




