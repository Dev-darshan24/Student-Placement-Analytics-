## Power BI Dashboard

### Page 1 — Placement Overview

This dashboard provides an overview of student placement outcomes, including total students, placement rate, branch-wise placement rate, gender-wise placement rate, and internship-wise placement rate.

![Placement Overview Dashboard](images/page1_placement_overview.png)

### Page 2 — Detailed Analysis

This page compares academic performance, aptitude, programming skills, communication skills, attendance, and package outcomes by placement status.

![Detailed Analysis Dashboard](images/page2_detailed_analysis.png)





# Student Placement Analytics System

An end-to-end data analytics project focused on analyzing student placement outcomes, identifying factors related to placement, and building an interactive dashboard for insights.

The project follows a practical industry-style workflow:

**Raw Data → Investigation → Cleaning → EDA → Dashboard → Insights**

---

## Project Overview

Student placement data can contain missing values, inconsistent categories, invalid numerical values, duplicate records, and different date formats.

The goal of this project is to take a messy student placement dataset, clean and analyze it using Python and Pandas, and finally build an interactive Power BI dashboard to understand placement outcomes.

The project focuses on questions such as:

- How many students were placed?
- What is the overall placement rate?
- Which branches have better placement outcomes?
- Does internship experience relate to placement?
- How does academic performance compare between placed and non-placed students?
- How do programming, communication, and aptitude skills relate to placement?
- What are the package trends among placed students?

---

## Project Objectives

- Investigate the quality of raw student placement data.
- Identify missing, inconsistent, duplicate, and invalid data.
- Clean and prepare the dataset using Python and Pandas.
- Perform exploratory data analysis (EDA).
- Identify meaningful placement-related patterns.
- Build an interactive Power BI dashboard.
- Present the final findings in a simple and understandable way.

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- **Power BI**
- **Git & GitHub**

---

## Project Structure

```text
Student-Placement-Analytics/
│
├── data/
│   ├── raw/
│   │   └── original_student_data.csv
│   │
│   └── processed/
│       └── student_placement_cleaned.csv
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   └── 02_EDA.ipynb
│
├── powerbi/
│   └── Student_Placement_Analytics.pbix
│
├── README.md
└── .gitignore