# SWYNEX Internship – Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of my **Data Analyst Internship at SWYNEX Technologies** (Task 2). I performed **Exploratory Data Analysis (EDA)** on the cleaned **Netflix Movies and TV Shows** dataset from Task 1 to understand its structure, calculate important statistics, and identify trends, patterns and anomalies.

---

## 🎯 Objectives

- Understand the structure and quality of the cleaned dataset
- Calculate important summary statistics
- Identify trends, patterns and anomalies
- Create charts to visualize the data
- Explain useful insights from the analysis

---

## 📂 Dataset

- **File:** `netflix_titles_cleaned.csv`
- **Source:** Cleaned dataset from Task 1 (Data Cleaning & Preparation)
- **Content:** Information about Netflix Movies and TV Shows such as type, title, country, release year, rating, duration and genre

---

## 🛠️ Tools & Libraries Used

- **Python**
- **pandas** – data handling and analysis
- **NumPy** – numerical operations
- **matplotlib / seaborn** – data visualization
- **VS Code** – development environment

---

## 🔍 Analysis Performed

1. Dataset overview (rows, columns, data types)
2. Missing value check
3. Summary statistics
4. Movies vs TV Shows distribution
5. Movie duration analysis
6. TV show seasons analysis
7. Content rating analysis
8. Release year trend
9. Country-wise distribution
10. Outlier and anomaly detection

---

## 💡 Key Insights

### 1. Movie vs TV Show Distribution

The dataset contains both Movies and TV Shows, with Movies forming a slightly larger portion of the available titles.

### 2. Movie Duration

Most movies are concentrated within a typical feature-film duration range. A few unusually high duration values were identified as potential data-quality outliers.

### 3. TV Show Seasons

Most TV Shows contain a relatively small number of seasons. An unusually high season value was identified as a potential data-quality anomaly and was considered during the analysis.

### 4. Content Ratings

TV-14 is one of the most frequently occurring ratings in the dataset. Other ratings such as PG, TV-PG, R, and G are also represented.

### 5. Release Year Trend

The number of titles varies across different release years, showing fluctuations and noticeable changes in the number of titles over time.

### 6. Country Distribution

The dataset contains titles from multiple countries, showing that the content represented in the dataset has an international distribution.

---

## ⚠️ Data Quality Observations

During the analysis, some unusual values were observed, including extremely high values in movie duration and TV show seasons.

These values were treated as potential data-quality anomalies rather than being assumed to represent normal Netflix content.

Missing values in fields such as movie duration and TV show seasons were also observed because these fields are not applicable to every type of content.

---

## 📊 Charts

All charts generated during the analysis are saved in the `charts/` folder.

---

## 📁 Repository Structure

```
SWYNEX-Exploratory-Data-Analysis/
│
├── netflix_titles_cleaned.csv
├── eda.py / eda.ipynb
├── charts/
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository
2. Install the required libraries:
```
   pip install pandas numpy matplotlib seaborn
```
3. Run the analysis file:
```
   python eda.py
```

---

## ✅ Conclusion

This EDA gave a clear understanding of the Netflix dataset, including its content types, ratings, release trends and data-quality issues. The analysis also highlighted unusual values that should be handled carefully in further analysis or dashboarding.

---

## 👩‍💻 Author

**Shivani Sharma**
Data Analyst Intern – SWYNEX Technologies
GitHub: [sharmashivani90029-lang](https://github.com/sharmashivani90029-lang)

#SWYNEX #Internship #DataAnalysis #EDA #Python