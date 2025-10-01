# 📊 NYC Motor Vehicle Collision Analysis (2021-2023)

## Project Overview
[cite_start]This repository contains the analysis and Key Performance Indicator (KPI) report created for the New York City (NYC) office, focusing on motor vehicle collision data reported by the **New York City Police Department (NYPD)**[cite: 3, 4].

The primary objectives of this analysis were to identify:
1.  **Temporal trends** for accidents and casualties (time, day, and month).
2.  **Location-based hotspots** that are more prone to accidents.
3.  [cite_start]**Key factors and vehicle types** contributing to these collisions[cite: 4].

---

## 📅 Data & Time Period
* [cite_start]**Source:** NYC Open Data Portal (Motor Vehicle Collisions) [cite: 10]
* [cite_start]**Time Period:** January 2021 to April 2023 [cite: 4, 11]
* [cite_start]**Total Records:** 238,421 collisions [cite: 12]

### Key Data Fields
[cite_start]The analysis utilized fields including: `Collision ID`, `Date`, `Time`, `Borough`, `Contributing Factor`, `Persons Injured`, and `Persons Killed`[cite: 13].

---

## 📈 Executive Summary of Key Findings

[cite_start]From January 2021 to April 2023, the dataset recorded **230,000+ collisions**, resulting in **116,227+ injuries** and **635 deaths**[cite: 6].

### A. Temporal Findings
* [cite_start]**Most Dangerous Day:** **Friday** is the most dangerous day, responsible for **18% of all deaths**[cite: 8, 19].
* [cite_start]**Most Dangerous Month:** **July** is the top month for crashes and casualties, with deaths increasing by **38%** from the average[cite: 7, 16].
* [cite_start]**Peak Accident Time:** Most accidents and injuries happen between **4 PM and 5 PM**, likely due to high traffic[cite: 20].
* **Peak Fatality Time:** Most casualty-heavy accidents happen between **3 AM and 5 AM**, peaking around **4 AM**. [cite_start]This is likely due to poor lighting and reckless/drunk driving[cite: 30].

### B. Location Findings
* [cite_start]**Most Dangerous Borough:** **Brooklyn** is the most dangerous borough, accounting for approximately **29% of all casualties**[cite: 6, 33].
* [cite_start]**Top 3 Boroughs for Casualties:** Brooklyn (**29%**), Queens (**25%**), and the Bronx (**20%**)[cite: 33].
* [cite_start]**Most Dangerous Street:** **Belt Parkway**, which is responsible for **3%** of all casualties[cite: 35].

### C. Contributing Factors
* [cite_start]**Top Contributing Factor (by Death):** **Unsafe Speed** is responsible for the highest number of deaths (145)[cite: 52, 53].
* [cite_start]**Other Top Factors:** **Driver Inattention/Distraction** (74 deaths) and **Failure to Yield Right-of-Way** (46 deaths)[cite: 47, 49].
* [cite_start]**Vehicle Involvement:** **Passenger Vehicles** are involved in about **85%** of all accidents[cite: 36].
* [cite_start]**Casualty Breakdown:** Motorists contribute to about **42%** of all deaths, while over **45%** of all deaths involve pedestrians[cite: 55, 56].

---

## 🛠️ Data Cleaning Summary

Initial data cleaning and handling steps performed:

| Column | Issue | Magnitude | Resolution |
| :--- | :--- | :--- | :--- |
| **Cross Street** | Missing Values | 53.32% | Dropped the column |
| **Borough** | Missing Values | 3.02% | Recategorized to "Unknown" |
| **Contributing Factor** | Missing Values | 0.54% | Recategorized to "Unspecified" |
| **Persons Injured** | Missing Values | 0.00% (1 row) | Replaced with `0` |
| **Vehicle Type** | Weird/Unknown Categories | 1.88% | Combined and recategorized to "Others" |

---

## 💡 Recommendations
The following recommendations are proposed to the city office based on the analysis:
* [cite_start]Increase the number of traffic police and improve traffic flow during crowded hours[cite: 58].
* [cite_start]Conduct awareness campaigns around rush hours and weekends[cite: 59, 31].
* [cite_start]Increase the fine for reckless high-speed driving[cite: 61].
* [cite_start]Install railings on sidewalks to decrease pedestrian involvement in accidents[cite: 62].
* [cite_start]Add traffic rules to the curriculum of school students[cite: 63].

---

*For detailed analysis and methodology, please refer to the `NYC Collision Analysis Report.pdf` and the associated Jupyter notebooks.*
