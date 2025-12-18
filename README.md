# OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/datavitalyzer/OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions/blob/main/LICENSE.md)

## 🏥 Emergency Department Admissions Analysis with Power BI

This repository hosts a sample Power BI report designed to explore and visualize key metrics related to **hospital emergency admissions**. Developed using a limited, realistic dataset, the report demonstrates how data visualization can reveal meaningful trends in patient flow, departmental workload, and the quality of care.

The report is structured into three distinct pages, each focusing on a critical aspect of Emergency Department (ED) operations.

---

## 📊 Report Structure and Key Insights

The Power BI report, titled **"Health System Tracker – Emergency Department Overview"**, is divided into three interactive tabs, allowing for dynamic exploration using filters for calendar date and admitting department.

### Page 1: Overview (Data Explorer)

This page functions as a **Data Explorer**, providing a granular, record-level view of all patient visits. It is essential for detailed data validation and for understanding the raw volume and distribution of patients.

| Key Components | Description |
| :--- | :--- |
| **Patient Details Table** | A comprehensive list of individual visits, including ID, Age, Gender, Visit Date/Time, Department, and final Admission Status. |
| **Time Filters** | Interactive slicers for Year and Month to narrow the focus of the analysis. |
| **Volume Heatmap** | A matrix visualization showing the number of patients by time slot and day of the week, highlighting peak hours and days for staffing and resource planning. |

![Screenshot of the Overview page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/v1tuBePjwqXMIB19UopTNx-images_1766051742213_na1fn_L2hvbWUvdWJ1bnR1L292ZXJ2aWV3.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L3YxdHVCZVBqd3FYTUlCMTlVb3BUTngtaW1hZ2VzXzE3NjYwNTE3NDIyMTNfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyOTJaWEoyYVdWMy5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=gIDh5ry1JaCBdTY5pwZq7hTnC0xtDADeNe0K0xJ9BSTl2pAFsuxSFLfc~Umn4YuIQ8vIO0nHJ6xPUyS4rX0thbXaphijqBVVpCexN6UhvhnDxsB07deqLiNg05kIMrpTAHiFy8H6iyLnuN9o2g6G5Jc4ZxUXjAC8ih-rGBKFCx2Q21jMbaS43C4OvlL6mfAYHH6oGKPySb4hzCy8in63z0Ed~C-akxXB6uMygqrCg5-Oq8jSoMN8oWnRAX-ZB8CdiI5yj5ESGgYeVdm-2pTAxNoYPyJTfLMxXQfZpoL9S7gpAUVrcW2hrrk4UiOHr8vBP254AkDjeg-RMPk~omG0YQ__)

### Page 2: Detailed View (High-Level Dashboard)

The **Detailed View** serves as the primary high-level dashboard, focusing on key performance indicators (KPIs) and trends over time.

| Key Insights | Visualization Type |
| :--- | :--- |
| **Patient Flow Over Time** | Time series charts tracking the number of patients, average score, average waiting time, and referrals by month. |
| **Demographics** | Donut charts illustrating the distribution of patients by Gender and overall Admission Status (Admitted vs. Not Admitted). |
| **Departmental Performance** | Bar charts showing the breakdown of admitted and not admitted patients across various departments (e.g., Cardiology, Orthopedics, General Practice), providing a clear view of departmental workload and admission patterns. |

![Screenshot of the Detailed View page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/v1tuBePjwqXMIB19UopTNx-images_1766051742214_na1fn_L2hvbWUvdWJ1bnR1L2RldGFpbGVkX3ZpZXc.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L3YxdHVCZVBqd3FYTUlCMTlVb3BUTngtaW1hZ2VzXzE3NjYwNTE3NDIyMTRfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyUmxkR0ZwYkdWa1gzWnBaWGMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzk4NzYxNjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=QwnDMYUdYkCSZV9rgtwgsD4DVZh9bAFnl8XLjJHb1a1ds307fz6dsgzxHn0UkUrj01ek-aYTPm~SIMHtfXSzPRZppwKCK-td1Wly9eKd6mFawT~-hiWBam6JtSu-pADFlBH4oRrljJRoYInHoTjGZEmdpXTrw07HHO9YxYt6RQqSXWlncwuhCUke8-T9JzyqvqQ65U63Z-A4Hd52croYD3~Bl-yFD-JN6BLtEBBP0sc1TcXbgkj1KCX8ZJkZhAMwC2y0f7GwZnXGJs3eLzbQvJRYAvTL5IWPq4Jd1dXkHcQ-doC6rIVNC751h1CWGho2psusSVvkoUIAyhlMc3GJ3w__)

