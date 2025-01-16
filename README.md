# Marketing Campaign Analysis using A/B Testing

## Project Overview :-
This project evaluates the effectiveness of advertising campaigns using A/B testing techniques. By analyzing user behavior, ad exposure, and conversion rates, the project provides actionable insights into the success of the campaigns and identifies factors influencing user conversions.
Key questions addressed:
  1. Was the campaign successful?
  2. How much of the success can be attributed to advertisements?

## Dataset :-
The dataset was sourced from Kaggle and extracted programmatically using the Kaggle API. It includes detailed information about user interactions with advertisements and contains the following columns:

- Index: Row index.
- User ID: Unique identifier for each user.
- Test Group: Experimental group ("ad") or control group ("psa").
- Converted: Whether the user made a purchase (True/False).
- Total Ads: Number of ads seen by the user.
- Most Ads Day: Day the user saw the highest number of ads.
- Most Ads Hour: Hour the user saw the highest number of ads.
Rows: 500,000+

## Key Insights :- 
- Campaign Success: Ads increased conversions by 87.5% compared to PSAs.
- Peak Conversion Times: Users exposed to ads during peak hours were 8.1% more likely to convert.
- Behavioral Patterns: Higher ad exposure (>5 ads) correlated with a significant uplift in conversion rates.

## Methodology :-
- Data Extraction: Used the Kaggle API to download the dataset efficiently.
- Data Cleaning: Ensured data consistency and accuracy using Python libraries (pandas, numpy).
- Exploratory Data Analysis (EDA): Investigated user behavior and ad exposure patterns.
- Statistical Analysis: Performed hypothesis testing (chi-square, t-tests) to determine the significance of conversion differences.
- Visualization: Created clear and actionable visualizations using Matplotlib and Seaborn.

## Tools and Technologies:-
- Languages: Python
- Libraries: pandas, numpy, scipy, matplotlib, seaborn
- Data Source: Kaggle (via Kaggle API)
- Statistical Methods: A/B testing, hypothesis testing (chi-square, t-tests)

## Project Highlights:-
- Extracted and analyzed 500K+ rows of data programmatically using the Kaggle API.
- Evaluated campaign performance for experimental and control groups.
- Quantified the impact of advertisements and identified optimal times for ad delivery.
- Provided data-driven recommendations to improve campaign efficiency and ROI.

## Visualizations:-
- Conversion rate comparisons between test groups.
- Time-based trends in ad exposure and conversions.
- Correlations between ad frequency and user behavior.

## Results:-
This analysis demonstrated the power of A/B testing in quantifying the effectiveness of advertising campaigns and provided actionable insights to enhance future marketing strategies.


