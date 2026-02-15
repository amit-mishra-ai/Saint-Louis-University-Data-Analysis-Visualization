# 🎓 Admissions Analytics Dashboard (Looker Studio + PostgreSQL)

An end-to-end data analytics project that builds a cloud-connected dashboard to analyze university application data and support data-driven admissions decisions.

This project was developed as part of an analytics internship and demonstrates the full workflow from **database setup → data connection → EDA → dashboard creation → insight generation.**

---

## 📌 Project Overview

This project analyzes **6,894 university applications** to uncover patterns in:

- Application trends over time  
- Geographic distribution of applicants  
- Program demand and intake preferences  
- Recruitment source effectiveness  
- International vs domestic student distribution  

The final output is an **interactive Looker Studio dashboard** connected to a **Supabase PostgreSQL database**.

---

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| PostgreSQL | Data storage |
| Supabase | Cloud database hosting |
| Looker Studio | Dashboard & visualization |
| Python (Pandas, Matplotlib, Seaborn) | Exploratory Data Analysis |
| Jupyter Notebook | EDA report |

---

## 🗄️ Data Pipeline Architecture

**Local PostgreSQL → Supabase PostgreSQL → Looker Studio Dashboard**

### Steps Performed

1. Set up local PostgreSQL environment.  
2. Created Supabase cloud database.  
3. Created schema and `applicants` table.  
4. Imported applicant dataset into Supabase.  
5. Connected Looker Studio to PostgreSQL.  
6. Built interactive dashboard using live connection.  

This simulates a real-world cloud analytics workflow.

---

## 📊 Looker Studio Dashboard

### 🔗 Dashboard Link
_Add your Looker Studio link here_

### Dashboard Features

#### KPI Overview
- Total Applicants  
- Pending Applications  
- Decision Release %  
- International Students %  
- Countries Represented  

#### Visualizations
- Applications by Country (Top Markets)
- Geographic Distribution Map
- Program Demand Analysis
- Intake Distribution
- Application Source Distribution
- Global Graduate vs Domestic Students
- Top Cities Table

#### Interactivity
Users can filter by:
- Country
- Major / Program
- Intake
- Application Source
- Student Type

---

## 🔍 Exploratory Data Analysis (EDA)

The project includes a full EDA notebook:

📄 **EDA Report:** `EDA_report.ipynb`

### Key EDA Steps

- Data cleaning and validation  
- Handling inconsistent country values  
- Understanding distributions and categorical variables  
- Identifying trends and anomalies  
- Preparing features for dashboard metrics  

### Example Questions Explored

- Which countries generate the most applications?  
- Which programs are most popular?  
- What intake receives the most applications?  
- Are applications concentrated in specific cities?  
- Which recruitment sources dominate?  

---

## 💡 Key Insights

### 🌍 Strong Geographic Concentration
- Majority of applications originate from a small number of countries.  
- Indicates focused recruitment success in specific regions.

### 💻 High Demand for Tech Programs
- IT, Computer Science, and Cybersecurity dominate applications.  
- Suggests strong demand for technology-related programs.

### 🍂 Fall Intake Dominance
- Most applications target the Fall intake.  
- Shows clear seasonal behavior.

### 📢 Source Channel Dependency
- A large proportion of applications come from a single source.  
- Indicates potential marketing dependency risk.

### 🌎 Majority International Applicants
- Most applicants are international students.  
- Demonstrates strong global recruitment reach.

---

## 📁 Dashboard Link:
https://lookerstudio.google.com/reporting/b0172cc7-6b2c-4889-b8fc-b60ab442de13

## Snapshot 
<img width="825" height="813" alt="Screenshot 2026-02-15 100715" src="https://github.com/user-attachments/assets/e1168138-541b-4398-b45f-6f206fd769f8" />
