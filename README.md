# Healthcare Data Analysis Dashboard 🏥

## 📌 Project Overview
This project presents a comprehensive data analysis solution for a healthcare facility built entirely within Power BI. The goal is to monitor patient demographics, evaluate admission sources, analyze top diseases, and optimize operational efficiency by tracking patient wait times across different departments.

## 🛠️ Tools & Technologies Used
* **Data Visualizations & Dashboard Design:** Power BI Desktop.
* **Data Transformation & Cleaning:** Power Query (Used for handling missing values and renaming categories like 'Direct Admission').
* **Calculations & Analytics:** DAX (Data Analysis Expressions) for building custom KPIs, averages, and time-based metrics.

## 📊 Key Insights & Business Findings
* **Operational Efficiency:** The average wait time across all departments is **35.26 minutes**, which serves as a baseline for hospital operations.
* **Patient Demographics:** Total patients analyzed reached **9.216K**, with a balanced distribution between Male and Female patients.
* **Top Prevalent Conditions:** Hypertension and Diabetes Type 2 are the most common conditions among admitted patients.
* **Admission Insights:** A significant portion of patients are categorized under **Direct Admission** (cleaned from the original raw data), indicating high walk-in traffic rather than department referrals.
* **Demographic Dominance:** The **26-60 (Adults)** age group represents the highest volume of patient visits, making them the primary demographic for hospital services.
* **Top Prevalent Condition:** **Hypertension** is identified as the leading health issue among admitted patients, followed closely by Diabetes Type 2.
* **Operational Bottlenecks:** Patients experience the longest wait times in the **Neurology department**, averaging **36.80 minutes**—which is approximately **2 minutes longer** than the hospital's most efficient department.
* **Gender & Admission:** Patients are almost equally distributed between genders, with a significant portion entering via **Direct Admission** rather than department referrals.

## 🖼️ Dashboard Preview
![Healthcare Dashboard Screenshot](dashboard_screenshot.jpg)

## 📐 Data Architecture & Model
The project follows a clean data modeling approach to ensure high performance:

![Data Model](data_model.jpg)

## 📂 Project Structure
* `/Healthcare_Dashboard.pbix` - The core Power BI project file containing the data model, Power Query steps, and the visual layout.
* `/dashboard_screenshot.jpg` - A preview image of the final dashboard.
* `README.md` - Project documentation.
