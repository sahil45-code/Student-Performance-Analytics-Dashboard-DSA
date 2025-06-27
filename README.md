# 🎓 Student Performance Analytics Dashboard

## 📁 Project Overview

This project is a part of the **RISE Internship - Data Science & Analytics Program** by Jamizan Skills. The goal is to design an **analytics dashboard** to identify at-risk students and support proactive academic interventions.

## 🧠 Problem Statement

Educational institutions often struggle to identify students who are at risk of failing or dropping out. This project seeks to deliver early-warning insights by analyzing patterns in student academic data.

## 🎯 Objective

To analyze student performance data—including marks, attendance, and login activity—to identify trends and highlight students who may require academic support.

## 📋 Requirements

The project meets the following criteria:

- ✅ Dataset includes:
  - Marks/grades
  - Attendance records
  - Platform login frequency
- ✅ Analytical processes:
  - Calculated averages and performance scores
  - Evaluated correlation between absenteeism and academic performance
  - Identified top-performing vs. struggling students
- ✅ Visualizations:
  - Bar charts of average marks per student
  - Heatmaps showing correlation between different variables
  - Comparison charts of attendance vs performance

## 🧾 Dataset Structure

| Column Name | Description                        |
|-------------|------------------------------------|
| Student_ID  | Unique ID of each student          |
| Marks       | Student's academic performance     |
| Attendance  | Attendance percentage              |
| Logins      | Number of platform logins          |

## ⚙️ Technologies Used

- Python 🐍
- Pandas 📊
- Matplotlib 📈
- Seaborn 🎨
- Jupyter Notebook 📒

## 📊 Features Implemented

1. **Data Preprocessing**
   - Handled missing/null values
   - Normalized or scaled variables where needed

2. **Performance Analysis**
   - Calculated averages, correlations
   - Derived absenteeism impact on performance

3. **Visualization Dashboard**
   - Highlighted high vs low performers
   - Used heatmaps to show variable correlations
   - Bar graphs for comparative analysis

4. **Insights**
   - Clearly identified students at risk of poor performance
   - Highlighted potential relationships between login activity and academic success

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-dashboard.git
   cd student-performance-dashboard

Install required libraries:
```bash
pip install pandas matplotlib seaborn

Run the Jupyter Notebook:
```bash
jupyter notebook "Student Performance Analytics Dashboard.ipynb"

📌 Expected Outcome:-
An interactive dashboard-style notebook that:
Highlights academic trends
Provides visual support for identifying at-risk students
Helps institutions take early action

📦 Future Enhancements:-
Integrate with real-time school/college management systems
Add predictive modeling to forecast dropout risk
Build an interactive dashboard using Plotly or Dash

