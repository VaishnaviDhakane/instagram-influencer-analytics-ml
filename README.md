# 📊 Instagram Influencer Performance Analysis using Python (EDA)

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of top Instagram influencers to understand their performance based on followers, likes, and engagement metrics.  
The analysis provides data-driven insights useful for influencer marketing and brand collaboration decisions.

---

## 🎯 Objectives
- Analyze follower distribution of top Instagram influencers  
- Calculate and study Engagement Rate  
- Identify top-performing influencers based on engagement  
- Understand the relationship between followers and likes  
- Perform insight-driven analysis using EDA techniques  

---

## 🗂 Dataset Information
The dataset contains the following columns:
- Rank  
- Channel_info  
- Influence_score  
- Posts  
- Followers  
- Avg_likes  
- 60_day_eng_rate  
- New_post_avg_like  
- Total_likes  
- Country  

Some values were stored in abbreviated text formats such as `k` (thousands) and `m` (millions), which were converted into numeric values during data cleaning.

---

## 🛠 Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
---

## 🔄 Project Workflow

### 1. Data Loading
- Loaded the dataset using Pandas
- Checked shape, columns, and data types

### 2. Data Cleaning
- Renamed columns for consistency
- Converted string-based numeric values into numbers
- Handled missing values (Country column)

### 3. Feature Engineering
- Created Engagement Rate using:

Engagement Rate (%) =  
(Avg Likes + New Post Avg Likes) / Followers × 100

### 4. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Correlation analysis
- Boxplots for outlier detection
- Distribution analysis

### 5. Influencer Performance Analysis
- Top influencers by followers
- Top influencers by engagement rate
- Comparison of popularity vs engagement

### 6. Data Visualization
- Histogram for followers
- Engagement rate distribution plot
- Scatter plot: Followers vs Engagement Rate
- Bar charts for top influencers

---

## 📈 Key Insights
- High follower count does not always mean high engagement  
- Engagement rate is a better metric than followers alone  
- Some mid-level influencers show very strong engagement  
- Influencer performance varies across countries  

---

## ✅ Conclusion
This project demonstrates how Exploratory Data Analysis (EDA) can be used to extract meaningful insights from social media data.  
It highlights the importance of engagement metrics in evaluating influencer effectiveness.

---
 

---

