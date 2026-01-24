# 📺 EDA on the Netflix Content Strategy

## 🔍 Project Overview

This repository contains a data-driven Exploratory Data Analysis (EDA) project that examines Netflix’s content catalog to uncover insights on trends, distribution, and characteristics of movies and TV shows available on the platform.

The goal is to analyze how Netflix’s content strategy has evolved over time, identify patterns in content types, ratings, genres, and geographic distribution, and derive useful visual insights using Python and popular data science libraries. :contentReference[oaicite:1]{index=1}

---

## 🧠 Motivation

Netflix is one of the world’s leading streaming platforms, with thousands of movies and TV shows available globally. By conducting EDA on its content dataset, we can better understand:
- How content addition has trended over the years  
- Which genres dominate the Netflix library  
- How ratings and types differ across regions  
- Country-wise production insights  
- Duration patterns for movies and shows :contentReference[oaicite:2]{index=2}

---

## 📁 Dataset

### Source

The dataset used in this project is a Netflix titles dataset commonly sourced from Kaggle (or similar public sources). It consists of information such as titles, genres, types, release years, ratings, and other metadata for Netflix content.

### Columns Description

Typical columns in this dataset include:
- `show_id`: Unique ID for every title  
- `type`: Content type (Movie or TV Show)  
- `title`: Title of the movie/TV show  
- `director`: Director(s)  
- `cast`: Cast members  
- `country`: Country of origin  
- `date_added`: When the content was added  
- `release_year`: Year of release  
- `rating`: Rating category  
- `duration`: Duration or number of seasons  
- `listed_in`: Genres  
- `description`: Summary description :contentReference[oaicite:3]{index=3}

---

## 🛠️ Tools & Libraries

This analysis uses Python and the following libraries:
- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` & `seaborn` – Visualization  
- `plotly` (optional) – Interactive charts  
- `wordcloud` (optional) – Word cloud of content titles :contentReference[oaicite:4]{index=4}

---

## 📊 What’s Included

The notebook performs the following steps:
1. **Data Loading & Cleaning**  
   - Import dataset & check for null/missing values  
   - Data preprocessing and type conversions  
2. **Exploratory Data Analysis**  
   - Trend analysis of content added over years  
   - Genre distribution and popular genres  
   - Country-wise content production  
   - Rating analysis by content type  
   - Duration insights for Movies vs TV shows  
3. **Visualizations**  
   - Bar charts, pie charts, histograms, count plots  
   - Heatmaps & correlation analysis  
4. **Key Insights & Summary**  
   - Major observations and trends :contentReference[oaicite:5]{index=5}

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SagarDeshmukh24/GFG-21-Projects-ML-DL-GenAI-.git

