# 🎵 Music Streaming User Behavior Analysis

## 📌 Overview
This project analyzes user listening behavior in a music streaming platform. The work includes data cleaning, preprocessing, and exploratory analysis to compare music activity across cities and days of the week.

## 🎯 Objective
To prepare raw streaming data for analysis and identify differences in listening patterns between cities, with a focus on user activity on Mondays and Fridays.

## 🛠️ Tools & Technologies
- Python
- pandas
- Data Cleaning
- Exploratory Data Analysis (EDA)

## 📂 Dataset
The dataset contains music streaming activity records, including:
- User ID
- Track name
- Artist name
- Genre
- City
- Day of the week
- Time played

## 🔍 Key Steps
- Loaded and reviewed the dataset structure
- Standardized column names using consistent formatting
- Replaced missing values in relevant columns
- Identified and removed explicit duplicates
- Corrected implicit duplicates in music genres
- Grouped listening activity by city
- Compared listening activity by day of the week
- Built a reusable function to analyze track counts by city and day

## 📈 Key Findings
- Springfield showed significantly higher listening activity than Shelbyville
- Friday had more streaming activity than Monday overall
- Listening behavior varied depending on both city and day
- Cleaning genre inconsistencies improved the reliability of the analysis

## 💡 Business Impact
This analysis can help a music platform:
- Better understand regional user behavior
- Detect activity patterns by day of the week
- Improve audience segmentation
- Support targeted campaigns or content recommendations based on listening trends

## 🚀 How to run
1. Clone this repository
2. Open the notebook in Jupyter Notebook or JupyterLab
3. Make sure the dataset is available in the expected path
4. Run the cells in order

## 📚 Skills Demonstrated
- Data preprocessing
- Missing value treatment
- Duplicate handling
- Data standardization
- Grouped analysis with pandas
- Business-oriented interpretation of results
