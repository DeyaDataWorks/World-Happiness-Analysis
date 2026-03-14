Markdown
# Analysis of the Social and Economic Impact on the Well-being of Peoples
**A Data-Driven Study of the World Happiness Report (2015-2019)**

**Author:** Rabah | Deya DataWorks

## 📌 Executive Summary
This project aims to analyze global happiness levels to understand the underlying factors contributing to the overall well-being of nations. By evaluating economic indicators (such as GDP per capita) alongside social indicators (such as social support, health, and freedom), this analysis provides data-driven insights for global decision-makers and NGOs.

The project strictly adheres to the Google Data Analytics framework, following the six core phases: Ask, Prepare, Process, Analyze, Share, and Act.

## 🛠️ Feature Engineering & Core Insights
A significant analytical step in this project involved programmatic feature engineering to categorize economic classes. Since the raw dataset lacked a binary group column, the GDP was split based on the median value:
- **Above Median:** Categorized as "Rich"
- **Below Median:** Categorized as "Poor"

While this engineered feature allowed for the testing of wealth's relationship with well-being, the exploratory data analysis (EDA) revealed a crucial nuance: **High happiness does not necessarily mean a person or society is rich.** The data demonstrates that while GDP is a primary driver, robust social support systems and community ties act as powerful equalizers for overall life satisfaction, proving that wealth is not the sole definitive metric for a happy population.

## ⚙️ Technologies & Tools
- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly (Choropleth maps)
- **Statistical Analysis:** SciPy (ANOVA testing)
- **Environment:** Jupyter Notebook

## 📂 Data Sources
The analysis utilizes the open-source "World Happiness Report" datasets (2015-2019) under a CC0 license. Data integrity was verified using the ROCCC framework. *(A comprehensive Data Dictionary is included within the Notebook).*

## 🚀 How to Run Locally
To reproduce this analysis or review the code, please follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/DeyaDataWorks/World-Happiness-Analysis.git]
   cd World-Happiness-Analysis
Install the required packages:
Ensure you have the necessary libraries installed to run the notebook without errors:

Bash
pip install pandas numpy matplotlib seaborn plotly scipy
Run the Notebook:
Launch your Jupyter environment and open the project file:

Bash
jupyter notebook my_first_project.ipynb
📊 Key Findings & Recommendations
Targeted Regional Interventions: Statistical testing confirms a severe, non-random geographic developmental gap. International aid and global development programs must disproportionately target lower-performing regions with economic subsidies rather than relying solely on social programs.

Protect Social Safety Nets: For developed nations with high GDP, maintaining and strengthening community ties is the critical differentiator required to remain in the "High Happiness" tier.

🔮 Future Work
Post-Pandemic Impact: Integrating datasets from 2020-2024 to analyze how the global COVID-19 pandemic and subsequent inflation disrupted the established correlation between GDP and happiness.

Predictive Machine Learning: Transitioning from descriptive to predictive analytics by deploying algorithms (e.g., Random Forest) to forecast a nation's future happiness trajectory based on socio-economic policy shifts.