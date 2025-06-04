# CMS Inpatient Analysis – Medicare Cost & Utilization

## 📌 Project Purpose

This project explores variation in inpatient hospital costs and outcomes across the U.S. using CMS Medicare data. The goal is to identify how costs differ by hospital type, region, and population characteristics — and to build payer-relevant metrics such as cost-efficiency, readmission-adjusted payment rates, and DRG-level benchmarking.

The project is built in Power BI and includes data modeling, Power Query transformations, and advanced DAX calculations, with a focus on producing analysis that is both actionable and scalable.

---

## 📚 Datasets Used

| **Dataset Name**                                         | **Function / Role in Project**                                                                 |
|----------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **Medicare Inpatient Hospitals by Provider and Service** | 🔹 **Core fact table** – Hospital- and DRG-level utilization, cost, and payment data            |
| **CMS Program Statistics – HOSP 3 (by Area of Residence)** | 🔹 Regional benchmarking – Cost, discharges, and payments by geography                         |
| **CMS Program Statistics – HOSP 4 (by Hospital Type)**     | 🔹 Segment analysis – Compare cost/utilization by facility type (e.g., general, psych)         |
| **CMS Program Statistics – HOSP 9 (by Bedsize, Ownership, Teaching)** | 🔹 Provider characteristics – Used for slicing and grouping peer facilities         |
| **CMS Program Statistics – HOSP 2 or 6 (by Demographics)** | 🔹 Population insight – Analyze cost/utilization by race, dual-eligibility, age                |
| **Medicare Monthly Enrollment (by State or County)**      | 🔹 **Normalization dimension** – Allows per-enrollee cost/utilization rate calculations         |
| **Hospital Info / Certification Data**                    | 🔹 **Hospital dimension table** – Join to provider+DRG data to enrich with ownership, region   |
