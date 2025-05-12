# 🎓 Student Enrollment and Performance Dashboard using Tableau

This project presents an **interactive Tableau dashboard** that explores **student enrollment patterns and academic performance** across various demographic groups. Built using a subset of the **Open University Learning Analytics Dataset (OULAD)** and extended with additional metrics via Excel, the dashboard provides educators, administrators, and analysts with valuable insights into how different factors influence student outcomes.

![Tableau](https://img.shields.io/badge/tool-tableau-blue?logo=tableau)
![Excel](https://img.shields.io/badge/tool-excel-green?logo=microsoft-excel)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📊 Project Overview

This dashboard focuses on:

- Analyzing **average GPA** by gender, region, and other demographics
- Tracking **student enrollment trends** across modules
- Highlighting potential disparities in academic performance
- Empowering data-driven decisions in education

---

## 📁 Dataset

- **Source**: Refined subset of the [Open University Learning Analytics Dataset (OULAD)](https://analyse.kmi.open.ac.uk/open-dataset)
- **Format**: Excel (`.xlsx`)
- **Transformations**: Cleaned and enhanced using Excel to calculate **average GPA per student**, a metric not originally included in OULAD.

---

## 🧾 Dataset Fields

| Field Name          | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `id_student`        | Unique identifier for each student                                          |
| `gender`            | Gender of the student (`Male`, `Female`)                                   |
| `region`            | Student's region of residence                                               |
| `highest_education` | Highest qualification at registration                                       |
| `age_band`          | Age group (`0-35`, `35-55`, `55<=`)                                         |
| `disability`        | Whether the student has a disability (`Y`, `N`)                             |
| `code_module`       | Course code                                                                 |
| `code_presentation` | Academic term/session (e.g., `2013J`)                                       |
| `num_of_attempts`   | Number of attempts for a module                                             |
| `final_result`      | Result (`Pass`, `Fail`, `Withdrawn`, `Distinction`)                         |
| `average_gpa`       | **Custom field**: Average GPA based on module performance                   |

---

## 🛠 Tools Used

- **Excel** – for data preparation and GPA calculations
- **Tableau** – for interactive dashboard creation and visual analytics

---

## 🚀 Dashboard Link

📊 [**Student Enrollment and Performance Dashboard (Tableau Public)**](https://public.tableau.com/app/profile/dustin.sherratt/viz/ExtendedCase2_17442367562910/AverageGPA#1)

---

## 🧭 How to Use the Dashboard

- Use the **filters** (gender, age, region, course) on the right to explore data from different perspectives.
- **Hover over visual elements** (bars, segments) for detailed tooltips.
- **Click on charts or segments** to **dynamically filter** other visual components in the dashboard.
- To reset, use the "Reset" or "Clear Selections" options if provided.

---

## 🖥️ Run Locally in Tableau Desktop

To open and interact with the dashboard locally:

1. Clone or download this repository.
2. Open either of the following Tableau workbooks:
   - `workbook/student_dashboard.twb`
   - `workbook/student_dashboard.twbx` *(self-contained version)*
3. If using `.twb`, ensure the data source is correctly linked:
   - Path: `data/student_avg_gpa.xlsx`
   - Keep folder structure consistent to avoid broken links.

> ✅ `.twbx` file includes the data bundled — no need to reconnect.

---

## 🗂️ Folder Structure

```bash
/student-performance-dashboard
│
├── data/
│   └── student_avg_gpa.xlsx
│
├── workbook/
│   └── student_dashboard.twb
│   └── student_dashboard.twbx
│
├──
