# HR-Analysis

# 📊 HR Analytics Dashboard — Power BI

A comprehensive and dynamic **HR Dashboard** built in **Power BI** to provide deep insights into employee data, organizational structure, compensation trends, and diversity metrics. This dashboard empowers HR professionals, analysts, and organizational leaders to make data-informed decisions related to human capital management.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Insights Provided](#insights-provided)
- [Data Modeling](#data-modeling)
- [Technology Stack](#technology-stack)
- [How to Use](#how-to-use)
- [Use Cases](#use-cases)
- [Screenshots](#screenshots)
- [License](#license)
- [Contact](#contact)

---

## 📘 Overview

This dashboard provides a centralized and visual representation of core human resource metrics across various dimensions such as:

- **Employee Headcount**
- **Salary Distribution**
- **Job Titles and Departments**
- **Gender and Age Demographics**
- **Education Level**
- **Leave Balances**

It includes interactive slicers and filters, enabling HR teams to perform real-time analysis and segmentation across multiple variables for decision-making, workforce planning, and reporting.

---
HR Analysis Dashborad
![Dashboard Image](https://github.com/user-attachments/assets/6c398a2c-0df6-4269-bf6b-a96a58e2e494)

## 🚀 Key Features

### 🧑‍💼 Employee Distribution
- **Bar chart** showing headcount across different job titles.
- Useful for identifying workforce concentration and gaps.

### 💰 Salary Overview
- Displays **minimum** and **maximum salaries** across the organization.
- **Line graph** visualizing the **sum of salary by job title** for trend analysis.

### 👨‍👩‍👧 Gender and Age Insights
- Stacked **histogram charts** representing employee **headcount by age bins** segmented by **gender**.
- Identifies trends in workforce aging and gender diversity.

### 📚 Education Levels
- Button slicers filtering employees by **highest qualification**: High School, Diploma, Bachelor's, Master's.

### 🧾 Leave Balance Analysis
- Leave balance categories grouped in bins (0, 10, 20, 30 days).
- Identifies trends in leave utilization and accumulation.

### 📊 Gender Split
- **Donut chart** for quick view of gender representation.
- Percentages and counts included for clarity.

---

## 🔍 Insights Provided

- Total workforce size (161 employees)
- Salary range: $29,000 to $85,000
- Male-to-female ratio: ~55% Male, ~45% Female
- Age group with the highest employee count: 30–35 years
- Job titles with the highest headcount: Packaging Associate, Production Worker, Sales Representative
- Highest-paying roles: Product Manager, Research Analyst

---

## 🧮 Data Modeling

The dashboard assumes the use of a **clean HR dataset** structured with the following fields:

| Column Name         | Description                                |
|---------------------|--------------------------------------------|
| Employee ID         | Unique identifier                          |
| Job Title           | Employee's job title                       |
| Salary              | Annual salary                              |
| Gender              | Male / Female                              |
| Age                 | Integer (used for binning)                 |
| Education           | Highest qualification                      |
| Leave Balance       | Number of remaining leave days             |

Data transformations and aggregations (e.g., binning, group by, sum) are done using **Power Query** and **DAX** formulas in Power BI.

---

## 🛠 Technology Stack

| Tool/Platform      | Purpose                                      |
|-------------------|----------------------------------------------|
| Power BI Desktop  | Data visualization and dashboard creation    |
| Power Query       | Data transformation and shaping              |
| DAX               | Measures and calculated fields               |
| Excel / CSV       | Data source format (assumed)                 |

---

## 📥 How to Use

1. **Clone or Download** the repository.
2. Open the `.pbix` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. If using your own dataset, replace or map the fields in **Power Query Editor**.
4. Refresh the visuals using the **Refresh** button.
5. Use slicers to filter insights by education level or leave balance.
6. Customize visual themes or fields as per your HR needs.

---

## 🧑‍💼 Use Cases

This dashboard is ideal for:

- HR Executives & Generalists
- People Analytics Teams
- Business Partners & Consultants
- Corporate Strategy Teams

### Practical Applications:
- Analyze gender representation for diversity initiatives
- Identify workforce concentration in departments
- Monitor high/low leave balance trends
- Track compensation distribution and pay equity
- Present quarterly or annual HR reports to stakeholders

---

## 🖼 Screenshots

> 📷 Example visuals include bar charts, line graphs, pie charts, and filter buttons for dynamic exploration.  
> *(See `Screenshot 2025-06-01 005030.png` in this repository)*

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.

---

## 👩‍💻 About Me — Rukayat Adebisi Obanor

🎯 **Data Analyst | Data Instructor | Storyteller with Data**  
🌍 **Location:** Lagos, Nigeria  
📧 **Email:** [bisiobanor@gmail.com](mailto:bisiobanor@gmail.com)  
📞 **Phone:** +234 813 135 771  
🔗 **LinkedIn:** [linkedin.com/in/rukayatobanor](https://www.linkedin.com/in/rukayatobanor/)  
📁 **Portfolio:** [datascienceportfol.io/RukayatAdebisiObanor](https://www.datascienceportfol.io/RukayatAdebisiObanor)

---

I’m a passionate **Data Analyst** with a keen eye for uncovering insights and transforming raw data into compelling stories that drive business value. With a strong background in data visualization, cleaning, and interpretation, I help organizations make sense of their data through interactive dashboards, strategic analysis, and training sessions.

### 🛠 Key Skills:
- Power BI | Excel | SQL | Python (Pandas, Matplotlib, Seaborn)
- Data Cleaning, Transformation, and Visualization
- Storytelling with Data & Business Insight Development
- Cross-functional Team Collaboration
- HR Analytics | Sales & Operations Dashboards | Education & Training Analytics

### 👩‍🏫 As a Data Instructor:
I thrive in training aspiring data professionals, helping them navigate tools like Excel and Power BI, and guiding them through real-world business problem-solving using data.

---

Let’s connect and turn data into actionable insight!
