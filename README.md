# 📊 Netflix EDA & Trend Analysis

This project is an **Exploratory Data Analysis (EDA) and Trend Analysis** on Netflix content to understand content distribution, genre popularity, and content release trends.

## 📂 Dataset  
The dataset used for this analysis is `netflix_titles.csv`, which contains information about TV shows and movies on Netflix, including attributes like title, director, cast, country, date added, release year, duration, and rating.

## 🔎 Analysis Overview  

### 1️⃣ Data Cleaning  
✔ Checked for missing values  
✔ Converted `date_added` column to datetime format  
✔ Removed duplicates and handled categorical missing values  

### 2️⃣ Exploratory Data Analysis (EDA)  
✔ **Content Type Distribution** (Movies vs. TV Shows)  
✔ **Top 10 Countries with the Most Content**  
✔ **Genre Popularity Analysis**  
✔ **Rating Distribution**  
✔ **WordCloud of Genres**  

### 3️⃣ Trend Analysis  
✔ **Monthly and Yearly Content Release Trends**  
✔ **Film Duration Distribution**  

## 📊 Key Findings  
✅ **Movies dominate Netflix's catalog compared to TV shows.**  
✅ **USA, India, and the UK contribute the most content.**  
✅ **Content releases increased significantly after 2015, peaking in 2020.**  
✅ **Most movies have a runtime of 90-120 minutes.**  
✅ **Dramas, Comedies, and Action films are the most common genres.**  

## 📌 Visualizations  
- **Bar charts** for content distribution  
- **Pie charts** for percentage-based analysis  
- **Line charts** for trend analysis over time  
- **Histogram & Boxplots** for duration analysis  
- **WordCloud** for genre visualization  

## 🔧 Technologies Used  
- **Python** (pandas, numpy, matplotlib, seaborn, wordcloud)  
- **Jupyter Notebook / Colab**  

## 🚀 Run the Project  
To run the project:  
```bash
git clone https://github.com/Duyguonderr/netflix-eda.git
cd netflix-eda
pip install pandas numpy matplotlib seaborn wordcloud
jupyter notebook netflix_eda.ipynb
