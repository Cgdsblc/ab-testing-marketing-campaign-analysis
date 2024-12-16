# 📊 A/B Testing Project - Marketing Campaign Analysis

## Project Overview

This project analyzes the effectiveness of two marketing strategies: advertisements (ad group) versus public service announcements (psa group). Using an A/B testing dataset, we aim to determine which strategy leads to higher conversion rates through statistical analysis and data visualization.

## ❓ Problem Statement

The marketing team wants to identify the more effective campaign type between ad and psa groups to optimize conversions while reducing marketing costs.

## 🎯 Objective

Evaluate the impact of the ad and psa strategies on user conversions and engagement to optimize marketing campaigns.

### Key Results:

	1.	Improve understanding of user behavior and engagement metrics.
	2.	Identify statistically significant differences in conversion rates between the groups.
	3.	Provide actionable insights for campaign strategy adjustments.

## 📝 Hypothesis

	•	Null Hypothesis (H₀): There is no difference in conversion rates between the ad and psa groups.
	•	Alternative Hypothesis (Hₐ): The ad group has a higher conversion rate than the psa group.

## 📊 Dataset

The dataset was sourced from Kaggle, and it contains the following columns:

### Source: [Marketing A/B Testing Dataset on Kaggle](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing?resource=download)
### Columns:
	•	user id - Unique user identifier
	•	test group - Campaign type (ad or psa)
	•	converted - Whether the user converted (True/False)
	•	total ads - Number of ads viewed
	•	most ads day - Day of the week when the most ads were seen
	•	most ads hour - Hour of the day when the most ads were seen

## Key Performance Indicators (KPIs)

	1.	Conversion Rate: Percentage of users who converted in each group.
	2.	Ads Viewed per User: Average number of ads viewed by users in each group.
	3.	Statistical Significance (P-value): P-value from the Chi-Square Test to determine if differences in conversion rates are statistically significant.

## 🧑‍💻 Data Preparation & Analysis Steps

	1.	Data Preparation:
	•	Processed and cleaned the dataset for analysis.
	•	Converted converted column from boolean to binary for statistical tests.
	2.	Exploratory Data Analysis (EDA):
	•	Examined conversion rates and engagement metrics for both groups.
	•	Visualized distributions and trends using bar plots, box plots, and heatmaps.
	3.	Statistical Testing:
	•	Conducted a Chi-Square Test to evaluate the statistical significance of differences in conversion rates.
	4.	Visualization:
	•	Bar plots for conversion rates by test group.
	•	Box plots for total ads viewed by test group.
	•	Heatmaps for ads viewed by hour and test group.

## 📈 Key Findings

### Metrics:

	1.	Conversion Rate:
	•	Ad Group: 3.12%
	•	PSA Group: 2.65%
	2.	Ads Viewed per User (Engagement Metric):
	•	Ad Group: 180.64 ads/user
	•	PSA Group: 136.35 ads/user
	3.	Statistical Significance (P-value):
	•	Chi-Square Test P-value: 0.0158 (statistically significant)

### 🔍 Interpretations:

	•	The ad group performed significantly better than the psa group in terms of both conversion rate and engagement (ads viewed per user).
	•	The statistical test confirmed that the differences between the groups are not due to random chance.

### Recommendations

	1.	Allocate more resources to ad campaigns, as they yield higher conversions and user engagement.
	2.	Further analyze the timing and content of ads to optimize their performance.
	3.	Conduct follow-up tests to refine ad strategies and explore additional variations.

### Limitations

	•	The dataset may not represent all demographics, as it is limited to users included in the test.
	•	External factors (e.g., time of year, market trends) may influence results.

## 📂 Project Structure

/ab-testing-project
  |-- data
      |-- marketing_AB.csv (not uploaded, link to Kaggle)
  |-- notebooks
      |-- AB_Testing_Project.ipynb
  |-- visuals
      |-- bar_plot_conversion.png
      |-- box_plot_ads_viewed.png
      |-- chi_square_heatmap.png
  |-- README.md

## Tools Used

	•	Programming: Python (pandas, numpy, seaborn, matplotlib, scipy)
	•	Statistical Test: Chi-Square Test
