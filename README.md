# Bird-Species-Observation-Analysis# Bird Species Observation Analysis

## 📌 Project Overview
This project analyzes bird species observations from forest and grassland habitats to identify species diversity, environmental patterns, and conservation priorities.  
It combines exploratory data analysis (EDA) in Python (Jupyter Notebook) with an interactive Power BI dashboard.

**Author:** yelavarthi suchitra
**Date:**may 2026

---

## 📊 Dataset
The dataset contains bird monitoring observations, including:
- **Location details** (Site Name, Plot Name, Location Type)
- **Species information** (Common Name, Scientific Name, Watchlist Status)
- **Observation details** (Date, Temperature, Humidity, Disturbance)
- **Counts** within initial three minutes and total counts.

Data was cleaned and merged from:
- Forest dataset
- Grassland dataset

---

## 🔍 Analysis Performed
1. **Data Cleaning** – Removing nulls, formatting dates, handling missing codes.
2. **Exploratory Data Analysis (EDA)** – Summary stats, distribution analysis, environmental correlations.
3. **Power BI Dashboard** – Interactive visuals with slicers for month, location type, disturbance, and species.

---

## 📈 Dashboard Highlights
- **Total Bird Observations per Month**
- **Top 10 Most Observed Bird Species**
- **Top 10 Plots by Observation Count**
- **Observations by Temperature & Humidity Ranges**
- **PIF Watchlist Status Breakdown**
- **Disturbance Impact on Bird Count**
- **KPIs:** Total Observations, Unique Species, % Watchlist Species
- **Filters:** Location Type, Month, Species, Disturbance
- **Map Visual:** Site-wise distribution of observations

---

## 🛠 Tools Used
- **Python (Jupyter Notebook)** – Data cleaning, EDA
- **Pandas, Matplotlib** – Data processing and visualizations
- **Power BI** – Dashboard creation
- **Excel** – Preliminary inspection
- **GitHub** – Version control and sharing

---

## 📂 Project Structure
Bird-Species-Observation-Analysis/
│
├── data/
│ ├── bird_data_cleaned.csv
│ ├── raw_forest_data.csv
│ ├── raw_grassland_data.csv
│
├── notebooks/
│ ├── bird_analysis.ipynb
│ ├── bird_analysis.pdf
│
├── dashboard/
│ ├── bird_dashboard.pbix
│ ├── bird_dashboard.pdf
│
├── reports/
│ ├── Bird_Observation_Insights.pptx
│ ├── Bird_Observation_Insights.pdf
│
├── README.md


---

GitHub Upload Checklist
Before uploading:

Create GitHub Repo → Name: Bird-Species-Observation-Analysis

On local PC, create project folder matching the above Project Structure.

Place the following files:

bird_data_cleaned.csv (final cleaned dataset)

Raw datasets (optional, if allowed to share)

Jupyter Notebook (.ipynb) and PDF export

Power BI file (.pbix) and PDF export

Final PPT and PDF report


README.md file

Check file sizes – If .pbix > 25 MB, you’ll need Git LFS (Large File Storage).

Open GitHub Desktop or use Git CLI:

git init
git add .
git commit -m "Initial commit - Bird Species Observation Analysis"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
After push → verify on GitHub that all folders and files are accessible.


Disclaimer
This project is developed for educational purposes only.
The datasets used are provided for demonstration and learning, and may not reflect complete or official data.
All interpretations and visualizations are part of an academic exercise.

License
If you want people to freely view and share but not commercially exploit:

License: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
You are free to share and adapt this work for non-commercial purposes, provided appropriate credit is given.

If you want open-source flexibility:

License: MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this work to use, copy, modify, merge, publish, and distribute, subject to inclusion of this notice.
