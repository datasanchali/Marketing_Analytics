# Ad Impact Analysis: A/B Testing for Conversion Uplift

This project evaluates the effectiveness of a marketing ad campaign using a controlled A/B testing methodology. It compares conversion outcomes between users who were shown ads and those shown a public service announcement (PSA).

---

## Project Objectives

1. **Determine if the ad campaign was successful**
2. **Measure the uplift in conversions due to ads**
3. **Estimate incremental conversions and revenue attributable to the campaign**
4. **Validate results with statistical testing and confidence intervals**

---

## Dataset Overview

The dataset contains user-level interaction data, including:

- `user id`: Unique user identifier  
- `test group`: Indicates if the user saw an ad or PSA  
- `converted`: Boolean flag if the user converted (True/False)  
- `total ads`: Number of ads the user was shown  
- `most ads day`: Day user saw the most ads  
- `most ads hour`: Hour user saw the most ads  

---

## Key Analyses

- **Exploratory Data Analysis (EDA)**: Distribution of ad exposure, conversion by day/hour
- **Conversion Rate Comparison**: Between test and control groups
- **Binning Analysis**: Conversion rate by total ads seen (linear and log-scale bins)
- **Statistical Testing**: Z-test for proportions to validate uplift significance
- **Attribution Modeling**: Estimation of incremental conversions and revenue
- **Visualization**: Heatmaps, bar charts, confidence intervals

---

## 📈 Results Summary

- **Ad Group Conversion Rate**: 2.6%  
- **PSA Group Conversion Rate**: 1.8%  
- **Uplift**: 0.77%  
- **Z-statistic**: 7.37 → **Statistically significant**  
- **Incremental Conversions**: 4,342 users  
- **Estimated Revenue Impact**: (assuming $50 per conversion): $217,149

---

## 📁 Files

- `ads_revenue.ipynb`
---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git

