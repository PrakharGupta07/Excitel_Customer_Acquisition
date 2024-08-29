<img align="centre" alt="Coding" width="200" src="https://content3.jdmagicbox.com/comp/jaipur/l4/0141px141.x141.191018061003.q3l4/catalogue/excitel-broadband-tonk-pathak-jaipur-internet-service-providers-pai0bjj8h5.jpg">

# 📊 Excitel Customer Acquisition Analysis

This repository contains a comprehensive analysis of Excitel's customer acquisition funnel, focusing on lead acceptance and installation processes across three different cities. The analysis identifies key bottlenecks, variability in processes, and provides actionable recommendations to optimize operations.

## 📝 Executive Summary
You can find the detailed executive summary in the PDF document below:

[**Executive Summary**](Excitel_Case_ExecutiveSummary.pdf)

## 🧠 Problem and Observations

### Problem Statement
Excitel faces variability in lead acceptance rates and installation times across different cities, which could indicate inefficiencies or operational disparities that need to be addressed.

### Key Observations
- **Lead Acceptance**: The lead acceptance rates across cities are highly skewed, with significant imbalances and potential bottlenecks.
- **Installation Times**: Installation times vary widely, with some cities showing delays that may impact customer satisfaction.

### Visuals
- **Lead Acceptance Distribution**  
![image](https://github.com/user-attachments/assets/5fa93fe4-8279-46f2-a4d5-44c6574a262e)

- **Installation Time Distribution**  
![image](https://github.com/user-attachments/assets/49324126-f897-4294-8982-44e87f52d262)

## 🔍 Insights

### Lead Acceptance Analysis
- Normalizing the data through log and Box-Cox transformations revealed underlying patterns in lead acceptance rates, highlighting operational inefficiencies.
  
### Installation Time Analysis
- Confidence intervals for installation times across cities show significant overlap, suggesting common issues in the installation process.

### Correlation and Regression Insights
- A strong linear relationship between lead stages indicates that improving the qualification process can have a significant impact on final installations.
- **Regression Equation**: `Installed = 6.821 + 0.191 × Leads_Created`
- **Visuals**:
  - **Log-Transformed Distribution**  
    ![image](https://github.com/user-attachments/assets/874dd31c-71f8-4ad6-9bc3-36406beec1ca)

  - **Box-Cox Transformed Distribution**  
    ![image](https://github.com/user-attachments/assets/4a50540f-080c-4ed1-aa73-72052eae9c73)

  - **Regression Analysis**  
    (![image](https://github.com/user-attachments/assets/427ff243-8786-4fcf-b21f-a6ebc0fad682)

## 💡 Recommendations

### City-Level Recommendations
- **City 1**: Enhance the lead qualification process and leverage operational efficiency in installations.
- **City 2**: Revise marketing and lead management strategies to improve conversion rates.
- **City 3**: Focus on improving late-stage strategies and streamline operations to reduce installation times.

### Cross-City Strategy
- **Standardization**: Implement best practices from City 1's early-stage strategies and fast installation times across other cities.

### Next Steps
- **Process Improvement**: Invest in analytics tools for better tracking and dynamic adjustments.
- **Resource Optimization**: Analyze resource utilization to optimize allocations and replicate successful strategies across all cities.

## 📁 Files in This Repository

- **Code**: Python scripts used for data analysis, visualization, and model building.
- **Executive Summary**: A concise PDF summary of the findings and recommendations.

## Team Members

- [Aarushi Gosain](mailto:aarushi.gosain_pgp2025_25135@mastersunion.org)
- [Apoorv Kathuria](mailto:apoorv.kathuria_pgp2025_25183@mastersunion.org)
- [Dibyansu Mohanty](mailto:dibyansu.mohanty_pgp2025_25138@mastersunion.org)
- [Hari Shankar](mailto:hari.shankar_pgp2025_25220@mastersunion.org)
- [Sneha Roy](mailto:sneha.roy_PGP2025_25066@mastersunion.org)
- [Prakhar Gupta](mailto:prakhar.gupta_pgp2025_25187@mastersunion.org)

