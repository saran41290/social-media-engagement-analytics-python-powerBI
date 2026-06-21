# 📊 Social Media Engagement Analytics Using Python & Power BI

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-purple?style=for-the-badge&logo=pandas)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

# 📌 Project Overview

This project performs a comprehensive analysis of social media engagement data using Python and Power BI.

The objective is to identify content performance trends, user behavior patterns, audience engagement drivers, sentiment impact, and business insights through data analytics and interactive visualizations.

The project follows a complete analytics workflow:

✅ Data Cleaning  
✅ Data Transformation  
✅ Exploratory Data Analysis (EDA)  
✅ Feature Engineering  
✅ Statistical Analysis  
✅ Data Visualization  
✅ Business Insights Generation  
✅ Interactive Power BI Dashboard

---

# 🎯 Business Problem

Social media platforms generate massive amounts of engagement data every day.

Organizations need to understand:

- Which content performs best
- What drives engagement
- Which audiences interact the most
- How sentiment affects engagement
- When content performs best
- Which regions generate stronger engagement

This project analyzes social media engagement metrics to support data-driven content strategy decisions.

---

# 📂 Dataset Information

Dataset Name:

```text
social_media_engagement_5000.csv
```

Dataset Size:

- Approximately 5,000 records

Dataset Features Include:

- User ID
- Age
- Gender
- Country
- Device Type
- Post Type
- Post Category
- Likes
- Comments
- Shares
- Impressions
- Watch Time
- Followers
- Sentiment
- Verification Status
- Posted Date

---

# 🛠️ Tools & Technologies

## Programming Language

- Python 3.x

## Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Dashboarding

- Microsoft Power BI

## Development Environment

- Google Colab

---

# 🔄 Project Workflow

## Step 1: Data Loading

- Imported dataset using Pandas
- Inspected structure and schema
- Validated column data types

---

## Step 2: Data Cleaning

Performed:

### Missing Value Handling

- Age → Mean Imputation
- Gender → Mode Imputation
- Sentiment → Mode Imputation
- Likes → Group-based Imputation
- Comments → Group-based Imputation
- Shares → Group-based Imputation

### Duplicate Handling

- Identified duplicate records
- Removed duplicates

### Data Type Corrections

- Converted date fields
- Converted categorical columns
- Corrected numerical columns

### Category Standardization

- Gender labels standardized
- Sentiment labels cleaned
- Text values normalized

---

## Step 3: Feature Engineering

Created additional analytical features:

### Engagement Score

```python
engagement_score = likes + comments + shares
```

### Hashtag Count

Extracted hashtag frequency from content.

### Date-Based Features

Created:

- Year
- Month
- Day of Week

---

## Step 4: Exploratory Data Analysis

Performed analysis on:

### Demographics

- Gender Distribution
- Age Distribution

### Content Analysis

- Post Types
- Post Categories

### User Behavior

- Device Types
- Verified Users

### Sentiment Analysis

- Positive
- Negative
- Neutral

---

## Step 5: Statistical Analysis

Calculated:

### Central Tendency

- Mean
- Median
- Mode

### Dispersion

- Standard Deviation
- Variance

### Distribution Metrics

- Percentiles
- Skewness
- Kurtosis

---

## Step 6: Data Visualization

Created visualizations using:

### Matplotlib

- Scatter Plot
- Line Chart
- Bar Chart
- Pie Chart
- Histogram
- Box Plot

### Seaborn

- Count Plot
- Violin Plot
- Pair Plot
- Heatmap
- Swarm Plot

### Plotly

- Interactive Line Chart
- Interactive Scatter Plot
- Bubble Chart

---

# 📈 Key Business Insights

## 1️⃣ Content Performance

### Highest Engagement Post Types

| Post Type | Avg Engagement Rate |
|------------|--------------------|
| Video | 1.12 |
| Text | 1.06 |
| Image | 0.90 |
| Reel | 0.78 |

### Insights

- Video posts achieved the highest engagement rate.
- Text content ranked second.
- Reels were the most frequently published content type but generated the lowest engagement.

