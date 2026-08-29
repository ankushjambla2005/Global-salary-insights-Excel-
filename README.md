# 📊 Tech Job Market & Salary Analytics Dashboard

An interactive, dark-themed **Microsoft Excel Dashboard** built to analyze global tech job market trends, salary distributions, schedule preferences, and high-demand skill sets across **29,000+ job postings**.

![Dashboard Preview](docs/dashboard_preview.png)

---

## 📌 Executive Summary

Understanding salary trends and skill demands in the tech sector requires granular data analysis across multiple dimensions— job titles, geographic regions, schedule types, and posting timelines. 

This project transforms raw global job market data into an interactive visual reporting tool designed to evaluate:
* Which tech skills command the highest median compensation vs. job volume.
* Salary breakdown by work schedule (Full-time, Contractor, Part-time, Internship).
* Monthly job posting velocity alongside salary fluctuation.
* Geographic and role-based variance using dynamic cross-filtering.

---

## 🛠️ Excel Skills & Features Demonstrated

This project highlights advanced core Excel capabilities for data analysis, modeling, and executive reporting:

* **Data Preparation & Structuring:** Standardized raw dataset fields, cleaned missing entries, and structured data for dynamic Pivot consumption.
* **Pivot Tables & Multi-Dimensional Aggregation:** Built modular Pivot Tables driving dynamic summaries for skills, monthly timelines, schedule metrics, and geographic slices.
* **Interactive Slicer Dashboard Integration:** Connected unified **Slicers** (`job_title_short`, `job_country`,`prefferd_schedule`) and a **Timeline Slicer** (`job_posted_date`) across multiple Pivot Charts simultaneously.
* **Dual-Axis Combination Visuals:** Designed combination charts merging **Column/Bar charts** (Job Volume) with **Line charts** (Median Yearly Salary) on secondary axes for dual-metric evaluation.
* **Custom UX/UI Dashboard Layout:** Formatted a modern, dark-mode dashboard UI emphasizing visual hierarchy, readable contrast, cleanly aligned visual cards, and zero screen clutter.

---

## 💡 Key Analytical Insights & Data Observations

### 1. High-Paying vs. High-Volume Skills
* Core skills like **Python** ($136,100 median salary | 17,451 jobs) and **SQL** ($130,000 median salary | 18,243 jobs) represent the highest volume demand across global job postings.
* Cloud and data engineering tools like **Snowflake** ($145,000) and **Spark** ($147,500) yield higher median pay tiers while maintaining strong job counts.

### 2. Work Schedule Compensation Dynamics
* **Contractor** roles show significantly higher top-line compensation figures ($1,144,000 median in sample distributions) compared to traditional **Full-Time** employment ($120,000 median across 24,500+ records), reflecting specialized short-term advisory rates and varying payment structures.

### 3. Data Sparsity & Sample Size Impact *(Analytical Case Study)*
* **Macro View ($N = 29,040$):** When viewing global data across major regions, monthly trends show continuous, stable 12-month distributions with consistent job counts ($\approx 1,700–3,100$ jobs/month).
* **Micro/Filtered View ($N \le 5$):** Filtering down to niche combinations (e.g., *Software Engineer* roles in *Lebanon* or *Machine Learning Engineer* in *Bangladesh*) reduces sample size down to 1–2 postings.
* **Business Takeaway:** This variance illustrates a critical real-world analytical principle: **median values derived from small sample sizes ($N < 5$) reflect individual data points rather than statistically reliable market benchmarks.**

---
