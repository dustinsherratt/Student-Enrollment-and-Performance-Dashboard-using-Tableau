# Student Enrollment and Performance Dashboard using Tableau

This project presents an **interactive Tableau dashboard** that explores **student enrollment patterns and academic performance** across various demographic groups. Built using a subset of the **Open University Learning Analytics Dataset (OULAD)** and extended with additional metrics via Excel, the dashboard provides educators, administrators, and analysts with valuable insights into how different factors influence student outcomes.

## 📊 Project Overview

The dashboard focuses on:
- Analyzing **average GPA** by gender, region, and other demographics
- Tracking **student enrollment trends** across different modules
- Highlighting potential disparities in academic performance

It allows users to interact with filters and visualizations to identify at-risk groups, monitor performance patterns, and explore how demographic variables correlate with academic success.

## 📁 Dataset

- **Source**: A refined subset of the [Open University Learning Analytics Dataset (OULAD)](https://analyse.kmi.open.ac.uk/open_dataset)
- **Format**: Excel (`.xlsx`)
- **Modifications**: Cleaned and transformed in Excel to calculate **average GPA per student**, which is not originally present in OULAD.

## 🧾 Dataset Fields

The dataset (`OULA.xlsx`) includes the following fields:

| Field Name          | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `id_student`        | Unique identifier for each student                                          |
| `gender`            | Gender of the student (`Male`, `Female`)                                   |
| `region`            | Student's region of residence                                               |
| `highest_education` | Highest qualification held by the student at registration time             |
| `age_band`          | Age group of the student (`0-35`, `35-55`, `55<=`)                          |
| `disability`        | Whether the student has declared a disability (`Y` or `N`)                  |
| `code_module`       | Course code for the module the student is enrolled in                      |
| `code_presentation` | The term/session in which the module was presented (e.g., `2013J`)          |
| `num_of_attempts`   | Number of times the student has attempted the module                        |
| `final_result`      | Final result in the module (`Pass`, `Fail`, `Withdrawn`, `Distinction`)     |
| `average_gpa`       | **Custom field**: Calculated average GPA for each student based on grades   |

## 🛠 Tools Used

- **Excel** – for data preparation and GPA calculations
- **Tableau** – for creating the dashboard and visual analysis

## 🚀 Dashboard Link

View the full dashboard on Tableau Public:  
🔗 [Student Enrollment and Performance Dashboard](https://public.tableau.com/app/profile/dustin.sherratt/viz/ExtendedCase2_17442367562910/AverageGPA#1)

## 🧭 How to Use the Dashboard

- Use the **filters on the right** to explore GPA by gender, region, and course code.
- Hover over charts to view **tooltips** with detailed metrics.
- Click on bars or segments to **dynamically filter** other views.
- Reset filters by clicking the **"Reset" or "Clear Selections"** button (if available).

## 🖥️ Run Locally in Tableau Desktop

To explore or edit this dashboard locally:

1. Clone or download this repository.
2. Open the Tableau workbook file:
