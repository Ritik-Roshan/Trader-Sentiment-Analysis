# Trader-Sentiment-Analysis
![jupyter-notebook](https://github.com/user-attachments/assets/2ca75053-14b0-4b0c-8cbe-f6cf9cbefebe)

This project analyzes how trader sentiment (fear or greed) influences trading behavior using a combination of market sentiment data and historical trader data. The objective is to build a classification model that can predict trader sentiment and explore how it affects trading outcomes.


# 📌 Datasets Used
Bitcoin Market Sentiment Dataset - https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Columns: Date, Classification (Fear / Greed)

Historical Trader Dataset - https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Contains trading outcomes, trader IDs, and performance indicators

# 🧠 Methodology
**Data Loading & Cleaning**
- Merged sentiment data with trader performance based on date.

**Exploratory Data Analysis (EDA)**
- Visualized class distribution, trends, and correlations
    
- Checked for missing values and outliers

**Feature Engineering**
- Categorical encoding
  
- Date feature extraction
  
- Sentiment labeling

**Modeling**
- Random Forest Classifier

- Performance Metrics: Accuracy, Precision

**Results**
- Accuracy: ~76%

- Best performance on classifying traders during Fear sentiment

**🛠️ Tools & Technology Used**
- Jupyter Notebook is used as IDE.
  
- Pandas is used for Data Manipulation & Pre-processing.

- For visualization of the plots, Matplotlib, Seaborn, Plotly are used.

- GitHub is used as version control system.
![tools_used](https://github.com/user-attachments/assets/609660c3-b125-458f-9fc2-ba0bc6e88681)
