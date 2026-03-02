# Cement Plant QC Analytics Dashboard  
### End-to-End Data & Business Intelligence Project (Python + Power BI)

<img width="1128" height="638" alt="Page 1" src="https://github.com/user-attachments/assets/849fef54-1852-4760-9608-8a0c1ff10fad" />
<img width="1131" height="637" alt="Page 2" src="https://github.com/user-attachments/assets/555bd359-4c42-4b18-b936-cffc6c2771cd" />

---

## 🔎 Project Overview

This project simulates a **Quality Control (QC) analytics system** for a ready-mix concrete batching plant.

The objective is to transform raw plant QC data into actionable insights that help plant managers:

- Monitor 28-day compressive strength compliance
- Identify slump variability and out-of-spec trends
- Detect mix designs with high failure rates
- Evaluate effectiveness of corrective actions
- Understand environmental effects (temperature, air content) on strength performance

The dataset was synthetically generated to mimic realistic plant production conditions and QC variability.

---

## 🏭 Business Problem

In ready-mix concrete operations, failure to meet target compressive strength can result in:

- Structural non-compliance  
- Customer complaints  
- Costly rework  
- Reputational damage  
- Increased cement usage due to overdesign  

Plant managers require a centralized dashboard to:

1. Monitor strength pass rates in real time  
2. Detect quality drift over time  
3. Identify problematic mix designs  
4. Reduce unnecessary corrective actions  

---

## 🛠 Tools & Technologies Used

- **Python (Pandas, NumPy)** 
- **Jupyter Notebook (Anaconda)** 
- **Power BI Desktop** 
- **DAX** 

---

## Data Processing

Key transformations performed:

- Created `Strength_Margin_MPa`
- Generated binary pass/fail indicators
- Calculated slump out-of-spec flags
- Aggregated KPIs by mix design
- Built monthly trend analysis fields

---

## Dashboard Pages

### 1. Executive Overview

**Purpose:** Provide management-level performance snapshot.

**Key Metrics:**
- Overall Strength Pass Rate
- Total Batches Tested
- Average Strength Margin
- Corrective Actions Count

**Visuals Include:**
- Monthly strength pass rate trend
- Strength status by mix design
- Corrective action distribution
- Mix-level performance comparison table

---

### 2. Quality Deep Dive

**Purpose:** Root-cause analysis and operational diagnostics.

**Visuals Include:**
- Strength margin vs temperature
- Strength vs air content relationship
- Slump vs strength scatter analysis
- Target strength vs actual strength comparison

---

## Key Insights from Analysis

- Overall strength pass rate (76.8%) is below ideal operational target (≥ 90%).
- C40 mix design shows higher failure counts relative to other grades.
- Elevated temperatures correlate with increased strength variability.
- Slump values outside specification increase probability of strength failure.
- Corrective actions appear reactive rather than preventive — opportunity for predictive monitoring.

---

## Business Recommendations

- Implement temperature-adjusted mix control during high ambient conditions.
- Tighten slump monitoring for higher-grade mixes (e.g., C40).
- Introduce early-warning dashboard alerts when pass rate drops below 85%.
- Optimize mix designs to reduce overdesign while maintaining compliance.

---

## Skills Demonstrated

- Industrial domain knowledge (cement & concrete QC)
- Data cleaning and validation
- KPI modeling and performance tracking
- Business storytelling through dashboards
- Root cause exploration using scatter analysis
- DAX measure creation
- Executive-level report structuring

---

## Project Impact Summary

This project demonstrates the ability to:

- Translate operational QC data into decision-ready dashboards  
- Combine domain expertise with analytics  
- Build end-to-end BI solutions from raw data to executive reporting  

---

## Contact

Open to opportunities in:

- Data Analytics  
- Business Intelligence  
- Industrial / Manufacturing Analytics  
- Environmental Data Analysis  

Feel free to connect via LinkedIn.
