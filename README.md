# Medical Insurance Cost Analysis: Interactive Tableau Dashboard
**An analysis of leading factors influencing health insurance premiums using Tableau.**

---

## 📌 Project Overview
This project involved the development of a comprehensive business intelligence dashboard to visualize the key drivers of medical insurance charges. By analyzing a dataset of **1,338 records**, I identified how lifestyle factors (smoking), demographics (region), and physical metrics (BMI) correlate with healthcare costs.

---

## 💡 Key Analytical Insights

### 1. Demographic & Lifestyle Correlations
Utilizing a multi-layered bar chart, I compared regional average charges against smoker status.

* **Primary Finding:** Lifestyle choice (smoking) is a significantly higher cost-driver than geography.
* **Regional Variance:** The **Southeast** region was identified as having the highest average costs for smokers (**$33,949**), while the **Southwest** had the lowest average for non-smokers (**$7,213**).

![Regional Cost Analysis](average-charge-bar-chart.jpg)

### 2. The Impact of Dependents on Healthcare Spend
A dual-axis line chart was implemented to track how the number of children affects total charges, segmented by smoker status.

* **Trend Analysis:** For smokers, costs peaked at **2 children ($33,783)** before showing a significant reduction as the number of children increased to 5.
* **Comparative Baseline:** Non-smokers maintained a relatively stable cost profile regardless of the number of dependents.

![Dependents vs Charges Trend](average-charge-line-chart.jpg)

### 3. Multivariate Risk Assessment
The final dashboard segment utilizes an area chart and scatter plot to visualize the complex relationship between Age, BMI, and Charges.

* **Significant Trend:** A scatter plot with an integrated trend line confirms that as age increases, charges rise significantly (**P-value < 0.05**).
* **Risk Clusters:** The analysis identifies a "High Risk" group: smokers with excessive BMI, who pay an average of **$12,000 more** than lower-BMI smoking counterparts.

![Insurance Risk Dashboard](area-chart-scatter-plot.jpg)

---

## 🛠 Dashboard Features
* **Dynamic Filtering:** Users can filter by smoker status and number of children to see real-time charge updates.
* **Statistical Validation:** Integrated trend lines and P-value analysis to ensure visual observations are statistically significant.
* **Heatmapping:** Use of color gradients to quickly identify high-cost geographic regions and BMI categories.

---

## 🏁 Conclusion & Business Recommendations
The interactive analysis successfully identified lifestyle and demographic variables that serve as primary escalators for insurance premiums.

* **Smoking as a Primary Cost Driver:** Across all regions, smoker status remained the most significant predictor of high charges, with average costs exceeding $30k in the Southeast.
* **BMI & Age Correlation:** The scatter plot confirms a statistically significant trend (**P < 0.05**) where increasing age and high BMI create a compounding effect on healthcare spend.
* **Strategic Recommendations:** Insurance providers should prioritize wellness and smoking-cessation programs in the **Southeast and Northwest** regions to mitigate high-cost regional claims.
