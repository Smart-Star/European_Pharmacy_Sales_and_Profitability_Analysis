# 🏥 European Pharmacy Sales & Profitability Analysis

An interactive three-page Power BI dashboard designed for commercial leadership to monitor sales volume, profit margins, product hierarchy, and regional contributions across European pharmacy distribution branches.

---

## 🔗 Live Interactive Report
👉 **[View Published Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDViODk1NzctYjk3NC00MmQwLTk5M2UtNmEwMzE5MGMwNGE2IiwidCI6IjkyNWU0ZDViLTk4ZmYtNDc4NWU3LTU2NjAwM2VhM2VhM2ViIn0%3D)**

---

## 🎯 Project Overview & Key Metrics

This end-to-end Power BI report transforms daily transactional data into strategic insights across **3 interactive navigation pages**:

* **Total Revenue:** €8.63M *(▲ €383.51K vs. Previous Month)*
* **Total Cost:** €6.21M *(▲ €274.29K vs. Previous Month)*
* **Total Margin:** €2.42M *(Overall Margin %: 28%)*
* **Total Units Sold:** 446K units *(62K Total Sales Volume)*
* **Pharmacies Below Target Margin:** 2 locations

---

## 🖥️ Dashboard Views & Architecture

### 1️⃣ Overview Page
Focuses on macro-level KPI cards, dynamic monthly trend lines, geographic revenue distribution across Europe, top-performing countries, and baseline promotion revenue splits.

![Performance Overview](EPSPA_1.png)

* **Key Takeaway:** Germany leads total country revenue, followed closely by France, Italy, Belgium, and the Netherlands. Promoted sales account for **10.55% (€0.91M)** of total revenue, while non-promoted baseline sales represent **89.45% (€7.72M)**.

---

### 2️⃣ Regional Performance Page
Enables detailed geographic evaluation using location sparklines, top cities by cost/margin, pharmacy type comparisons (Urban vs. Suburban vs. Rural), and an interactive **Decomposition Tree** drill-down (`Country` → `Region` → `City` → `Pharmacy`).

![Regional Performance](EPSPA_2.png)

* **Key Takeaway:** Urban pharmacies dominate overall sales volume (**29.6K units**), followed by Suburban (**22.4K units**) and Rural (**10.2K units**). Milan, Hamburg, and Utrecht stand out as key drivers in regional contribution.

---

### 3️⃣ Product & Brand Performance Page
Evaluates product category margins, top brands by revenue and profit, scatter plot distribution (Volume vs. Profitability), conditional formatted product tables, and promotional efficiency.

![Product Performance](EPSPA_3.png)

* **Key Takeaway:** **Prescription** products generate the highest absolute revenue and total margin, followed by **Wellness** and **OTC** categories. **AntiBioX** is the top-performing brand in both revenue (**€55K**) and margin (**€13.0K**). Non-promoted sales demonstrate higher overall sales volume (**4.5K**) compared to promoted sales (**0.6K**).

---

## 🛠️ Data Modeling & Technical Features

* **Custom DAX Measures:** Developed metrics for Month-over-Month (MoM) performance shifts, margin percentages, conditionally formatted KPI indicators, and dynamic filter resets.
* **UX/UI Visual Hierarchy:** Standardized color palette with custom-designed visual cards, tab navigation controls, hover states, and dynamic sparklines.
* **Hierarchical Drill-Downs:** Implemented interactive map layers, dynamic scatter plots, and custom decomposition trees for rapid root-cause analysis.

---

## 💡 Strategic Business Recommendations

1. **Optimize Promotional Mix:** Since 89.45% of total revenue is generated through non-promoted channels, evaluate whether promotional discounts are driving net-new customer acquisition or unnecessarily eroding profit margins on high-volume items.
2. **Targeted Inventory Allocation for Urban Centers:** Focus top-tier prescription and wellness inventory toward high-volume Urban locations, which drive nearly half of total branch unit sales.
3. **Address Underperforming Branches:** Focus operational support on the **2 pharmacies currently falling below target margin limits** to restore regional balance.
