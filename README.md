# 🏝️ Dune Store Data Exploratory Data Analysis

##  Project Overview
This project presents an in-depth **Exploratory Data Analysis (EDA)** on Dune Store’s sales data.  
The goal is to uncover patterns, evaluate performance across dimensions like product, customer demographics, and time, and derive **data-driven business insights** that support growth, marketing, and strategic decisions.

### Key Business Questions
- Which products contribute most to profit and revenue?  
- How do customer demographics affect purchasing behavior?  
- What seasonal trends drive or hinder performance?  
- How do sales vary across time, region, and sales representatives?

---

##  Table of Contents
- [Project Overview](#-project-overview)
- [Tools & Libraries](#-tools--libraries)
- [ Data Cleaning & Preparation](#-data-cleaning--preparation)
- [🔍 Exploratory Data Analysis](#-exploratory-data-analysis)
  - [🔸 Univariate Analysis](#-univariate-analysis)
  - [🔸 Bivariate Analysis](#-bivariate-analysis)
  - [🔸 Multivariate Analysis](#-multivariate-analysis)
- [ Key Insights Summary](#-key-insights-summary)
- [ Recommendations](#-recommendations)

---

##  Tools & Libraries

**Programming Language:** Python  

**Core Libraries:**
- 🧮 **Pandas** → Data cleaning and manipulation  
- 📊 **Matplotlib & Seaborn** → Visualization and storytelling  
- ⚙️ **NumPy** → Numerical computation  
- 📓 **Jupyter Notebook** → Data exploration and reporting  

---

##  Data Cleaning & Preparation
The dataset underwent a comprehensive cleaning and preparation process to ensure data accuracy and quality.

**Steps Taken:**
- ✅ Removed duplicates and missing entries  
- ✅ Standardized date formats and extracted *Year-Month* features  
- ✅ Cleaned inconsistent category labels  
- ✅ Treated outliers in profit and cost columns  
- ✅ Derived new features for time-based and segment-based analysis  

These steps ensured **data consistency and readiness** for deeper analysis.

---

## 🔍 Exploratory Data Analysis

### 🔸 Univariate Analysis
Examined individual variables to understand their distribution and characteristics.

**Key Findings:**
- **Customer Value:** Most transactions came from low-value customers, but a small high-value group contributed significantly to profit.  
- **Salesperson Performance:** *Remota* consistently outperformed all others — nearly doubling *Kenny’s* sales, suggesting better conversion skills or stronger customer targeting.  
- **Age Distribution:** Ages *28–38* dominated sales volume, followed by *39–48*, showing that middle-aged adults are the store’s primary customer base.  
- **Gender Distribution:** Sales were almost evenly split between male and female customers, indicating balanced market appeal.  
- **Regional Distribution:**  
  - 🏙️ **Lagos** → Highest sales and profit  
  - 🏛️ **Abuja** → Second highest performance  
  - 🌍 **Benue** → Lowest sales, potential market gap  

---

### 🔸 Bivariate Analysis
Assessed relationships between pairs of variables.

**Highlights:**
- **Revenue vs. Profit:**  
  Strong positive correlation — higher revenue generally leads to higher profit. However, some categories (like phones) show high revenue but low profit margins.  
- **Region vs. Profit:**  
  Lagos and Abuja deliver the highest profits, while smaller regions underperform due to weaker purchasing power or fewer outlets.  
- **Salesperson vs. Revenue:**  
  Significant variation — top reps generate disproportionately higher revenue, showing potential for peer-based training.  
- **Age vs. Profit:**  
  Profit tends to rise with age, suggesting older customers make higher-value purchases.

---

### 🔸 Multivariate Analysis
Explored how multiple factors interact to shape outcomes.

**Insights:**
- **Category, Cost & Profit Relationship:**  
  - 👜 **Accessories** → Highest overall profit with moderate cost and revenue  
  - 📱 **Phones** → High revenue but thin margins (pricing issue)  
  - 👕 **Clothing** → Consistent performer but not top in profit  

- **Monthly & Yearly Trends:**  
  - Losses were recorded in early 2015, but profitability began in *July 2015* and grew steadily through *2016*.  
  - Revenue slightly dipped mid-year, but profit rose — suggesting better **cost control** or **optimized product mix**.  

- **Gender & Age Interaction:**  
  - The *71–81 age group* recorded the highest average profit per transaction for both genders.  
  - Indicates older demographics prefer premium or high-margin items.  

- **Revenue & Profit by Product & Region:**  
  - Accessories outperform all regions.  
  - Phones dominate revenue charts but lag in profit.  
  - Urban regions (Lagos, Abuja) show stronger financial performance overall.  

---

##  Key Insights Summary

| **Focus Area** | **Insight** | **Business Implication** |
|----------------|-------------|---------------------------|
| **Product** | Accessories are the most profitable; Phones bring high revenue but low profit. | Prioritize accessories and re-evaluate phone pricing or sourcing. |
| **Region** | Lagos and Abuja dominate; Benue lags behind. | Focus marketing and logistics on high-performing areas; explore growth in underperforming regions. |
| **Customer Age** | 28–38 years lead in purchases; 71–81 years lead in profit per sale. | Tailor promotions by age group — bulk discounts for mid-aged buyers, premium offers for older customers. |
| **Salesperson** | Strong disparity in sales performance. | Develop training based on top performers’ methods. |
| **Time Trend** | Revenue dips mid-year, profit rises after July. | Optimize mid-year inventory and campaigns around profitable months. |

---

##  Recommendations

Based on the findings, the following strategies are proposed:

1. **Optimize Product Pricing:**  
   Investigate low margins on phones; renegotiate vendor contracts or adjust pricing models.  

2. **Focus on Accessories:**  
   Increase stock and marketing around high-profit categories.  

3. **Customer Segmentation:**  
   Design loyalty programs for older, high-value customers (71–81).  

4. **Leverage Seasonal Insights:**  
   Plan campaigns post-July to maximize profit trends.  

5. **Empower Sales Reps:**  
   Use top performers as internal mentors to boost overall conversion rates.  

6. **Regional Expansion:**  
   Strengthen brand presence in weaker regions through localized promotions and distribution.  

---

 **Author:** *Muhammad Abdus-Salam*  
 Data Scientist | Machine Learning Enthusiast  
