# AtliQ Business Insights – Power BI Analytics Suite  
### Enterprise Dashboard | Sales • Finance • Supply Chain • Marketing • Executive View  

This repository contains the full analytics solution built for **AtliQ** using Power BI.  
The project consists of 5 enterprise dashboards designed to help leadership teams monitor  
performance across **Sales, Marketing, Finance, Supply Chain, and Executive KPIs**.

The entire data model was validated end-to-end to ensure accuracy, reliability, and real-world usability.

---

## 🚀 Project Overview

The goal was to build an enterprise-grade BI system that enables AtliQ’s leadership to:

- Track **Net Sales, Gross Margin%, Net Profit%**
- Evaluate **market share & competitor performance**
- Monitor **forecast accuracy, net error & ABS error**
- Assess **customer & product profitability**
- Review **P&L statement performance**
- Analyze **supply chain accuracy & forecast errors**
- Compare **FY, LY, YTD, YTG** performance
- Enable **drill-down by region, market, customer & segment**

---

## 🏗️ Data Model

- **Star Schema** with:
  - `fact_actuals_estimate`
  - `fact_forecast_monthly`
  - `dim_customer`
  - `dim_product`
  - `dim_market`
  - `dim_date`
  - 'marketshare'
  - 'NsGmTarget'
  - 'Operational Expense'
  - 'freight_cost'
  - 'manufacturing_cost'
  - 'post_invoice_deductions'
  - 'fiscal_year'
  - 'sub_zone'
    
- Clean relationships, no circular dependencies.
- Optimal cross-filtering (single direction).
- Validated keys: Customer, Product, Market, Date.

### 📂 Repository Structure

📁 AtliQ-Business-Insights
│── README.md
│── INSIGHTS.md
│── VALIDATION.md
│── 📁 Dashboard Screenshots
│── 📁 Data Model
│── 📁 DAX Measures
│── 📁 Source Files


---

## 🧪 Data Validation Summary

Detailed validation is available in `VALIDATION.md`.

Key checks performed:

✔ Row Count Validation  
✔ DISTINCTCOUNT Key Integrity  
✔ Fact–Dimension Mapping  
✔ Date Range Validation (2017–2022)  
✔ Null & Duplicate Check  
✔ Data Type Validation  
✔ Business Rules (No negative sales, valid dates, unique codes)

**Conclusion:**  
✔ Dataset is clean, accurate, and analytics-ready.
(https://github.com/atishayjain777/Atliq_PowerBI_Analytics/blob/main/%F0%9F%93%84%20Atishay_Atliq_VALIDATION.md.txt)
---

## 📊 Dashboards Included

### 1️⃣ **Executive View Dashboard**
A high-level summary for CXO & VP-level stakeholders:

- Net Sales, GM%, Net Profit% (FY vs LY vs BM)
- Market Share Trend (AtliQ vs Competitors)
- Key Insights by Region / Sub-Zone
- Revenue Distribution by Division & Channel
- Top 5 Customers & Products by Revenue
- Yearly Trend Analysis (NS$, GM%, NP%)

### 2️⃣ **Sales View Dashboard**
Focused on customer performance & product-level sales:

- Net Sales Trend (vs LY & vs Target)
- P&L Line Item Summary
- Top/Bottom Customer & Product Contribution
- Customer Performance Matrix (GM% vs NS$)
- Product GM% & Profitability Drivers

### 3️⃣ **Marketing View Dashboard**
Evaluating market segmentation & brand strength:

- PC Market Share Trend
- Customer penetration analysis
- Sub-Zone insights (NS%, GM%, NP%)
- Brand performance vs competitors

### 4️⃣ **Supply Chain View Dashboard**
End-to-end forecast accuracy & risk assessment:

- Forecast Accuracy %, Net Error, ABS Error
- Key Metrics by Customer & Product
- Accuracy & Net Error Trend
- Customer/Product Risk Flags (EI / OOS)
- Supply chain reliability KPIs

### 5️⃣ **Finance View Dashboard**
Full financial transparency including:

- Profit & Loss Statement  
- COGS Breakdown  
- Gross Margin & Operating Expense variance  
- Net Profit Bridge  
- Region / Customer / Product financials  
- Unit Economics Dashboard

---

## 📐 Key DAX Measures Used

- Net Sales  
- Gross Margin %  
- Net Profit %  
- Forecast Accuracy %  
- Net Error  
- ABS Error  
- LY, FY, YTD, YTG comparisons  
- Target Achievement %
 
➡ Full code included in `/DAX Measures/`.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- Power Query
- DAX Studio
- MS Excel
- Power BI Sevice
- GitHub for version control

---

## 🧾 Business Impact

This analytics suite enables AtliQ to:

- Improve forecast accuracy & reduce supply chain risks  
- Identify high-value customers & declining accounts  
- Optimize product-level profitability  
- Track financial KPIs in real-time  
- Strengthen market competitiveness  
- Enable data-driven executive decision-making  

---

## 👨‍💻 Developed By

**Atishay Jain**  
Power BI Developer  
AtliQ Business Insights Project  
