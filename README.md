# -us-accident-analysis
Analysed 2.8M+ US road accidents using Python to find patterns by location, time, weather and severity.
# US Road Accident Analysis (2016–2023)

## About this project
Analysed a real-world dataset of 2.8 million+ US road accidents to find 
patterns by location, time, weather, and severity using Python.

This project was built as part of my transition into data analytics and 
platform support roles — demonstrating real data cleaning, feature 
engineering, and visual storytelling skills.

---

## Tools used
- Python (pandas, NumPy, matplotlib, seaborn)
- Google Colab
- Dataset: US Accidents March 2023 — Kaggle (Sobhan Moosavi)

---

## What I did

### 1. Data Cleaning
- Loaded and explored a 2.8M row dataset
- Identified and handled missing values across 46 columns
- Dropped irrelevant columns (End_Lat, End_Lng, Airport_Code, 
  Wind_Chill, Weather_Timestamp)
- Filled numerical missing values with median
- Filled categorical missing values with mode
- Removed rows missing critical fields like Street, City, Zipcode

### 2. Feature Engineering
Created new columns from raw timestamp data:
- Hour — to analyse peak accident times
- Day of Week — to find busiest days
- Month and Season — to find seasonal patterns
- Duration in minutes — filtered outliers (kept 1 min to 24 hrs only)

### 3. Analysis & Charts built
| Chart | What it shows |
|---|---|
| Top 10 Dangerous States | California, Florida, Texas lead |
| Top 10 Dangerous Cities | Miami, Houston, Charlotte top the list |
| Day vs Night (Pie chart) | 70%+ accidents happen in daylight |
| Accidents by Hour | Peak at 7–9am and 4–6pm (rush hours) |
| Accidents by Day of Week | Weekdays have significantly more accidents |
| Accidents by Severity | Severity 2 accounts for majority of accidents |
| Accidents by Season | Fall and Winter have higher accident counts |
| Top 10 Weather Conditions | Fair weather has most accidents — not bad weather |

---

## Key findings
- Rush hour is the most dangerous time — 8am and 5pm are peak hours
- California alone accounts for nearly 30% of all accidents in the dataset
- Surprisingly, most accidents happen in fair weather — not rain or fog
- Severity level 2 (moderate impact) makes up the bulk of all accidents
- Weekdays are far more dangerous than weekends

---

## Files in this repo
- `US_Accident_Analysis.ipynb` — full notebook with all code and charts

---

## About me
I'm Tejaswi Kambala — a data and operations professional transitioning 
into data analytics and platform support roles. This is one of several 
projects I'm building to demonstrate real analytical thinking with 
real-world datasets.

Connect with me on LinkedIn: www.linkedin.com/in/tejaswi-kambala
