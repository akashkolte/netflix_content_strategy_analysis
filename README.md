# 🎬 Netflix Content Strategy Analysis

An exploratory data analysis (EDA) project on Netflix’s content library to understand
how Netflix builds, grows, and positions its catalog across time, geography, genres,
and audience maturity levels.

This project focuses on data cleaning, feature engineering, time-series analysis,
and text analytics to extract meaningful business insights.

---

## 📌 Project Objective

To analyze Netflix’s dataset and answer key business questions such as:

- How content is distributed between Movies and TV Shows  
- How Netflix’s catalog has grown over time  
- What kind of audiences Netflix targets  
- Which countries and genres dominate the platform  
- What themes commonly appear in content descriptions  

---

## 📁 Dataset

Source: Netflix Titles Dataset  
Each record contains:

- Title, Type (Movie/TV Show)  
- Director, Cast, Country  
- Date Added, Release Year  
- Rating, Duration  
- Genres (listed_in)  
- Description  

---

## 🛠 Key Steps in the Analysis

### 1. Data Cleaning & Transformation
- Handled missing values using:
  - “Unknown” for text fields
  - Mode/median for categorical/numerical fields
- Converted date fields to datetime
- Created new features:
  - `year_added`, `month_added`
  - `age_on_netflix = year_added - release_year`

---

### 2. Content Distribution Analysis
- Movies make up ~70% of Netflix content
- TV Shows account for ~30%
- Content addition peaked around 2019

---

### 3. Time-Series Analysis
- Content additions increased rapidly from 2016–2019  
- Slight slowdown after 2020  
- Movies grew faster than TV Shows  

---

### 4. Genre & Geography Analysis
- Top genres:
  - International Movies  
  - Dramas  
  - Comedies  
  - Action & Adventure  
- Top content producing countries:
  - United States  
  - India  
  - United Kingdom  
  - Japan  
  - South Korea  

Shows Netflix’s strong global strategy.

---

### 5. Ratings & Audience Targeting
- Most common ratings:
  - TV-MA  
  - TV-14  
- Indicates Netflix mainly targets mature audiences.

---

### 6. Content Freshness Strategy
- Many titles added in the same year they were released → Netflix Originals  
- Long tail of very old content → licensed classics  
- Strategy = New Originals + Deep Library

---

### 7. Text Analysis on Descriptions
- Word Cloud analysis revealed common themes:
  - Life, family, love, young, friends, world  
- Bigram (word-pair) analysis highlighted phrases like:
  - “high school”  
  - “year old”  
  - “young man”  
  - “New York”  

Shows focus on youth, relationships, and urban life.

---

## 📈 Key Insights

- Netflix is movie-heavy but steadily growing TV content  
- Strong push between 2016–2019  
- Focus on mature audiences  
- Heavy investment in international content  
- Strategy blends:
  - Fresh originals  
  - Old licensed classics  
- Content themes revolve around relationships, growth, struggle, and discovery  

---

## 📦 How to Run

git clone https://github.com/akashkolte/netflix_content_strategy_analysis.git

jupyter notebook "Netflix's_Content_Strategy.ipynb"
or use Google Colab

📌 Skills Demonstrated
	•	Data Cleaning & Feature Engineering
	•	Exploratory Data Analysis
	•	Time-Series Analysis
	•	Text Analytics (Word Clouds, Bigrams)
	•	Visualization with Matplotlib & Seaborn
	•	Business-oriented insights


❤️ Author

Akash Kolte
MS in Computer Science (AI/ML) – SUNY Buffalo
GitHub: https://github.com/akashkolte
LinkedIn: https://linkedin.com/in/akash-kolte

🚀 Future Improvements
	•	Add trend analysis for ratings over time
	•	Predict content success using ML
	•	Build dashboard using Streamlit
	•	Add topic modeling on descriptions
