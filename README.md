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


# 🛠️ Tools & Technology Used
- Jupyter Notebook is used as IDE.
  
- Pandas is used for Data Manipulation & Pre-processing.

- For visualization of the plots, Matplotlib, Seaborn, Plotly are used.

- GitHub is used as version control system.
![tools_used](https://github.com/user-attachments/assets/609660c3-b125-458f-9fc2-ba0bc6e88681)

# Some Visuals of the Project
![image](https://github.com/user-attachments/assets/a5a3bfd4-6fbc-41f0-98ca-119924739137)

![image](https://github.com/user-attachments/assets/8340a36f-d5ac-40df-a29b-3b6f223fdb6f)

![image](https://github.com/user-attachments/assets/9d43c898-e8ff-4ef8-aa4d-d10b7141e611)

![image](https://github.com/user-attachments/assets/872c9fd5-3195-4771-aa63-11d65d34040d)

# Conclusions
Objective is to explore the relationship between trader performance and market sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading 
strategies.

Based on the Trader Sentiment Analysis project, several valuable conclusions were drawn. The analysis confirmed a strong relationship between market sentiment—specifically fear and greed—and trader behavior. Traders generally exhibited more cautious actions during periods of fear and more risk-seeking decisions during greed, indicating that sentiment plays a key role in influencing trading patterns. The machine learning model, particularly the Random Forest Classifier, performed well, achieving approximately 76% accuracy with balanced precision and recall scores. Notably, the model was slightly more effective in identifying fear-driven behavior, suggesting that such patterns are more consistent and easier to predict than those influenced by greed.

The study also highlighted that class imbalance in the dataset affected recall scores, which could be improved in future iterations through advanced sampling techniques. Feature importance analysis revealed that factors such as a trader’s past performance, trade volume, and timing (e.g., time of day or day of the week) were significant predictors of sentiment-influenced behavior. This insight provides opportunities for trading platforms to implement real-time risk monitoring, behavioral flagging, or personalized guidance based on sentiment trends.

Furthermore, the fusion of external market sentiment indicators with internal trader activity data significantly improved the predictive power of the model. This approach demonstrates how integrating diverse data sources can enhance decision-making in finance. Overall, the findings support the potential use of such models in real-world applications such as risk management systems, personalized trading suggestions, and sentiment-aware portfolio strategies.
