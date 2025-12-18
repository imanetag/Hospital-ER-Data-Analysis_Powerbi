# Hospital-ER-Data-Analysis_Powerbi

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)

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

![Screenshot of the Overview page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/mLHzMv0EJaRJeAIQA0DGy2-images_1766052752079_na1fn_L2hvbWUvdWJ1bnR1L292ZXJ2aWV3.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L21MSHpNdjBFSmFSSmVBSVFBMERHeTItaW1hZ2VzXzE3NjYwNTI3NTIwNzlfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyOTJaWEoyYVdWMy5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=fUtuTyzrKBfdTQ7i2VN6YVcWlr7EZpXz9ybO5ZyvPS6uRsEt~dYBw0kQkkuh4plq-sAGxRQVTZYKsFQm3NqD13ejfBCavSmageQSU~7SrphzHaocV42pk2O0Pp5beHv0hc6cfFlb3C6iIRVWn-3bNpcBAI8kU61pxW~Y6ESVrpqNn9sleHMmPDfVVJQQX0es-XYYV4JBRZdnIlB6wSBUPegdUh2ExgeZvqBQjI8WUP3tHTpdizbW0bXnfsx-xk~lcGlBu3OtEH-g9-Ix7bjPkHnctf4IznuR73~gqRv~l0B~t~Lfc8j7-Joz0WbX2f3~sVZmoi32Oo-VKhHGhH75pg__)

### Page 2: Detailed View (High-Level Dashboard)

The **Detailed View** serves as the primary high-level dashboard, focusing on key performance indicators (KPIs) and trends over time.

| Key Insights | Visualization Type |
| :--- | :--- |
| **Patient Flow Over Time** | Time series charts tracking the number of patients, average score, average waiting time, and referrals by month. |
| **Demographics** | Donut charts illustrating the distribution of patients by Gender and overall Admission Status (Admitted vs. Not Admitted). |
| **Departmental Performance** | Bar charts showing the breakdown of admitted and not admitted patients across various departments (e.g., Cardiology, Orthopedics, General Practice), providing a clear view of departmental workload and admission patterns. |

![Screenshot of the Detailed View page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/mLHzMv0EJaRJeAIQA0DGy2-images_1766052752080_na1fn_L2hvbWUvdWJ1bnR1L2RldGFpbGVkX3ZpZXc.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L21MSHpNdjBFSmFSSmVBSVFBMERHeTItaW1hZ2VzXzE3NjYwNTI3NTIwODBfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyUmxkR0ZwYkdWa1gzWnBaWGMucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzk4NzYxNjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=ZmU0egVKWHN9ueWgHGiQltia5P2XHwlpUar9XOmohtQZRA5-9Qyh6vF2ualj6hKZ7h6EiIA7hTu-wd-aXYGXDfU98RubPWUvEDxVZP~E0ox~bXF6B6x8LigyNAjgVK994C-Y6x3vew0BElDqYGVJcmuieA9ykingDErTVHyWTk3wDcluMLQyLQnsOClt9TR921f0eOHkjxGg7CXom8bWi70nELdJE6SNatIdDNdhMdtz3QyaPXzeBe0BmcNKwue071jyxKh4r6VxWBAE1sUpPAhq7DHWVYSzdjoUXBqPlOtS-LnwXuqWfVR2LyRWyMPMDRRj6Ei5yclQHFEANRop4g__)

### Page 3: Operational & Experience Metrics

This page dives into the **Quality of Care and Operational Efficiency**, exploring the critical relationship between service delivery and patient experience.

| Key Metrics | Focus Area |
| :--- | :--- |
| **Patient Satisfaction** | Scatter plot analyzing the **Impact of Waiting Time on Patient Satisfaction** and bar charts showing **Average Patient Satisfaction by Department**. |
| **Operational Efficiency** | Heatmap detailing **Waiting Time by Hour Slot** and bar charts showing patient volume by time slot and weekday, identifying potential bottlenecks. |
| **Service Level Agreement (SLA)** | A clear visualization of the percentage of **Patients Seen Within 30 minutes**, a critical measure of ED responsiveness. |

![Screenshot of the Operational & Experience Metrics page in the Power BI Report](https://private-us-east-1.manuscdn.com/sessionFile/hGfjEcfVgeT2Ms2fvw7nbq/sandbox/mLHzMv0EJaRJeAIQA0DGy2-images_1766052752081_na1fn_L2hvbWUvdWJ1bnR1L29wZXJhdGlvbmFsX21ldHJpY3M.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvaEdmakVjZlZnZVQyTXMyZnZ3N25icS9zYW5kYm94L21MSHpNdjBFSmFSSmVBSVFBMERHeTItaW1hZ2VzXzE3NjYwNTI3NTIwODFfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyOXdaWEpoZEdsdmJtRnNYMjFsZEhKcFkzTS5wbmciLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=L2-VeomR7ZDwPcgy-Lh1AgnVmrGFnvk6uaaEcfc5Uf7OOT68iJDtiCIxy4WLxG~8l47Yl8xjIp5QdHrzQ5FQpYXqb4y9S5jXWOwIJytXvDYBVe9XXP9cy8c2~hr0dZ~hwVCi~G1HLraERMMSPb9AcPB2POxOoXJi5r8hhW26Vjiuyuu7bFbXWDD1AQb5GxQC97TqBW4Zq~xI7OfIDU2ES1X9JlOl-NeRI3KNEzVf29yK5Wz8fETx5RqPUDSWkk~C~KJ-Frx7svoHJfAomaTF7AgaTZGZ5JX-awv2b0cRkuHbVMbka4NtjkyBMJ2UEw34fI0ewieCDJyLLgFpeJYP3A__)

---

## 💾 Dataset Overview

The analysis is based on a simplified and anonymized dataset that mimics a real emergency intake scenario. The dataset was originally sourced from the [OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions](https://github.com/datavitalyzer/OBaz-DA4U-PowerBI-ReportSample-Emergency-Admissions) repository. The data includes the following fields:

*   `Visit Date`
*   `Time before Admission`
*   `Department`
*   `Admission Status` (Admitted or Not Admitted)
*   `Gender`

The raw data file, `Hospital ER.csv`, is included in this repository.

[Download Hospital Emergency data sample here](Hospital%20ER.csv)

## 🚀 Getting Started

To view and interact with the report:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/[YOUR_GITHUB_USERNAME]/Hospital-ER-Data-Analysis_Powerbi.git
    ```
2.  **Open the Power BI File:**
    *   The Power BI report file (`.pbix`) is not included in this sample, but the underlying data (`Hospital ER.csv`) is provided.
    *   You can recreate the report using the provided data and the visual structure shown in the screenshots.
3.  **View Online:**
    *   If an online version is available, you can browse the report directly [Here](https://app.powerbi.com/view?r=eyJrIjoiZmM4ZjE3YjgtYjE5Ny00YmU1LTg2YjktYjM5M2Q3YmI2M2Q1IiwidCI6IjI1ZGY2M2FmLTkwY2EtNDU2Mi1hYjY5LTQ1ZTY1M2Q3N2M2YyJ9). (Note: This link is a placeholder based on the original README and should be verified/updated by the user).


