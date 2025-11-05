# Data-engineering-with-analysis-
End-to-end Netflix Data Engineering &amp; Machine Learning Pipeline built in Python

 Netflix Data Engineering & ML Insights Pipeline
📌 Overview

This project builds an end-to-end data analytics pipeline using Netflix viewing dataset.
It demonstrates data engineering, visualization, and machine learning in one workflow — ideal for portfolio or resume projects.

⚙️ Features

✅ ETL pipeline: Cleaning, transformation, and SQLite integration

✅ EDA & Visualization: Matplotlib + Seaborn

✅ ML Models: K-Means Clustering & Linear Regression

✅ Automated chart saving for GitHub presentation

🧠 Key Insights

Netflix content grew significantly after 2018

Majority of top-performing titles are globally available

English & Hindi dominate viewership

Regression model (R² ≈ 0.7) shows release year and global availability highly influence viewership

Clustering model identifies 3 content segments by popularity

🧰 Tools & Technologies
Category	Tools Used
Data Engineering	Pandas, SQLite
Visualization	Seaborn, Matplotlib
Machine Learning	Scikit-learn (KMeans, Linear Regression)
Environment	Google Colab
Deployment Ready	Streamlit compatible output structure
🧩 Folder Structure
📁 netflix-analytics-ml-pipeline/
│
├── Netflix_Data_Pipeline.ipynb
├── netflix_content.csv
├── output/
│   ├── cleaned_data.csv
│   ├── clusters.csv
│   ├── regression_coefficients.csv
│   └── charts/
│       ├── *.png
│
└── README.md

📊 Sample Visuals
Chart	Preview
🔥 Top 10 Titles	

🌍 Global Availability	

⚙️ Feature Importance	
🚀 How to Run (Colab)

Open Google Colab

Upload netflix_content.csv

Paste notebook code

Run all cells sequentially
