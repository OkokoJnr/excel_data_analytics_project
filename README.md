Got it ✅
Here’s a **detailed `README.md` file** you can place at the root of your project folder. It explains the course context, project structure, and how to reproduce everything step by step.

---

# 📊 Excel for Data Analytics Projects

This repository recreates two end-to-end projects from **Luke Barousse’s Excel for Data Analytics** course. It is designed as a self-contained portfolio project to practise Excel data analysis skills on real-world datasets.

---

## 📂 Project Structure

```
excel_data_analytics_project/
│
├── 0_Resources/
│   ├── Problems/               # Practice workbooks from the course
│   ├── Images/                 # Screenshots & exported visuals
│   └── Data/                   # Raw datasets (.xlsx, .csv)
│
├── 1_Salary_Dashboard/         # Project 1: Salary Dashboard
│   ├── Salary_Dashboard.xlsx   # Final dashboard file
│   ├── Notes.md                # Step-by-step build notes
│   └── Exports/                # Exported dashboard charts
│
├── 2_Job_Skills_Analysis/      # Project 2: Job Skills & Salary Analysis
│   ├── Job_Skills_Analysis.xlsx
│   ├── Notes.md
│   └── Exports/
│
└── README.md                   # High-level documentation
```

---

## 📘 Project 1: Salary Dashboard

**Objective**
Create an interactive dashboard to explore salary data for data-related jobs across job titles, countries, and work schedules.

**Key Excel Skills**

* Charts (Bar chart, Map chart)
* Array formulas (`MEDIAN`, `IF`, `FILTER`)
* Data validation (dropdown filters)

**Dataset**

* 2023 dataset of job titles, salaries, countries, and job types.

**Dashboard Features**

1. **Median Salary by Job Title** – Bar chart sorted descending for clarity.
2. **Country Median Salaries** – Excel Map chart visualising salary levels by geography.
3. **Job Schedule Type** – Filterable list of schedule types using `FILTER()`.
4. **User Filters** – Dropdown lists for job title, country, and type to interact with the data.

**Insights**

* Senior/engineering roles consistently show higher pay than analyst roles.
* Salary levels vary significantly by country.
* Clean validation improves dashboard usability.

---

## 📘 Project 2: Job Skills & Salary Analysis

**Objective**
Analyse the impact of technical skills on salaries and identify top-paying skills in the data job market.

**Key Excel Skills**

* Power Query (Extract, Transform, Load)
* Power Pivot (Data models & relationships)
* DAX formulas (custom measures)
* PivotTables & PivotCharts (salary + skill analysis)

**Dataset**

* `data_salary_all.xlsx` containing:

  * `data_jobs_all` (job details & salaries)
  * `data_job_skills` (skills by job ID)

**Analytical Questions**

1. Do more skills = better pay?
2. What are salaries across regions (US vs Non-US)?
3. What are the top skills of data professionals?
4. What’s the pay for the top 10 skills?

**Findings**

* More skills are linked to higher salaries (esp. for Data Scientists/Engineers).
* US salaries remain higher than non-US equivalents, particularly in tech roles.
* SQL, Python, AWS, and Azure dominate as top skills.
* Python, Oracle, and SQL are tied to the highest-paying jobs.

---

## 🚀 How to Use

1. Clone or download this project folder.
2. Place datasets in `0_Resources/Data/`.
3. Open Excel and rebuild dashboards step by step:

   * Start with **Project 1: Salary Dashboard** for formulas & charting.
   * Move to **Project 2: Job Skills Analysis** for Power Query, Pivot, and DAX practice.
4. Export visuals to `Exports/` for reporting.
5. Document your steps in `Notes.md` so you track your learning process.

---

## 🎯 Learning Outcomes

* Master core Excel data analysis features (formulas, charts, tables).
* Build interactive dashboards to explore real-world datasets.
* Apply Power Query and Power Pivot for advanced analysis.
* Use DAX for custom calculations.
* Strengthen portfolio with real, project-based Excel work.

---

## 📌 Credits

This project is based on **Luke Barousse’s Excel for Data Analytics Course**.

* [Course Website](https://lukebarousse.com/excel)
* [YouTube Playlist](https://youtu.be/pCJ15nGFgVg)

