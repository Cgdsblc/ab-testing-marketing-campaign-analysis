📊 A/B Testing Project - Marketing Campaign Analysis

📝 Project Overview

This project analyzes the effectiveness of two marketing strategies: advertisements (ad group) versus public service announcements (psa group). Using an A/B testing dataset, we aim to determine which strategy leads to higher conversion rates through statistical analysis and data visualization.

❓ Problem Statement

The marketing team wants to identify the more effective campaign type between ad and psa groups to optimize conversions while reducing marketing costs.

🎯 Hypothesis

	•	Null Hypothesis (H₀): There is no difference in conversion rates between the ad and psa groups.
	•	Alternative Hypothesis (Hₐ): The ad group has a higher conversion rate than the psa group.

📊 Dataset

	•	Source: Marketing A/B Testing Dataset on Kaggle
	•	Columns:
	•	user id - Unique user identifier
	•	test group - Campaign type (ad or psa)
	•	converted - Whether the user converted (True/False)
	•	total ads - Number of ads viewed
	•	most ads day - Day of the week when the most ads were seen
	•	most ads hour - Hour of the day when the most ads were seen

🧑‍💻 Data Preparation & Analysis Steps

	1.	Data Loading & Cleaning:
	•	Removed duplicates and null values.
	•	Corrected data types.
	2.	Exploratory Data Analysis (EDA):
	•	Descriptive statistics.
	•	Group-level analysis of conversion rates and ad engagement.
	3.	Visualizations:
	•	Bar plot of conversion rates by test group.
	•	Box plot of total ads viewed by conversion status.
	•	Heatmap of the Chi-Square test contingency table.
	4.	Statistical Testing:
	•	Chi-Square Test: To check if the conversion rates differ significantly.
	•	P-Value Interpretation: Statistical significance at a 95% confidence level.

📈 Key Findings

	•	Conversion Rates:
	•	Ad Group: X%
	•	PSA Group: Y%
	•	Statistical Test Results:
	•	Chi-Square Statistic: Z
	•	P-Value: W
	•	Result: The difference is/is not statistically significant.

🔍 Conclusions & Recommendations

Based on the analysis, recommend whether the company should prioritize Ads or PSAs to optimize marketing campaigns. Include any future recommendations for improvement or further analysis (e.g., considering day and hour of ad views).

🚀 How to Run the Project

	1.	Clone the Repository:

git clone https://github.com/yourusername/ab-testing-project.git


	2.	Install Required Libraries:

pip install -r requirements.txt


	3.	Run the Notebook:
Open AB_Testing_Project.ipynb in Jupyter Notebook or any IDE.

📂 Project Structure

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
  |-- requirements.txt
