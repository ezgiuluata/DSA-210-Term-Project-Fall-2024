# DSA-210-Term-Project-Fall-2024
Welcome to the GitHub repository for my term project in the DSA210 course. This project will explore the relationship between the daily TikTok screen time and the steps taken during the day.

You can access the presentation of my project via this link: https://docs.google.com/presentation/d/1sTLAdtnx10DQ5uD7IRb9uaBwg07HBjOZ3z0aZHBtikk/edit?usp=sharing 

# Motivation
I am Ezgi Uluata (32671), and for my term project for the DSA210 course, I will analyze how my daily TikTok screen time impacts the number of steps I take during a day. Watching TikTok has become a regular part of my routine, and this project is an opportunity to understand how this habit might be influencing my physical activity levels, specifically the steps I take. By analyzing this relationship, I hope to understand how TikTok screen time might influence personal health and well-being, specifically through its impact on the daily number of steps I take.
# Hypothesis
I believe that on days when I spend more time watching TikTok videos and thus, having higher screen time, I tend to walk less, resulting in fewer steps taken throughout the day. 
# Data Sources
* TikTok Screen Time Data
  * I extracted my data directly from TikTok, which provided me with a browsing history file in .txt format. This file includes details such as the date, the exact time I watched each video, and the specific videos I viewed. 
* Daily Steps taken From the iPhone Health Application
  * Provides the number of steps taken during the day with the exact date.
# Objectives
1. Quantify and analyze tikTok screen time
   * Measure daily TikTok screen time accurately to establish a reliable dataset.
3. Track physical activity, more specifically daily steps taken
   * Collect and record the daily number of steps taken as an indicator of physical activity.
4. Evaluate consistency
   * Determine if the relationship between screen time and steps is consistent or varies based on external factors like weekdays vs. weekends.
5. Correlate TikTok screen time and steps taken during the day
   * Investigate the correlation between TikTok screen time and the number of steps taken to determine if higher screen time correlates with reduced physical activity.
6. Suggest Behavioral Adjustments
   * If necessary, provide recommendations for balancing screen time with physical activity to maintain a healthier lifestyle.
# Methodology

1. Exploratory Data Analysis (EDA)
   * Daily TikTok Usage Patterns: Visualize TikTok screen time trends across different days to identify usage patterns.
   * Physical Activity Trends: Plot the distribution of daily steps to understand activity levels.
   * Initial Relationship Insights: Analyze scatter plots to observe preliminary relationships between TikTok screen time and steps taken.
   * Identify Outliers: Detect and investigate days with unusually high or low screen time or step counts.

2. Statistical Analysis
   * Correlation Analysis: Measure the strength of the relationship between TikTok screen time and the number of steps taken using Pearson or Spearman correlation coefficients.
   * Daily Patterns: Assess variations in step counts based on different ranges of TikTok usage (e.g., low, moderate, and high screen time).
   * Weekday vs. Weekend Comparison: Compare correlations between screen time and steps on weekdays versus weekends to identify behavioral differences.

3. Predictive Modeling
   * Regression Analysis: Build a regression model to predict daily step counts based on TikTok screen time as the primary predictor.
   * Threshold Classification: Classify days into "active" (higher steps) and "inactive" (lower steps) categories based on screen time thresholds.
     
4. Visualization
   * Screen Time Trends: Create line graphs to display daily TikTok usage over time.
   * Step Count Distribution: Generate histograms or density plots to visualize daily step counts.
   * Correlation Insights: Use scatter plots and heatmaps to depict relationships between screen time and physical activity.
