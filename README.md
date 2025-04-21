# - Stock Market Analysis & Prediction using Machine Learning
This project focuses on analyzing historical stock price data for multiple tech companies (e.g., Apple, Microsoft, Netflix, Google) and predicting future stock price movements using machine learning techniques like Logistic Regression, Support Vector Machine (SVM), and XGBoost Classifier.

# 🚀 Project Overview
This Jupyter Notebook performs:

Exploratory Data Analysis (EDA)

Feature Engineering

Technical Indicator Calculations

Correlation Analysis

Binary classification: Predicting whether the next day’s closing price will rise or fall

Model training & evaluation

 # 📁 Dataset
The dataset used is a .csv file containing historical stock prices with the following columns:

Date, Open, High, Low, Close, Volume, Company

Ensure the CSV file is named stocks.csv and placed in the root directory or adjust the path in the code.

# 📌 Key Steps
1. Library Imports
Essential libraries for data handling, visualization, and modeling.

2. Data Loading & Overview
Read the dataset, explore shape, structure, and summary statistics.

3. Visualization
Plotting closing prices over time for each company

7-day Moving Average & Volatility trends

Correlation heatmap of closing prices

4. Feature Engineering
open-close: Difference between opening and closing prices

low-high: Difference between low and high prices

is_quarter_end: Flag for quarter-end months

target: Binary value (1 = price up next day, 0 = down)

5. Preprocessing
Standardization using StandardScaler

Train-test split (90%-10%)

6. Model Training
Three ML classifiers are trained:

Logistic Regression

Support Vector Machine (SVM with polynomial kernel)

XGBoost Classifier

7. Evaluation
ROC-AUC scores for training and testing

Confusion matrix for model performance

🛠️ Requirements
Python ≥ 3.7

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

Install dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
📊 Example Visualization
📉 Time series of stock closing prices

🔁 Moving average and volatility plots

🔥 Heatmap showing inter-company correlations

📍 Future Improvements
Use more features like technical indicators (RSI, MACD)

Predict price movement magnitude (regression)

Add LSTM or deep learning models

Include economic indicators or news sentiment

📂 Project Structure
Copy
Edit
├── stocks.csv
├── stock_analysis.ipynb
├── README.md
└── requirements.txt
🙌 Acknowledgements
Stock data inspired by Yahoo Finance and similar sources

Machine learning models powered by scikit-learn and XGBoost

📬 Contact
Pritam Nath
📧 pritam322@gmail.com
🔗 LinkedIn