---

## 2️⃣ Category Performance

### Average Likes by Category

Top Performing Categories:

1. Food
2. Music
3. Lifestyle

Lowest Performing Category:

- Fashion

### Insights

- Food-related content received the highest audience interaction.
- Fashion content generated comparatively lower engagement.

---

## 3️⃣ Country Performance

### Average Engagement Rate by Country

| Country | Avg Engagement Rate |
|----------|--------------------|
| Brazil | 1.54 |
| Australia | 1.32 |
| France | 1.15 |
| UAE | 1.11 |
| Canada | 0.92 |

### Insights

- Brazil demonstrated the strongest audience engagement.
- Australia and France also showed high engagement levels.
- USA and India recorded comparatively lower engagement rates.

---

## 4️⃣ User Trends

### Verified vs Non-Verified Accounts

| Account Type | Avg Engagement Score |
|--------------|---------------------|
| Non-Verified | 12,645 |
| Verified | 12,309 |

### Insights

- Non-verified accounts slightly outperformed verified accounts.
- Verification status showed limited impact on engagement.

---

## 5️⃣ Behavioral Insights

### Best Day for Impressions

| Day | Avg Impressions |
|------|----------------|
| Tuesday | 51,309 |

### Lowest Day

| Day | Avg Impressions |
|------|----------------|
| Thursday | 48,119 |

### Best Month

| Month | Avg Impressions |
|---------|---------------|
| September | 51,514 |

### Lowest Month

| Month | Avg Impressions |
|---------|---------------|
| June | 48,134 |

### Insights

- Tuesday generated the highest average impressions.
- September was the strongest performing month.
- Thursday and June recorded the lowest impression averages.

---

## 6️⃣ Device Analysis

### Average Engagement Score

| Device | Avg Engagement Score |
|---------|--------------------|
| Desktop | ~12.7K |
| Mobile | ~12.7K |
| Tablet | ~12.5K |

### Insights

- Device type had minimal impact on engagement.
- Engagement patterns were consistent across all device categories.

---

## 7️⃣ Sentiment Analysis

### Average Engagement Score

| Sentiment | Avg Engagement Score |
|------------|--------------------|
| Negative | 12,732 |
| Positive | 12,669 |
| Neutral | 12,446 |

### Insights

- Negative sentiment generated slightly higher engagement.
- Positive sentiment closely followed.
- Neutral content showed the lowest engagement levels.

---

## 8️⃣ Correlation Analysis

### Findings

- Most variables demonstrated weak correlations.
- Likes, comments, shares, watch time, and followers were largely independent.
- Engagement appears to be influenced by multiple factors rather than a single metric.

---

# 📊 Power BI Dashboard

The project includes a fully interactive Power BI dashboard consisting of:

## Executive Dashboard

KPIs:

- Total Posts
- Total Likes
- Total Shares
- Total Comments
- Average Engagement Rate
- Average Engagement Score

---

## Content Performance Dashboard

Visuals:

- Engagement Rate by Post Type
- Country Performance Map
- Sentiment Analysis
- Category Performance

---

## User & Behavioral Dashboard

Visuals:

- Verified vs Non-Verified Analysis
- Device Analysis
- Best Day Analysis
- Best Month Analysis

---

# 🎓 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Data Visualization
- Business Intelligence
- Dashboard Design
- Power BI
- Data Storytelling
- Insight Generation

---

# 🚀 Future Enhancements

- Predictive Engagement Modeling
- Machine Learning Algorithms
- Recommendation Systems
- Real-Time Dashboard Integration
- Automated Reporting Pipelines

---

# 👩‍💼 Author

## Saranya D
### Data Analyst

Passionate about transforming raw data into meaningful insights through analytics, visualization, and business intelligence solutions.

---

# ⭐ Project Outcome

Successfully analyzed approximately 5,000 social media records, developed multiple visualizations, generated business-focused insights, and built an interactive Power BI dashboard to support data-driven decision making for social media performance optimization.
