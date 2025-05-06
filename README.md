# A/B Testing on Marketing Campaigns Data
## Overview  
This project analyzes the effectiveness of digital advertising campaigns using A/B testing methodologies. Leveraging a dataset of over **580,000 user records**, the analysis aims to determine whether the ad campaign led to a statistically significant increase in conversion rates compared to a PSA (control) group.

In addition to classical hypothesis testing, the project incorporates **bootstrap resampling**, **group sequential analysis**, and **multiple testing correction techniques** to account for interim data reviews and time-varying effects.

---

## 🔍 Key Findings  
- **Ad Group Conversion Rate**: 2.55%  
- **Control Group Conversion Rate**: 1.79%  
- **p-value**: < 0.001 (significant uplift in ad group)  
- **Effect strengthened after Day 2**, suggesting time-dependent ad impact  
- Pocock and Bonferroni boundaries used to control Type I error across repeated analyses

---

## 🧪 Methods Used  
- A/B testing with two-sample t-tests  
- Bootstrapped confidence intervals  
- Group sequential design (interim analysis and early stopping rules)  
- Multiple testing correction (Pocock and Bonferroni methods)  
- Temporal trend analysis

---

## 📊 Visualizations  
- Conversion trends over time  
- Statistical thresholds and confidence intervals  
- Created using:
  - `ggplot2` in R  
  - `Matplotlib` in Python

---

## 🛠️ Technologies & Tools  
- **Python**: pandas, NumPy, matplotlib  
- **R**: ggplot2, dplyr, boot  
- **JupyterLab**  
- **RStudio**
