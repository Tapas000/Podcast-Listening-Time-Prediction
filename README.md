# 🎧 Podcast Listening Time Analysis

This project analyzes podcast episodes to understand patterns in listener behavior and what factors influence podcast listening time.

## 📂 Project Overview

The notebook `podcast-listening-time.ipynb` explores a dataset with various features about podcast episodes and attempts to predict or understand the **Listening Time** of users. The project includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Visualizations
- Insights into what impacts podcast engagement

## 📊 Dataset Features

The dataset contains the following columns:

- `Podcast_Name`
- `Episode_Title`
- `Episode_Length_minutes`
- `Genre`
- `Host_Popularity_percentage`
- `Publication_Day`
- `Publication_Time`
- `Guest_Popularity_percentage`
- `Number_of_Ads`
- `Episode_Sentiment`
- `Listening_Time_minutes` (Target variable)

## 🧪 Key Tasks Performed

- Missing value treatment and data cleaning
- Encoding categorical features like `Genre` and `Episode_Sentiment`
- Correlation analysis and distribution plotting
- Regression modeling (if applicable)
- Feature importance analysis

## 📌 Insights

Some of the findings (based on EDA and modeling):

- Highly popular hosts and guests tend to retain more listeners.
- Sentiment and genre play a role in listening time.
- Too many ads may decrease listening duration.

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (if modeling included)
- Jupyter Notebook

