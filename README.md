# 🎬 Netflix Dataset Analysis — Major Project

## 📘 Project Overview
This project analyzes the Netflix dataset to uncover content trends, audience preferences, and strategic insights into Netflix’s evolving catalog.  
The dataset contains **7,789 records** and **11 attributes**, including information about movies and TV shows such as title, director, cast, country, release year, rating, duration, and genre.

The main objective is to explore **how Netflix’s content strategy has evolved** across years, genres, and countries — and to use data-driven insights for future strategic recommendations.

---

## 🎯 Problem Statement
With growing competition from platforms like **Amazon Prime**, **Disney+**, and **regional OTT services**, Netflix must understand its own catalog trends to stay competitive.  
This analysis focuses on identifying:
- The balance between **Movies and TV Shows**
- **Genre popularity** and its evolution over time
- **Country-wise content contributions**
- **Audience-oriented insights** based on ratings and duration trends

---

## 🚀 Objectives
- Analyze the distribution of **Movies vs TV Shows** over the years  
- Identify the **most common genres** and their changing trends  
- Compare **country-wise content contributions** to Netflix’s catalog  
- Explore **rating distribution** and **average duration trends**

---

## 🧩 Dataset Information
- **Total Records:** 7,789  
- **Columns (Attributes):** 11  
- **Time Span:** 2008 – 2021  
- **File Used:** `Netflix Dataset.csv`  

| Column Name | Description |
|--------------|--------------|
| Show_Id | Unique Identifier |
| Category | Type (Movie / TV Show) |
| Title | Title of the Content |
| Director | Director Name |
| Cast | Leading Cast Members |
| Country | Country of Origin |
| Release_Date | Date Content Was Released |
| Rating | Age Rating (e.g., TV-MA, PG-13) |
| Duration | Duration (Minutes / Seasons) |
| Type | Genre(s) |
| Description | Summary of the Content |

---

## 🧹 Data Cleaning Steps
1. Removed rows with **missing Release_Date and Rating** (essential for accurate analysis).  
2. Filled missing values in:
   - **Director →** "Not Available"
   - **Cast →** "Not Available"
   - **Country →** "Unknown"
3. Converted `Release_Date` to datetime and extracted **Year**.
4. Standardized `Duration` column to numeric format.

---

## 📊 Exploratory Data Analysis (EDA)
The analysis covers the following key aspects:

1. **Movies vs TV Shows Distribution**
   - Compare count of movies and shows on Netflix.

2. **Yearly Content Trends**
   - Visualize how content has evolved from 2008 to 2021.

3. **Country-Wise Contributions**
   - Identify top 10 content-producing countries.

4. **Genre Popularity**
   - Extract and visualize top 10 most common genres.

5. **Ratings Distribution**
   - Understand audience classification patterns (e.g., TV-MA, PG).

6. **Average Movie Duration Over the Years**
   - Track how movie lengths have changed over time.

---

## 📈 Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Google Colab / Jupyter Notebook  
- **Dataset:** Netflix Dataset (`Netflix Dataset.csv`)

---

## 🧠 Key Insights
1. The number of **Movies** is higher, but **TV Shows** have increased steadily in recent years.  
2. **USA**, **India**, and **UK** are the top content producers.  
3. **Dramas, Documentaries, and Comedies** are the most common genres.  
4. **TV-MA** dominates the rating distribution, showing Netflix’s focus on mature audiences.  
5. **Average movie duration** has slightly decreased over the years.

---

## 🧭 How to Run the Project (in Google Colab)
1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy and paste the complete Python code from `Netflix_Analysis.ipynb`.
4. Upload your dataset file — `Netflix Dataset.csv`.
5. Run all cells in order to generate all visualizations and insights.

---

## 🧩 Project Workflow Summary
1. **Data Loading** → Import CSV into Pandas  
2. **Data Cleaning** → Handle missing values and extract relevant features  
3. **Data Exploration** → Analyze Movies, Shows, Genres, and Ratings  
4. **Visualization** → Use Matplotlib and Seaborn for insights  
5. **Insight Generation** → Derive trends and strategic recommendations  

---

## 💡 Future Enhancements
- Add **Machine Learning models** for predicting popular genres or ratings.  
- Perform **sentiment analysis** on descriptions for deeper content insights.  
- Build an **interactive dashboard** using Plotly or Power BI for dynamic exploration.

---

## ✍️ Author
**M. Venkatesh**  
🚀 Passionate about Data Analytics, Machine Learning, and AI-driven Insights

---

## 🏁 License
This project is open-source and available for educational and research use only.
