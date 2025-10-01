# 📊 Netflix Dataset Analysis
## 📌 Project Overview

This project analyzes the Netflix Dataset (7,789 records, 11 columns) containing information about Movies and TV Shows available on Netflix between 2008–2021.
The goal is to uncover content trends (Movies vs. TV Shows, popular genres, country contributions) and provide strategic recommendations for Netflix to stay competitive in the OTT industry.

## 🏆 Problem Statement

Netflix faces tough competition from platforms like Amazon Prime, Disney+, and regional OTT providers. To remain ahead, Netflix must analyze its content catalog to identify:
- Strengths
- Gaps
- Opportunities

This project answers:
- How has Netflix’s Movies vs. TV Shows distribution evolved over time?
- Which genres are most popular, and how have they changed?
- Which countries contribute the most content to Netflix’s catalog?

## 🎯 Objectives
- Analyze Movies vs. TV Shows over the years
- Identify most common genres and their trends
- Compare country-wise contributions
- Explore ratings and duration distribution
- Provide strategic recommendations for Netflix

## 📂 Dataset
- File: Netflix Dataset.csv
- Rows: 7,789
- Columns:
Show_Id, Category, Title, Director, Cast, Country, Release_Date, Rating, Duration, Type, Description

##  🛠️ Tech Stack
- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Jupyter Notebook for analysis

## 🚀 How to Run
1. Clone this repository
```bash
git clone https://github.com/Shilpa3107/VOIS_AICTE_Oct2025_MajorProject_Shilpa-Sinha/netflix-analysis.git
cd netflix-analysis
```
2. Install required libraries
```bash
pip install pandas numpy matplotlib seaborn plotly
```
3. Run the Jupyter Notebook
```bash
jupyter notebook Netflix_Analysis.ipynb
```
4. Make sure Netflix Dataset.csv is in the project folder

## 📊 Key Insights (Example — update with your results)
- Movies dominate Netflix’s catalog, but TV Shows have grown rapidly since 2016
- Documentaries and Dramas are among the top genres
- USA, India, and UK are the top contributing countries
- Most movies have durations between 80–120 minutes
- Ratings are concentrated around TV-MA and PG-13

## 💡 Strategic Recommendations
- Increase investment in regional content (India, Brazil, South Korea)
- Expand documentary and drama genres where demand is rising
- Focus more on TV Shows, as their growth trend is stronger than movies
- Strengthen family/kids content to target wider demographics

## 📌 Future Work
- Add viewership data (if available) to link supply with demand
- Use NLP on descriptions to cluster content into hidden themes
- Build a dashboard for interactive Netflix trend exploration

## 📜 License
This project is for educational purposes only.
