📊 ConnectaTel Customer Analysis
🚀 Overview

This project performs an Exploratory Data Analysis (EDA) on ConnectaTel users to identify usage patterns, segment customers, and generate actionable business insights.

Key variables such as age, number of messages, calls, and call duration are analyzed to better understand user behavior.

🎯 Objectives
Clean and validate data quality
Analyze customer usage behavior
Segment users by age and activity level
Identify consumption patterns and outliers
Provide strategic business recommendations
🧹 Data Cleaning

During the analysis, several data quality issues were identified and addressed:

Invalid values (sentinels such as -999 and "?")
Out-of-range dates (future years)
Missing values
Structurally missing data

These steps ensured a reliable dataset for further analysis.

📊 Exploratory Data Analysis

The analysis included:

Descriptive statistics
Distribution analysis (histograms)
Outlier detection (boxplots)
User behavior analysis
👥 Customer Segmentation
🔹 By Age
Young: < 30 years
Adult: 30–59 years
Senior: 60+ years

👉 The adult segment represents the most active user group.

🔹 By Usage Level
Low usage: < 5 interactions
Medium usage: 5–9
High usage: ≥ 10

👉 Most users fall into the medium usage category, but high-usage users generate greater value.

🔍 Key Insights
Most users show moderate usage behavior
A group of heavy users with high call minutes was identified
Outliers represent high-value customers, not errors
No strong relationship between age and plan type was observed
💡 Recommendations
🎯 Improve retention strategies for high-usage users (especially premium)
📈 Develop upselling strategies for medium-usage users
📣 Implement age-targeted marketing campaigns
💰 Design tailored plans for heavy users
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
📁 Project Structure
├── data/
├── notebooks/
├── README.md
📌 Conclusion

This analysis highlights key business opportunities through customer segmentation and usage patterns, enabling data-driven decision-making.

👨‍💻 Author

Data analysis project developed as part of a data analytics learning journey 📊
