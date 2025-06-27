# Trader-Sentiment-Analysis
![jupyter-notebook](https://github.com/user-attachments/assets/2ca75053-14b0-4b0c-8cbe-f6cf9cbefebe)
![made-with-python](https://github.com/user-attachments/assets/b3620304-6fd8-442d-be59-eac409607635)
![matplotlib](https://github.com/user-attachments/assets/bed11ff9-4a90-42bd-b5ff-7fbb2556e32b)
![numpy](https://github.com/user-attachments/assets/d8f1f964-e021-4f6d-8ad3-bbe900fad431)
![pandas](https://github.com/user-attachments/assets/7e74df6b-f973-4170-aa62-4a3a139716f6)
![plotly](https://github.com/user-attachments/assets/451d6d34-9739-47b2-b472-c6ab410664c6)
![seaborn](https://github.com/user-attachments/assets/d5936529-2c5d-409b-bf96-2a59d3dcac80)


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
