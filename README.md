# 🌍 Global Terrorism Data Analysis (EDA)

![R](https://img.shields.io/badge/R-4.x-blue)
![EDA](https://img.shields.io/badge/Analysis-Exploratory%20Data%20Analysis-orange)
![Data](https://img.shields.io/badge/Dataset-Global%20Terrorism%20Database-purple)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

**Author:** Anurag Surve
**Domain:** Data Analysis · Public Policy · Security Analytics

---

## 🔍 Project Snapshot (TL;DR)

This project performs **exploratory data analysis (EDA)** on the **Global Terrorism Database (GTD)** to uncover long-term trends, geographic patterns, attack characteristics, and human impact of terrorist incidents worldwide.

The focus is on:

* Understanding **where, when, and how** attacks occur
* Identifying **high-risk regions and time periods**
* Examining **attack types, targets, and casualties**
* Practicing rigorous data cleaning and analytical reasoning

---

## 🎯 Objectives

* Explore global and regional terrorism trends over time
* Identify countries and regions most affected by terrorism
* Analyze attack methods, targets, and outcomes
* Examine casualty patterns (killed vs wounded)
* Produce clear, interpretable visual insights for policy discussion

---

## 📊 Dataset Overview

**Source:** Global Terrorism Database (GTD)

**Coverage**

* Worldwide incidents
* Multiple decades of data
* Thousands of recorded terrorist events

**Key Variables**

* `iyear`, `imonth`, `iday` – incident date
* `country_txt`, `region_txt`, `city` – location
* `attacktype1_txt` – attack method
* `targtype1_txt` – target type
* `nkill`, `nwound` – casualties
* `success` – attack outcome

Two versions are used:

* **Raw dataset** (original GTD)
* **Cleaned dataset** (processed for analysis)

---

## 🧹 Data Cleaning & Preparation

Major preprocessing steps:

* Removed or handled missing and ambiguous values
* Standardized categorical variables
* Filtered unrealistic or incomplete records
* Created derived features for temporal and regional analysis

The cleaned dataset is stored separately to ensure **reproducibility and clarity**.

---

## 🔎 Exploratory Analysis Highlights

Key analyses include:

* **Temporal trends** in terrorist incidents by year
* **Geographic concentration** of attacks by region and country
* **Attack type distribution** (bombings, armed assaults, etc.)
* **Target analysis** (civilians, military, government, infrastructure)
* **Casualty analysis** focusing on fatalities and injuries

The EDA emphasizes **interpretation over prediction**, ensuring results remain meaningful and responsible.

---

## 📈 Key Insights

* Terrorism incidents are **highly concentrated** in specific regions
* Certain attack types dominate across time periods
* Civilian and government targets account for a large share of incidents
* Casualty distributions are **heavily right-skewed**, with few extreme events causing disproportionate harm
* Trends shift significantly across decades, reflecting geopolitical changes

---

## 🛠️ Tech Stack

* **R**
* **RMarkdown**
* Libraries:

  * `tidyverse`
  * `ggplot2`
  * `dplyr`
  * `readxl`

---

## 🚀 How to Run

1. Open `EDA Global Terrorism DATA.Rmd` in RStudio
2. Ensure cleaned dataset path is correctly set
3. Knit the file to:

   * **HTML** (recommended for interactivity)
   * **PDF** (for academic submission)

---

## ⚠️ Ethical Considerations

* Results are **descriptive**, not predictive
* No profiling or individual-level inference
* Emphasis on **data context, uncertainty, and responsible interpretation**

---

## 📌 Limitations & Future Work

* Missing data in early years limits trend continuity
* No causal inference performed
* Future extensions:

  * Regional deep dives
  * Time-series change-point analysis
  * Integration with socioeconomic indicators

---

## 💼 Why This Project Matters

This project demonstrates:

* Strong **EDA fundamentals**
* Careful handling of **sensitive real-world data**
* Ability to extract **policy-relevant insights**
* Clear analytical storytelling using visualizations

---

## 📬 Contact

**Anurag Surve**
LinkedIn: [www.linkedin.com/in/anurag-surve-b37291265](http://www.linkedin.com/in/anurag-surve-b37291265)
