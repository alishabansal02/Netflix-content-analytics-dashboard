# Netflix Content Analytics & Executive Dashboard

A complete, end-to-end analytics engagement built on the Netflix Movies and TV Shows dataset (Kaggle) —
demonstrating data cleaning, feature engineering, exploratory and statistical analysis, dashboard design,
and executive-level business reporting.

This project goes beyond a simple dashboard: it's a full analytics workflow, with the dashboard serving as
the final deliverable on top of a rigorous, reproducible analysis.

## What's Inside

| File | Description |
|---|---|
| `Netflix_Content_Analytics.ipynb` | Full reproducible analysis: cleaning → feature engineering → EDA → statistical testing → dashboard prep |
| `Netflix_Content_Analytics_Report.pdf` | 50-page executive consulting report with 28 charts, KPI dashboard, and business insights |
| `netflix_titles.csv` | Source dataset (Kaggle: Netflix Movies and TV Shows) |
| `requirements.txt` | Python dependencies |
| `figures/` | All 28 generated chart and dashboard-mockup images |

## Project Highlights

- **8,797** cleaned and feature-engineered titles across **87** countries and **42** genres
- **23 exploratory/advanced visualizations** + **5 dashboard mockup screens** (Executive, Content, Country, Genre, Rating)
- **7 statistical tests** (chi-square, correlation, t-test, ANOVA, outlier detection) with plain-English business interpretation
- **15 data-backed business insights** and **5 strategic recommendations**

## Sample Insights

- Movie production accelerated ~370% between 2016 and 2019 before plateauing.
- The U.S. contributes 36% of the catalog, followed distantly by India.
- TV Shows have grown faster in relative terms than Movies since 2018.
- U.S. movies run ~15 minutes shorter than international movies on average (statistically significant, p < 0.001).
- Content format preference (Movies vs. TV) varies significantly by country of origin (chi-square, p < 0.001).

*(See the full report for all 15 insights, statistical test results, and supporting charts.)*

## Dashboard Screens

The `figures/` folder includes 5 Power-BI-style dashboard mockups: **Executive**, **Content**, **Country**,
**Genre**, and **Rating** — each summarizing a different lens on the catalog with KPI cards and charts.

## Analytics Workflow

```
Raw Dataset → Data Cleaning → Feature Engineering → Exploratory Data Analysis
            → Statistical Testing → Dashboard Design → Business Insights → Recommendations
```

## Getting Started

```bash
git clone https://github.com/yourusername/netflix-content-analytics-dashboard.git
cd netflix-content-analytics-dashboard
pip install -r requirements.txt
jupyter notebook Netflix_Content_Analytics.ipynb
```

Run all cells to reproduce the cleaned dataset, every chart, and every statistical test from scratch.

## Skills Demonstrated

Data Cleaning · Feature Engineering · Exploratory Data Analysis · Data Visualization · Dashboard Design ·
Business Intelligence · Statistical Analysis · Storytelling with Data · Professional Reporting ·
Python Programming · Jupyter Notebook Documentation

## Dataset Source

[Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) — Kaggle

## About

Prepared by **[Your Name]**, Data Analytics Consultant. See Section 15 of the PDF report for full bio and contact details.
