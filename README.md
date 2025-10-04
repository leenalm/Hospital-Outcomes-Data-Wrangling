# 📊 Data Wrangling Projects  

This repository contains two real-world data wrangling projects demonstrating advanced data cleaning, reshaping, and integration techniques.  

---

## 1️⃣ Hospital Outcomes Data Wrangling

### 🧠 Overview  
This project investigates how patient demographics and medical diagnoses influence hospital outcomes, such as discharge status or complications. We integrate **patient-level hospital data** with **national health statistics** to identify patterns in age, sex, race, and specific conditions affecting patient outcomes.

### 🎯 Objectives  
- Gather data from **two sources** (CSV + API)  
- Resolve **data quality** and **tidiness issues**  
- Merge datasets for integrated analysis  
- Explore:  
  > *How do patient demographics relate to specific conditions and hospital outcomes?*

### 🧰 Tools & Libraries  
Python, pandas, NumPy, requests, json, matplotlib, seaborn, Jupyter Notebook  

### 📁 Project Structure  

### 🧮 Data Wrangling Workflow  

1. **Data Gathering**: Load CSV dataset with flight-level arrival and departure information  
2. **Assessment**:  
   - Checked for missing values (`ARR_Late`, `DEP_HOUR`, `DAY_OF_WEEK`)  
   - Assessed data types and invalid entries  
3. **Cleaning**:  
   - Imputed missing numeric values with median  
   - Converted categorical columns to consistent labels  
4. **Analysis**:  
   - Grouped by `DEP_HOUR` and `DAY_OF_WEEK` to compute average delays  
   - Visualized trends using bar and line plots  

### 📈 Key Findings  
- Early-morning flights (before 5 AM) tend to have higher late arrivals  
- Delays gradually increase throughout the day  
- Patterns differ between weekdays and weekends  
- Insights can guide airline scheduling and operational planning  
