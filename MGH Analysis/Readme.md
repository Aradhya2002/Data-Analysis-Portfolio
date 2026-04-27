# 📊 MGH Healthcare Performance Analysis

## PowerBi Dashboard
<img width="1049" height="588" alt="Encounters_page" src="https://github.com/user-attachments/assets/44b2fcf2-a065-4e02-afcf-71634d473c70" />
<img width="1049" height="592" alt="Procedures_page" src="https://github.com/user-attachments/assets/c28eb548-0234-4076-ab17-7db770fbc3da" />


## 🎯 Project Objective
Analyze patient, encounter, and procedure data to build KPI-driven reports that evaluate operational performance, financial efficiency, and patient outcomes, while uncovering actionable insights.

---

## 📌 Executive Summary
This analysis presents a comprehensive view of MGH’s performance across admissions, readmissions, length of stay (LOS), and financial metrics.

- **Total Encounters:** ~28,000  
- **Admissions:** 1,135 (4.1%)  
- **Total Claim Cost:** $102M  
- **Payer Coverage:** $31M  

A critical issue identified is the **high unclaimed procedure cost of $74.4M (~71%)**, indicating significant revenue leakage and inefficiencies in the claims process.

### 🔑 Key KPIs
- **Average Encounter Cost:** $116.18  
- **Average Claim Cost:** $3.64K  
- **Average Daily Procedures:** 12  
- **Mortality Rate:** 15.8%  
- **Average Length of Stay:** 7.28 hours  

> ⚠️ **Key Insight:** Operational performance is stable, but financial inefficiencies—especially unclaimed costs—are a major concern.

---

## 🔍 Insights Deep-Dive

### 🏥 Patient Admissions & Readmissions
- 1,135 admissions from ~28,000 encounters  
- 396 unique admitted patients  
- Admission peaks in **2014 and 2020**  
- **14% readmission rate (within 30 days)**  
- Dropped below **5% during 2020–2021** (likely due to COVID-19 impact)

> 📌 Reduced readmissions during the pandemic may reflect limited hospital access rather than improved outcomes.

---

### ⏱️ Length of Stay (LOS)
- **Average LOS (overall):** 7.3 hours  
- **Admitted patients:** 37 hours  
- **Non-admitted patients:** < 45 minutes  

#### 📈 Trend:
- Pre-pandemic: ~24 hours  
- Post-pandemic: ~55 hours  

> ⚠️ Increased LOS post-pandemic suggests resource strain and reduced throughput efficiency.

---

### 💰 Financial Analysis
- **Average cost per visit:** $3.7K  
- **Admissions cost:** $7.8K  
- **Non-admissions cost:** $3.5K  

#### Insurance Impact:
- **Uninsured (Admissions):** $9.2K  
- **Insured (Admissions):** $7.3K  

#### 🚨 Revenue Leakage:
- **Total Procedure Cost:** ~$105M  
- **Unclaimed:** 71%  

> 📌 Indicates:
> - Claim processing inefficiencies  
> - Insurance rejection issues  
> - Missing documentation  

---

### ⚙️ Operational Insights
- **Non-admissions:** 95.9%  
- **Admissions:** 4.1%  

> 📌 Hospital is heavily **outpatient-focused**

- **67% of patients are seniors (65+)**

> 📌 Aging population drives higher costs and resource utilization

---

## 🚨 Key Problems Identified
1. **Massive unclaimed procedure cost (71%)**
2. **Increasing length of stay post-pandemic**
3. **High cost burden for uninsured patients**
4. **Senior-heavy patient demographic driving costs**

---

## ✅ Recommendations

### 💡 Financial Optimization
- Audit high-cost procedures contributing to unclaimed revenue  
- Improve claim submission and validation processes  
- Reduce insurance rejection rates  

---

### ⚙️ Operational Efficiency
- Reduce LOS for admitted patients to pre-pandemic levels  
- Improve patient throughput and bed utilization  

---

### 👥 Patient Strategy
- Increase insurance coverage awareness  
- Introduce financial assistance programs for uninsured patients  
- Focus on preventive care for senior patients  

---

## ⚠️ Assumptions & Caveats
- Readmission rate is calculated using a **30-day window**  
- Drop in readmission during 2020 assumed due to **COVID-19 impact**  
- LOS calculations only include **inpatient admissions**

---

## 📊 Tools & Technologies
- Power BI  
- SQL  
- Excel  

---

## 📌 Conclusion
MGH demonstrates stable operational performance but suffers from significant financial inefficiencies, particularly due to high unclaimed procedure costs. Addressing these gaps can lead to improved revenue realization and better resource utilization.

---

## 🚀 Future Improvements
- Add predictive modeling for readmissions  
- Build LOS optimization models  
- Develop claim approval forecasting  
