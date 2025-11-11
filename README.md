# LA Crime Analytics — Data Exploration with Python  

A Python-based exploratory analysis uncovering **crime patterns, victim demographics, and temporal trends** in **Los Angeles (2020–2023)**.  
Built using **Pandas**, **Matplotlib**, and **Seaborn**, the project transforms raw city crime data into visual insights that support **data-driven policing and community safety strategies**.

---

## Dashboard / Notebook  
- **Jupyter Notebook (view/download):** _https://drive.google.com/file/d/your-notebook-link/view?usp=drive_link_  

![Image](https://github.com/user-attachments/assets/your-la-crime-image-id)

---

## Table of Contents  
- [About the Project](#about-the-project)  
- [Dataset](#dataset)  
- [Business Questions](#business-questions)  
- [Features & KPIs](#features--kpis)  
- [Steps Followed](#steps-followed)  
- [Outcome](#outcome)  
- [Contact](#contact)

---

## About the Project  
**Goal:** Perform **exploratory data analysis (EDA)** on Los Angeles crime records to identify **patterns over time**, **victim demographics**, and **crime type distribution**, providing actionable insights for law enforcement and civic safety.  
**Tech:** Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook.  
**Dataset Source:** **Los Angeles Open Data Portal (Crime Data 2020-Present)**.

---

## Dataset  
Key columns:  
- `Date Occurred`, `Time Occurred`, `Crime Code Description`, `Victim Age`, `Victim Sex`, `Victim Descent`, `Premise Description`, `Status`, `Area Name`.  

> The dataset covers over **750,000+ incidents** from **2020 to mid-2023**, updated monthly by the Los Angeles Police Department (LAPD).

---

## Business Questions  
1. How have **crime counts** changed over time (month/year trends)?  
2. What are the **top 20 most frequent crimes** reported in Los Angeles?  
3. How does **victim age distribution** vary across different crime types?  
4. Which **areas** report the **highest number of incidents**?  
5. What is the **average time taken** to report a crime after it occurs?  
6. Are there visible **spikes in crime** during certain **times of day or days of the week**?  
7. How can these insights assist **policymakers and law enforcement** in proactive safety measures?

---

## Features & KPIs  
- **Crime Over Time Line Chart:** Monthly aggregation of total incidents (2020–2023).  
- **Victim Age Histogram:** Distribution of victim ages with density overlay.  
- **Top 20 Crimes Bar Chart:** Frequency of most common crime categories.  
- **Geographic Trends:** Area-wise incident counts visualized for hotspot identification.  
- **Temporal Patterns:** Hour-of-day vs day-of-week matrix to detect peak reporting times.  
- **Feature Analysis:** Relationship between **victim demographics** and **crime severity**.  
- **Reporting Delay Metric:** Average time gap between crime occurrence and report date.  
- **Clean Data Pipeline:** Null handling, type conversion, and datetime extraction for accurate analysis.  

---

## Steps Followed  

**1) Data Import & Preparation**  
- Imported raw dataset using **Pandas** and inspected key data types.  
- Cleaned missing or invalid values in **Victim Age** and **Crime Description** columns.  
- Converted `Date Occurred` and `Time Occurred` into proper **datetime format** for temporal grouping.  

**2) Exploratory Data Analysis (EDA)**  
- Grouped and visualized total crimes by **month/year** using `groupby()` and `plot()`.  
- Created **bar charts** for the **top 20 crime categories**.  
- Built **histograms** to analyze victim age and demographic patterns.  

**3) Feature Understanding & Analysis**  
- Segmented data by **crime type**, **area**, and **time of occurrence**.  
- Derived new columns for **hour of crime**, **day of week**, and **report delay (in hours)**.  
- Examined **temporal spikes** using line and heatmap visuals.  

**4) Visualization & Insights**  
- Used **Matplotlib** and **Seaborn** for clean, consistent visual styling.  
- Generated multi-panel layout:  
  - Crime Over Time (Line Chart)  
  - Victim Age Distribution (Histogram)  
  - Top 20 Crimes (Horizontal Bars)  
- Applied **crime-specific color palette** for readability and storytelling.  

**5) Interpretation & Recommendations**  
- Identified notable increase in **vehicle theft** and **battery-related incidents** post-pandemic.  
- Highlighted age 25-40 as the **most affected group** in majority of cases.  
- Suggested optimizing patrol schedules around **evening hours (6 PM–10 PM)** when activity peaks.  

---

## Outcome  
A research-style **Python notebook** that provides leadership and city analysts with a **data-driven view of Los Angeles crime patterns**.  
The project uncovers actionable trends in **crime frequency**, **victim demographics**, and **reporting behavior**, empowering decision-makers to enhance **public safety, resource allocation, and policy planning**.

---

