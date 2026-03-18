# U.S. E-Commerce Sales Analytics Dashboard (2019)

An end-to-end sales analytics project analyzing 185,916 transactions across 19 products and 9 U.S. cities. Built with Google Looker Studio, powered by Python data pipelines.

**[View Live Dashboard →](YOUR_LOOKER_STUDIO_LINK)**

---

## Project Overview

| | |
|---|---|
| **Data** | 185,916 orders · 19 products · 9 U.S. cities · Full year 2019 |
| **Tools** | Google Looker Studio · Python (pandas) · Jupyter Notebook |
| **Output** | 6-page interactive dashboard + bilingual insight report (EN/VI) |

---

## Key Findings

### 1. Volume-Driven Business Model
Revenue growth is driven by **order volume, not price**. AOV remains stable at ~$193 year-round. Top 3 subcategories (Laptops, Phones, Monitors) consistently account for **~80% of revenue** across all seasons, months, and time of day — product mix is a structural constant.

### 2. Revenue Cycle — 3 Distinct Phases
| Phase | Period | Revenue Range |
|---|---|---|
| Growth | Jan → Apr | $1.81M → $3.39M |
| Decline | May → Sep | $3.39M → $2.80M (2-wave pattern) |
| Surge | Oct → Dec | $3.74M → $4.61M (twin peaks at Oct & Dec) |

### 3. Twin Peak Purchasing Pattern
Online shopping forms a **"Twin Peak" model** daily — 51.9% of all orders concentrated in just 8 hours:
- **Noon zone (10–13h):** Built up from commute → tab shopping → lunch break burst
- **Evening zone (18–21h):** Single concentrated burst — home, relaxed, longest free time of day
- **Golden Hour:** 19:00 is the absolute daily peak, hottest in 5/7 days on the heatmap

### 4. Product Mix = Dual Constant
SubCategory share is virtually **identical across all hours AND all months** (Laptops always ~35%, Phones ~26%). Time of day changes *how many* people buy — not *what* they buy.

---

## Dashboard Pages

| # | Page | Key Question |
|---|---|---|
| 1 | Sales Performance Overview | Revenue cycle, monthly trends, Growth/Decline/Surge phases |
| 2 | Purchasing Time Patterns | When do customers buy? Twin Peak model, hourly heatmap |
| 3 | Geographic Analysis | Which cities drive revenue? |
| 4 | Order Segmentation & Pricing | AOV distribution, order size patterns |
| 5 | Market Basket Analysis | Which products are bought together? |
| 6 | Product Performance | SubCategory breakdown, top products |

---

## Repository Structure

```
├── README.md
├── BI_Sales_Main.csv               # Main transaction data (185,916 rows, 2019 only)
├── BI_Order_Summary.csv            # Aggregated order-level data
├── BI_Product_Dim.csv              # Product dimension table
├── BI_Association_Rules.csv        # Market basket association rules
├── BI_Category_CoOccurrence.csv    # Category co-occurrence matrix
├── BI_SubCategory_CoOccurrence.csv # SubCategory co-occurrence matrix
├── Data_Dictionary.csv             # Field definitions
├── market_basket_analysis.ipynb    # Python notebook: association rules
└── E-Commerce Sales Report.docx    # Full bilingual insight report (EN + VI)
```

---

## Highlights

- **Built a 6-page Looker Studio dashboard** on 185K+ transactions, identifying a Volume-Driven business model where Top 3 products consistently contribute ~80% of revenue across all seasons.
- **Identified a "Twin Peak" purchasing pattern** through 7-segment hourly behavioral analysis, revealing that 51.9% of orders concentrate in 8 hours — and that product mix remains constant across all time slots, disproving the assumption that evening shoppers buy more expensive products.
- **Delivered bilingual insight reports** (EN & VI) with data-validated findings: SubCategory-level breakdowns, AOV analysis, and month-over-month comparisons across Growth, Decline, and Surge revenue phases.

---

*Tools: Python · pandas · Google Looker Studio*
