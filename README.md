## Google Play Store Data Analysis: EDA and Feature Engineering

## Project Overview
A Python project exploring Google Play Store data to understand app ratings,

categories, installations, reviews, and pricing through data cleaning,

exploratory data analysis, and feature engineering

## Objectives
- Inspect the dataset and identify missing values and duplicate app records.
- Clean and prepare fields for analysis.
- Explore app categories, ratings, reviews, installs, size, and pricing.
- Compare app category counts and installation totals.
- Present findings with charts.

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Notebook
Open `notebooks/google_play_store_eda_feature_engineering.ipynb` to review the code, analysis, and outputs.

## Key findings reported in the notebook
These findings are transcribed from the notebook's saved outputs and written observations:
1. The original dataset contains **10,841 rows and 13 columns**.
2. The notebook reports missing values in fields including **Rating (1,474)**, **Type (1)**, **Content Rating (1)**, **Current Ver (8)**, and **Android Ver (3)**.
3. The notebook identifies **1,181 duplicate app records** and reports **9,659 rows** after keeping one record per app.
4. The notebook's category analysis identifies **Family** as the largest category by app count (about **18%**) and **Beauty** as the smallest (less than **1%**).
5. The notebook reports **GAME** as the category with the largest total number of installations, at approximately **35 billion**.
6. The notebook reports these popular apps within selected categories: **Subway Surfers** (GAME), **Hangouts** (COMMUNICATION), **Google Drive** (PRODUCTIVITY), and **Instagram** (SOCIAL).
7. The notebook reports **271 apps with a 5.0 rating** in its final rating query.

> Note: These are the findings written or displayed in the supplied notebook. Some results depend on the notebook's cleaning and aggregation choices. Re-run the notebook and verify the calculations before using the figures in a formal report or interview.

## Visualisations
Charts extracted from the notebook's saved outputs are in the `images/` folder.

### Numeric feature distributions
<img width="1489" height="954" alt="Image" src="https://github.com/user-attachments/assets/ba160858-1a80-4215-a795-e8db8e66b3f9" />

### Categorical feature distributions
<img width="1990" height="842" alt="Image" src="https://github.com/user-attachments/assets/e181734b-5bef-488f-b18f-0221dc62f3b5" />

### App category proportions
<img width="1300" height="1182" alt="Image" src="https://github.com/user-attachments/assets/6555f8bd-dc13-47be-860c-65bc380305b6" />

### Top app categories
<img width="1246" height="663" alt="Image" src="https://github.com/user-attachments/assets/1e11c255-6e39-49ff-9662-2fafb0ff2147" />

### Most installed categories
<img width="1400" height="890" alt="Image" src="https://github.com/user-attachments/assets/e05fec77-4bb2-4ad0-8369-54d434e178f5" />

### Top installed apps in selected categories
<img width="3948" height="1499" alt="Image" src="https://github.com/user-attachments/assets/f5a30d9c-115d-435d-8daf-e7734e821019" />


## Repository structure
```text
google-play-store-eda-feature-engineering/
├── README.md
├── requirements.txt
├── notebooks/
│   └── google_play_store_eda_feature_engineering.ipynb
└── images/
    ├── numeric_features_distribution.png
    ├── categorical_features_distribution.png
    ├── app_category_proportion.png
    ├── top_app_categories.png
    ├── most_installed_categories.png
    └── top_installed_apps_by_category.png
```

## 👤 Author

Presley Ufuoma Sergine
Data Analyst | Lagos, Nigeria

<p>
  <a href="https://www.linkedin.com/in/presley-sergine-b9176343a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:presleysergine23@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
