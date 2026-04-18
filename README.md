# Air-Quality-Health-Impact-Analysis

## 📌 Overview

This project analyzes the relationship between air pollution, environmental factors, human activity, and health outcomes using a comprehensive dataset. The goal is to identify key drivers of Air Quality Index (AQI) and understand whether pollution directly impacts public health.

---

## 🎯 Objectives

* Analyze factors influencing AQI
* Study the impact of weather conditions on pollution
* Evaluate effects of human activities (vehicles, industry, construction)
* Assess policy interventions (lockdown, school closures)
* Investigate the relationship between pollution and health outcomes
* Explore potential lag effects between AQI and hospital visits

---

## 📂 Dataset Description

The dataset contains 3000 records with 26 features, including:

### 🌫️ Pollution Indicators

* AQI, PM2.5, PM10, NO2, SO2, CO, O3

### 🌦️ Weather Factors

* Temperature, Humidity, Wind Speed, Precipitation

### 🏥 Health Metrics

* Hospital Visits, Emergency Visits, Respiratory Admissions

### 🚶 Human Activity & Policy

* Mobility Index, School Closures, Mask Usage, Lockdown Status

### 🏭 Activity Indicators

* Industrial Activity, Vehicle Count, Construction Activity

### 🌱 Environmental Factors

* Population Density, Green Cover Percentage

---

## 🛠️ Tools & Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 🔍 Analysis Performed

### 1. Correlation Analysis

* Examined relationships between AQI and pollutants
* Found negligible correlations across all pollutants

---

### 2. Regional & Seasonal Analysis

* Compared AQI across regions and months
* Observed minimal variation in air quality

---

### 3. Weather Impact Analysis

* Studied humidity, wind speed, and precipitation effects
* No strong influence on AQI detected

---

### 4. Human Activity Analysis

* Analyzed vehicle count, industrial activity, and construction
* Weak or no relationship with pollution levels

---

### 5. Policy Impact Analysis

* Evaluated lockdowns and school closures
* Minimal impact on AQI and mobility

---

### 6. Health Impact Analysis

* Compared AQI with hospital visits and respiratory admissions
* No strong correlation found

---

### 7. Lag Analysis

* Tested delayed effects (1–5 days) of AQI on hospital visits
* No significant lag effect observed

---

## 📊 Key Findings

* AQI shows **no strong linear relationship** with individual pollutants
* Weather factors have **minimal influence** on pollution levels
* Human activities do not independently explain AQI variation
* Policy measures show **negligible impact** on air quality
* Health outcomes are **not directly linked** to AQI in this dataset
* Lag analysis confirms **no delayed effect**

---

## 💡 Final Insight

> The absence of strong correlations indicates that air quality is not driven by isolated variables but by complex, multi-factor interactions. Traditional EDA techniques are insufficient to capture these relationships.

---

## 🚀 Future Work

* Apply machine learning models (Random Forest, Regression)
* Perform feature importance analysis
* Explore non-linear relationships
* Build predictive models for AQI and health outcomes

---

## 📌 Conclusion

This project demonstrates that air pollution is a complex system where individual variables fail to explain outcomes independently. A multivariate and model-driven approach is necessary to uncover meaningful insights.

---

## 👤 Author

Dhruv Karande
