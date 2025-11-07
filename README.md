# 📊 Social Media Ad Targeting Analysis  

This project focuses on analyzing **social media advertising data** collected from different platforms such as **Facebook** and **Instagram**.  
The goal is to explore **how different ad types, demographics, and interests** are being targeted by advertisers.  

The dataset includes the following columns:  
`['ad_id', 'campaign_id', 'ad_platform', 'ad_type', 'target_gender', 'target_age_group', 'target_interests']`

---

## 🔧 Step 1: Importing Required Libraries  
Libraries like **Pandas**, **Matplotlib**, **Seaborn**, and **Counter** were used for data handling, visualization, and frequency analysis.  
Seaborn’s whitegrid style was applied to keep the visuals clean and readable.  

---

## 📋 Step 2: Basic Dataset Overview  
The dataset’s shape, column names, and data types were inspected.  
Missing values were checked to ensure data quality before performing any analysis.  

---

## 📊 Step 3: Categorical Value Summary  
For columns such as `ad_platform`, `ad_type`, `target_gender`, and `target_age_group`,  
the unique value counts were displayed to understand how data is distributed across categories.

---

## 📈 Step 4: Distribution Visualizations  
Count plots were created for each categorical column to visualize the frequency of different ad categories, platforms, and target groups.  
This helped in identifying which platforms or age groups were most commonly targeted.  

---

## 🔍 Step 5: Cross Feature Relationships  
Cross-tabulations were performed to see how platforms relate to gender, ad type, and age group.  
This provided a deeper look into how different user segments are approached on each platform.  

---

## 🎨 Step 6: Visualizing Cross Relationships  
Bar charts were plotted using **Seaborn’s countplot** to visually represent relationships like:  
- Ad Platform vs Target Gender  
- Ad Platform vs Ad Type  
- Target Age Group vs Gender  

These visuals gave a quick understanding of which audience segments are being focused on by advertisers.  

---

## 💬 Step 7: Interest Analysis  
The `target_interests` column was split into individual keywords to analyze the most frequent interests.  
Using the **Counter** library, the top 10 most common interests were extracted and visualized using a bar chart.  

---

## 🎯 Step 8: Platform-Wise Targeting by Interest  
Specific keyword filters (e.g., “technology”, “fashion”) were applied to check which platforms focused more on these interest categories.  
This helped identify platform-wise advertising trends.  

---

## 🧠 Step 9: Key Insights  
- Facebook and Instagram have noticeable differences in ad distribution.  
- Gender and age targeting vary depending on the platform and ad type.  
- Top 10 user interests reveal which topics attract the most ad attention.  
- Visual analysis supports better understanding of advertiser strategies.  

---

## 👨‍💻 Author  
**Aamir Shahzad**  
Data Scientist | Machine Learning Enthusiast  
GitHub: [https://github.com/aamir5656](https://github.com/aamir5656)
