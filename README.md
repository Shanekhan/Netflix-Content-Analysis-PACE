# Netflix Content Analysis (PACE Workflow)

## Overview
This project provides a **comprehensive exploratory data analysis (EDA)** of Netflix content using the **PACE workflow**: Plan → Analyze → Construct → Execute.  

It explores:
- The type of content Netflix releases the most (Movies vs TV Shows)  
- Genre distribution  
- Country contributions  
- Content trends over time  
- Movie durations and rating distributions  

The project is beginner-friendly and suitable for data enthusiasts, students, or analysts interested in streaming content patterns.

---

## Repository Files
| File | Description |
|------|-------------|
| `netflix_titles.csv` | Dataset containing Netflix movies and TV shows with columns such as `title`, `genre`, `country`, `release_year`, `rating`, `duration`. |
| `Netflix-Content-Analysis.ipynb` | Jupyter Notebook containing the step-by-step analysis using the PACE workflow. |
| `Netflix-Content-Analysis.pdf` | PDF version of the notebook for quick reference and sharing. |

---

## Key Insights

### 1. Dominant Content Type
- Netflix’s catalog is overwhelmingly composed of **Movies (97%)**, with TV Shows representing only **3%**.  
- This indicates a strong focus on movie content over serialized shows.

### 2. Top Genres
- Most frequently released genres are **International Movies**, **Dramas**, and **Comedies**.  
- Action & Adventure, Independent Movies, and Romantic Movies also appear frequently.  
- Netflix aims to cater to global audiences and diverse tastes.

### 3. Top Contributing Countries
- The **United States, India, and United Kingdom** produce the majority of Netflix content.  
- This reflects Hollywood dominance and Netflix’s strategy to expand regionally.

### 4. Content Trends Over Time
- Netflix’s content production grew significantly from **2015 to 2018**, peaking in 2017–2018.  
- A slight decline after 2019 reflects global production slowdowns.

### 5. Movie Duration Insights
- Most movies run for **90–120 minutes**, which aligns with typical audience preferences.  
- Outliers exist with very short or extremely long durations.

### 6. Rating Distribution
- Majority of titles target **adult and teen audiences** (TV-MA, TV-14, R).  
- Family-friendly and children’s content is a smaller portion of the library.

---

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Netflix-Content-Analysis-PACE.git

Navigate into the project folder:

cd Netflix-Content-Analysis-PACE


Open the Jupyter Notebook:

jupyter notebook Netflix-Content-Analysis.ipynb


Run all cells to reproduce the analysis and visualizations.



Tools & Libraries

Python 3.x

pandas, numpy

matplotlib, seaborn


seaborn
