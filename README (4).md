# 📺 Netflix Data Analysis — EDA Project

> **Exploratory Data Analysis on the Netflix Titles Dataset using Python**

---

## 🎯 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on the **Netflix Titles Dataset** from Kaggle. The goal is to explore content patterns, understand what Netflix prioritizes, and derive actionable insights from the data.

---

## 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preparation
- Statistical Data Exploration
- Professional Data Visualization
- Business Insight Generation
- Python Data Analysis with Pandas

---

## 📁 Dataset

| Detail | Value |
|--------|-------|
| Source | [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) |
| Total Records | 8,807 |
| Total Features | 12 |
| Target Variable | `type` — Movie or TV Show |

**Features include:** title, type, country, date_added, release_year, rating, duration, listed_in (genres), description

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

### 1️⃣ Problem Understanding
Define what patterns and trends are worth exploring in a streaming catalog.

### 2️⃣ Data Exploration
Analyze dataset structure, data types, and missing value distribution.

### 3️⃣ Data Cleaning
- Filled missing `country` values with `"Unknown"` (preserving all rows)
- Parsed `date_added` to datetime and extracted `year_added`
- Removed only 4 rows with missing `rating`
- Dropped `director` and `cast` columns (not needed for this analysis)

### 4️⃣ Data Analysis
Filtering, sorting, groupby, and value counts to uncover patterns.

### 5️⃣ Data Visualization
Professional Netflix-themed charts with consistent styling.

### 6️⃣ Insight Generation
Each chart is paired with a business insight.

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

> 🎨 All charts use a professional **Netflix-themed color palette** (`#E50914`, `#B81D24`, structured multi-color for categories)

---

## 🔑 Key Insights

| # | Finding | Insight |
|---|---------|---------|
| 1 | ~70% Movies, ~30% TV Shows | Netflix is primarily a film platform |
| 2 | USA, India, UK lead content production | Reflects market size and investment priorities |
| 3 | Content peaked in 2019 | COVID-19 disrupted post-2019 additions |
| 4 | International Movies & Dramas dominate genres | Global, story-driven content wins |
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
1. Upload `Netflix_data_analysis_FIXED.ipynb` and `netflix_titles.csv` to [Google Colab](https://colab.research.google.com)
2. Run all cells

### Option 2 — Local Setup

```bash
# Clone the repository
git clone https://github.com/madhav-0000/Netflix_Data_Analysis

# Install dependencies
pip install pandas matplotlib seaborn

# Launch the notebook
jupyter notebook Netflix_data_analysis_FIXED.ipynb
```

---

## 📂 Repository Structure

```
Netflix_Data_Analysis/
│
├── Netflix_data_analysis_FIXED.ipynb   # Main EDA notebook
├── netflix_titles.csv                  # Dataset (8,807 Netflix titles)
└── README.md                           # Project documentation
```

---

## 👤 Author

**Madhav**
- 🐙 GitHub: [madhav-0000](https://github.com/madhav-0000)

---

*If you found this project useful, please ⭐ star the repository!*
