# A/B Testing Analysis: Control vs Test Campaign

# Project Summary
This project presents a comprehensive A/B testing analysis comparing two marketing campaigns (Control vs Test) to determine which variant performs better in terms of conversion efficiency and cost-effectiveness.

The analysis combines Python for data preprocessing, Power Query for transformation, and Power BI for interactive visualization and business insights.

# Business Objective
The primary goal is to evaluate which campaign drives better performance by analyzing:

- Conversion Rate (CR)
- Cost Per Acquisition (CPA)
- Total Purchases
- Marketing Spend
This enables data-driven decision-making for optimizing marketing strategy.

# Tech Stack

- **Python (Pandas)** → Data cleaning and preprocessing  
- **Power Query** → Data transformation and merging  
- **Power BI** → Dashboard creation and KPI analysis  

# Data Description

The dataset consists of two groups:

- **Control Group** Existing campaign  
- **Test Group** New variation  

Each dataset includes:

- Impressions  
- Clicks  
- Spend  
- Purchases  
- User engagement metrics  

# Data Preparation

# Python (Pandas)
- Cleaned column inconsistencies  
- Handled missing values  
- Standardized dataset structure  

# Power Query
- Added group labels (Control/Test)  
- Appended datasets into a unified table  
- Prepared data for analysis  

# Key Metrics Defined

- **Conversion Rate (CR)** = Purchases / Clicks  
- **Cost Per Acquisition (CPA)** = Spend / Purchases  
These metrics were calculated using DAX measures in Power BI for dynamic analysis.

# Analysis & Findings

| Metric | Control | Test |
| Conversion Rate | 10% | 9% |
| CPA | 4.53 | 4.92 |
| Total Purchases | 15,161 | 15,637 |
| Total Spend | 68,653 | 76,892 |

# Insights

- The **Control group achieved a higher conversion rate**, indicating better user engagement and effectiveness.
- The **Control group maintained a lower CPA**, making it more cost-efficient.
- Although the Test group generated slightly more purchases, it required significantly higher spend.

---

# Final Conclusion

The **Control campaign is the winner** as it delivers:
- Higher conversion efficiency  
- Lower acquisition cost  
- Better overall return on investment  

This suggests that the new variation (Test group) does not outperform the existing strategy and should not be adopted without further optimization.

---

# Dashboard Overview
The Power BI dashboard provides:
- KPI comparison (CR, CPA, Purchases, Spend)  
- Group-wise performance breakdown  
- Time-based trends  
- Interactive filtering  

# Key Learnings
- Importance of evaluating both **performance and cost efficiency**
- Proper structuring of A/B test data using a unified dataset
- Leveraging DAX for dynamic metric calculations
- Building business-focused dashboards instead of just visual reports

# Future Improvements
- Statistical significance testing (p-value, confidence intervals)  
- Segmentation analysis (device, audience type)  
- Experiment duration optimization  


**Rabeeh Mabrook**  
Aspiring Data Analyst | Power BI | Python  

---
