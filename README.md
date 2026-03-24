# deeptech-foundation-journey
Documenting my 4-week DeepTech Foundation journey covering data analysis, SQL, visualization, Python, machine learning, and computer vision. Includes weekly notes, assignments, quizzes, and reflections.
# 🚀 DeepTech Foundation Journey

## 📌 Overview
This repository documents my **4-week DeepTech Foundation program**, covering:

- Data Analysis & Visualization  
- Python for Data Analysis  
- SQL & Database Management  
- Data Science & Machine Learning  
- Computer Vision  

Each week includes:
- Learning objectives  
- Applied assignments  
- Solutions  
- Reflections  
- ✅ Quiz completion  

---

# 🧭 Table of Contents

- [Week 1](#-week-1--data--python-foundations)
  - [Course 1: Data & Visualization](#-course-1-introduction-to-data--visualization)
  - [Course 2: Python for Data Analysis](#-course-2-introduction-to-python-for-data-analysis--visualization)

- [Week 2](#-week-2--sql-data-science--computer-vision)
  - [Course 1: SQL](#-course-1-introduction-to-sql)
  - [Course 2: Data Science & Machine Learning](#-course-2-data-science--machine-learning-foundations)
  - [Course 3: Computer Vision](#-course-3-introduction-to-computer-vision)

- [Key Takeaways](#-key-takeaways)
- [Overall Reflection](#-overall-reflection)

---

# 📅 Week 1 – Data & Python Foundations

## 📌 Overview
Focused on **data fundamentals, visualization, and Python basics**.  
✅ Quiz completed.

---

## 📊 Course 1: Introduction to Data & Visualization

### 🎯 Learning Objectives
- Explain data and data analysis  
- Understand visualization principles  
- Use visualization tools  
- Interpret statistical summaries  
- Explain correlations and trends  

---

### 📝 Assignment: Visualization Tools

#### Tools Reviewed
- Power BI  
- Tableau  
- Plotly  
- Google Data Studio  
- Microsoft Excel  

#### ✅ Best Tool
**Tableau** — due to flexibility, advanced visuals, and ease of use.  
**Power BI** is a strong alternative.

---

### ❌ When NOT to Visualize
- Small datasets  
- Sensitive data  
- When tables are clearer  
- When exact values are needed  
- When visualization adds no value  

---

### 📊 Correlation

- **Age vs Height:** Positive (during growth)  
- **Salary vs Years:** Positive  

---

## 🐍 Course 2: Python for Data Analysis & Visualization

### 🎯 Learning Objectives
- Install Python (Anaconda)  
- Work with data types  
- Use loops  
- Write functions  
- Identify visualization tools & packages  

---

### 🧰 Python Tools
- Jupyter Notebook  
- Jupyter Lab  
- VS Code  
- Spyder  
- Google Colab  

---

### 📦 Visualization Packages

#### Matplotlib
- Static, customizable plots  

#### Seaborn
- Statistical, beautiful plots  

#### Plotly
- Interactive dashboards  

---

# 📅 Week 2 – SQL, Data Science & Computer Vision

## 📌 Overview
Focused on **SQL, Data Science lifecycle, ML concepts, and Computer Vision**.  
✅ Quizzes completed.

---

## 🗄️ Course 1: Introduction to SQL

### 🎯 Learning Objectives
- Use SELECT, WHERE, GROUP BY, JOIN  
- Filter and group data  
- Solve real-world SQL problems  
- Understand database structure  
- Use primary & foreign keys  

---

### 📝 Assignment: Healthcare Database

#### 1. Patients in Abuja & Plateau
```sql
SELECT *
FROM Patients
WHERE State IN ('Fct Abuja', 'Plateau');