### Page 3: Operational & Experience Metrics

This page dives into the **Quality of Care and Operational Efficiency**, exploring the critical relationship between service delivery and patient experience.

| Key Metrics | Focus Area |
| :--- | :--- |
| **Patient Satisfaction** | Scatter plot analyzing the **Impact of Waiting Time on Patient Satisfaction** and bar charts showing **Average Patient Satisfaction by Department**. |
| **Operational Efficiency** | Heatmap detailing **Waiting Time by Hour Slot** and bar charts showing patient volume by time slot and weekday, identifying potential bottlenecks. |
| **Service Level Agreement (SLA)** | A clear visualization of the percentage of **Patients Seen Within 30 minutes**, a critical measure of ED responsiveness. |

![Screenshot of the Operational & Experience Metrics page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/v1tuBePjwqXMIB19UopTNx-images_1766051742214_na1fn_L2hvbWUvdWJ1bnR1L29wZXJhdGlvbmFsX21ldHJpY3M.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L3YxdHVCZVBqd3FYTUlCMTlVb3BUTngtaW1hZ2VzXzE3NjYwNTE3NDIyMTRfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyOXdaWEpoZEdsdmJtRnNYMjFsZEhKcFkzTS5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=cQrv-~MzoDI1apMq0oEoyb90NcsoM3FVKqQRI71p2R1JxhxMMJb9Ab6JVd7zUZwQhl2mcJdSi2J42X05B3K10eJmiVl4Y2xqt3hEAwHT6qHFhcKm~6HnrkNe8JWEkrmoXPCp6KYqFjazkEjXHNgftGEgd9ASbxKrqcAhRJSU7r2BBjnbCLYLC4XHugNrFYexiaZ7l4u~VtnbDvF7LpKltoiA4Ozi1ncMDl7jdRu22s9TWFJLut2rC9S4SPedSkSjIrockX1rdoDLSL-wNEbAjhjFvl49BO~sBFUrO6v8OkUkNPN-6XCpzlPcibqq9mO8mYT0a33zicaTNfoeHyw3~w__)

---

## 💾 Dataset Overview

The analysis is based on a simplified and anonymized dataset that mimics a real emergency intake scenario. The data includes the following fields:

*   `Visit Date`
*   `Time before Admission`
*   `Department`
*   `Admission Status` (Admitted or Not Admitted)
*   `Gender`

The raw data file, `Hospital ER.csv`, is included in this repository.

[Download Hospital Emergency data sample here](https://github.com/datavitalyzer/OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions/blob/main/Hospital%20ER.csv)

## 🚀 Getting Started

To view and interact with the report:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/datavitalyzer/OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions.git
    ```
2.  **Open the Power BI File:**
    *   The Power BI report file (`.pbix`) is not included in this sample, but the underlying data (`Hospital ER.csv`) is provided.
    *   You can recreate the report using the provided data and the visual structure shown in the screenshots.
3.  **View Online:**
    *   If an online version is available, you can browse the report directly [Here](https://app.powerbi.com/view?r=eyJrIjoiZmM4ZjE3YjgtYjE5Ny00YmU1LTg2YjktYjM5M2Q3YmI2M2Q1IiwidCI6IjI1ZGY2M2FmLTkwY2EtNDU2Mi1hYjY5LTQ1ZTY1M2Q3N2M2YyJ9). (Note: This link is a placeholder based on the original README and should be verified/updated by the user).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

*Report created by Manus AI for datavitalyzer.*
