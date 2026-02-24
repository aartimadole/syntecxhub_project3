# 🦠 COVID-19 Time Series Analysis & Insights

## 📌 Project Overview
This project performs country-level COVID-19 time series analysis to generate data-driven insights on case trends, peak detection, rolling averages, and basic reproduction rate proxy estimation.  

The objective is to demonstrate time-series analytics, data transformation, smoothing techniques, and comparative country analysis using Python.

---

## 🎯 Key Objectives
- Load and preprocess country-wise COVID time series dataset
- Compute daily and weekly new cases
- Apply rolling averages to smooth noise
- Detect peak infection periods
- Estimate basic reproduction proxy (Rt approximation)
- Compare trends across multiple countries
- Export visual reports and summary insights

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Time-Series Analysis

---

## 📊 Key Features Implemented

### 1️⃣ Daily & Weekly Case Computation
- Converted cumulative cases into daily new cases
- Used rolling windows and resampling for weekly aggregation

### 2️⃣ Rolling Average Smoothing
- Applied 7-day rolling average to reduce reporting noise
- Improved trend visibility for better comparison

### 3️⃣ Peak Detection
- Identified highest infection day per country
- Extracted peak value and corresponding date

### 4️⃣ Reproduction Proxy (Rt Approximation)
- Estimated growth factor using:
  Rt ≈ (7-day avg today / 7-day avg 7 days ago)

### 5️⃣ Multi-Country Comparison
- Compared India, US, Brazil (customizable)
- Generated rolling average comparison chart

---

## 📁 Output Files Generated
- `rolling_avg_comparison.png` → Country trend comparison
- `covid_summary_report.csv` → Country-level summary metrics

---

## 📈 Sample Insights
- Peak waves varied significantly across countries.
- Rolling averages effectively reduced volatility in daily reporting.
- Growth proxy indicated multiple infection waves during high transmission phases.
- Weekly aggregation highlighted wave cycles more clearly than raw daily cases.

---

## 🚀 How to Run the Project

```bash
pip install pandas numpy matplotlib
