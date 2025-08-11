# 🎓 Student Survey Data Analysis – Power BI

## 📌 Overview
This project is a **Power BI dashboard** built to analyze student survey data.  
It aims to identify trends, measure student satisfaction, and gain insights into academic, social, and facility-related experiences.  
The dashboard supports educational institutions in making data-driven decisions to improve student life and learning outcomes.

---

## 📂 Data Source
- **Source Type:** CSV / Excel / Google Forms Export
- **Dataset Name:** `student_survey_data`
- **Date Range:** *(e.g., Academic Year 2024 – 2025)*
- **Data Size:** *(Number of responses)*

**Key Columns:**
| Column Name                | Description                                        | Example Value           |
|----------------------------|----------------------------------------------------|-------------------------|
| Student ID                 | Unique identifier for each student                 | STU1023                 |
| Name                       | Name of the student (if collected)                 | John Doe                |
| Age                        | Age of the student                                 | 21                      |
| Gender                     | Gender of the student                              | Female                  |
| Course/Program             | Program enrolled                                   | B.Tech Computer Science |
| Year of Study              | Current academic year                              | 3rd Year                |
| Satisfaction Level (1-5)   | Overall satisfaction rating                        | 4                       |
| Teaching Quality (1-5)     | Rating for teaching and learning quality           | 5                       |
| Facility Satisfaction (1-5)| Rating for infrastructure and facilities           | 3                       |
| Extracurricular Activities | Participation status                               | Yes                     |
| Internet Access            | Availability of internet for academic purposes    | Yes                     |
| Suggestions                | Open-ended feedback from students                  | More workshops          |

---

## 📊 Dashboard Features
- **Overall Satisfaction Score**
- **Academic & Teaching Quality Ratings**
- **Infrastructure & Facility Ratings**
- **Participation in Extracurricular Activities**
- **Demographic Breakdown (Age, Gender, Course)**
- **Trend Analysis by Academic Year**
- **Word Cloud of Student Suggestions**

---

## 🛠 Data Transformation in Power BI
- Removed duplicate survey entries
- Converted categorical responses to numeric values where applicable
- Cleaned text feedback for keyword analysis
- Created calculated columns:
  - `Average Satisfaction = (Teaching Quality + Facility Satisfaction) / 2`
- Added DAX measures:
  - Total Students
  - Average Ratings
  - Participation Percentage

---

## 📌 How to Use
1. **Open Power BI Desktop**
2. Go to **File → Open** and select `student_survey_dashboard.pbix`
3. Update the dataset path in **Transform Data** if needed
4. Click **Refresh** to load the latest survey data

---
