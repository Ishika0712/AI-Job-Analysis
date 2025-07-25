# 🧠 AI Job Market Analysis using SQL

This project explores and analyzes over **15,000 AI job postings** using **SQL** by transforming raw, unstructured data into a clean, normalized relational database. It uncovers key job market trends including in-demand skills, salary comparisons, remote work distribution, and hiring patterns by companies and industries.

---

## 📌 Project Objective

- Build a normalized relational schema from a messy AI job dataset using 1NF, 2NF, and 3NF principles.
- Perform SQL-based data analysis to derive decision-ready insights on:
  - Skill demand
  - Salary ranges (Local, USD, INR)
  - Remote vs. on-site roles
  - Hiring trends by company, industry, location, and experience level

---

## 🗃️ Dataset Overview

- **Total Records:** 15,000 
- **Columns Included:** Job Title, Company, Industry, Skills, Experience Level, Salary (in multiple currencies), Location, Employment Type, Education, etc.

---

## 🧩 Data Modeling

The raw dataset was normalized into 7+ linked tables:
- `Jobs`
- `Companies`
- `Skills`
- `JobSkills` (many-to-many relation)
- `Industries`
- `Education`
- `JobTitles`

An **ER model** was created to map relationships and ensure data integrity and scalability.

---

## 🔍 Key Insights

- **Top Skills in Demand:** Python, SQL, TensorFlow, Kubernetes  
- **Highest Paying Roles (in INR):** Data Engineer, AI Research Scientist  
- **Remote-Friendly Industries:** Government and Finance  
- **Top Hiring Countries:** Switzerland, China, Ireland, India, USA  
- **Currency Insights:** Jobs paid in GBP and EUR convert to higher INR values than JPY or AUD  

---

## 🛠️ Technologies Used

- **Database:** MySQL  
- **Querying:** SQL (Joins, Aggregations, Filtering, Grouping)  
- **Visualization:** PowerPoint (for presentation/report)  
- **Tools:** Excel (initial cleaning), ERD tools for schema design  

---


