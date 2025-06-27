# Trader-Sentiment-Analysis
This project analyzes how trader sentiment (fear or greed) influences trading behavior using a combination of market sentiment data and historical trader data. The objective is to build a classification model that can predict trader sentiment and explore how it affects trading outcomes.


# 📌 Datasets Used
Bitcoin Market Sentiment Dataset - https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Columns: Date, Classification (Fear / Greed)

Historical Trader Dataset - https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Contains trading outcomes, trader IDs, and performance indicators

# 🧠 Methodology
Data Loading & Cleaning
Merged sentiment data with trader performance based on date.

Exploratory Data Analysis (EDA)

Visualized class distribution, trends, and correlations

Checked for missing values and outliers

Feature Engineering

Categorical encoding

Date feature extraction

Sentiment labeling

Modeling

Random Forest Classifier

Performance Metrics: Accuracy, Precision

Results

Accuracy: ~76%

Best performance on classifying traders during Fear sentiment
