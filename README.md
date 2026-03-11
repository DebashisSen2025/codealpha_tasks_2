# 📺 Netflix Data Analysis — EDA Project
### CodeAlpha Data Analytics Internship | Task 2

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Charts-red?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 🎯 Project Overview

This project performs a complete **Exploratory Data Analysis (EDA)** on the **Netflix Titles Dataset** from Kaggle.  
The goal is to explore content patterns, understand what Netflix prioritizes, and generate actionable business insights from real-world streaming data.

---

## 👤 Author

**Debashis Sen**
- 🐙 GitHub: [DebashisSen2025](https://github.com/DebashisSen2025)
- 🏢 Internship: CodeAlpha — Data Analytics

---

## 📁 Dataset

| Detail | Value |
|--------|-------|
| Source | [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) |
| Total Records | 8,807 |
| Total Features | 12 |
| File | `netflix_titles.csv` |

**Features include:** `title`, `type`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genres), `description`

---

## ❓ Business Questions Answered

| # | Question |
|---|----------|
| 1 | What is the distribution of Movies vs TV Shows? |
| 2 | Which countries produce the most Netflix content? |
| 3 | How has Netflix content volume changed over the years? |
| 4 | What are the most common genres on Netflix? |
| 5 | What are the most common content ratings? |
| 6 | How has the Movies vs TV Shows mix evolved year by year? |

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
Loaded `netflix_titles.csv` using Pandas with `show_id` as index.

### 2️⃣ Data Exploration
Analyzed dataset structure, data types, and missing value distribution.

### 3️⃣ Data Cleaning
- Filled missing `country` values with `"Unknown"` — preserving all rows
- Parsed `date_added` to datetime and extracted `year_added`
- Removed only 4 rows with missing `rating`
- Dropped `director` and `cast` columns (not needed for this analysis)

### 4️⃣ Data Analysis
Used filtering, sorting, groupby, and value_counts to uncover patterns.

### 5️⃣ Visualization
Professional Netflix-themed charts with consistent styling.

### 6️⃣ Insight Generation
Every chart paired with a real business insight.

---

## 📈 Visualizations Created

| Chart | Purpose |
|-------|---------|
| Bar + Pie Chart | Movies vs TV Shows distribution |
| Horizontal Bar | Top 10 content-producing countries |
| Line + Area Chart | Content additions over the years (with peak annotation) |
| Horizontal Bar | Top 10 genres |
| Count Plot | Most common content ratings |
| Grouped Bar | Movies vs TV Shows added per year |

> 🎨 All charts use a professional **Netflix-themed color palette** (`#E50914`, `#B81D24`)

---

## 🔑 Key Insights

| # | Finding | Actionable Insight |
|---|---------|-------------------|
| 1 | ~70% Movies, ~30% TV Shows | Netflix is primarily a film-heavy platform |
| 2 | USA, India, UK lead content production | Reflects market size and investment priorities |
| 3 | Content peaked in 2019 | COVID-19 disrupted post-2019 additions |
| 4 | International Movies & Dramas dominate | Global, story-driven content wins |
| 5 | TV-MA is the most common rating | Focus on adult audiences differentiates from broadcast TV |
| 6 | TV Show additions grew after 2016 | Strategic shift toward original series investment |

---

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, groupby, value counts |
| `matplotlib` | Base plotting, custom styling |
| `seaborn` | Statistical chart types |
| `collections.Counter` | Genre frequency analysis |

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Upload `Netflix_data_analysis.ipynb` and `netflix_titles.csv` to [Google Colab](https://colab.research.google.com)
2. Run all cells

### Option 2 — Local Setup
```bash
# Clone the repository
git clone https://github.com/DebashisSen2025/codealpha_tasks_2

# Install dependencies
pip install pandas matplotlib seaborn

# Launch the notebook
jupyter notebook Netflix_data_analysis.ipynb
```

---

## 📂 Repository Structure

```
codealpha_tasks_2/
│
├── Netflix_data_analysis.ipynb   # Main EDA notebook
├── netflix_titles.csv            # Dataset (8,807 Netflix titles)
└── README.md                     # Project documentation
```

---

## 🏆 Skills Demonstrated

- ✅ Exploratory Data Analysis (EDA)
- ✅ Data Cleaning & Preparation
- ✅ Statistical Data Exploration
- ✅ Professional Data Visualization
- ✅ Business Insight Generation
- ✅ Python Data Analysis with Pandas

---

*⭐ If you found this project useful, please star the repository!*  
*Completed as part of **CodeAlpha Data Analytics Internship** — February Batch 2026*
