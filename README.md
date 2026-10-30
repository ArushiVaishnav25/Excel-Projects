# Telco Customer Churn Analysis (Excel)
End-to-end Excel analysis of 7,043 telecom customers: data cleaning, PivotTable analysis, a validated churn risk score, a What-If retention model and a one-page interactive dashboard.

**Business question:** Which customers are likely to leave, how much revenue is at risk, and which retention offer would pay for itself?

## Results

| Metric | Value |
|---|---|
| Churn rate | 26.5% (1,869 of 7,043 customers) |
| Revenue lost to churn | $1.67M a year |
| Active high-risk customers | 628, holding $595K a year |
| Retention offer net gain | +$74.8K a year, profitable in 25 of 30 scenarios |

## Key findings

- **Month-to-month** customers churn at **42.7%** vs **2.8%** on two-year contracts, and drive **87%** of lost revenue
- **47.4%** of first-year customers leave
- **Fiber** churns about **2x** DSL, even on the same contract type
- Churn falls from **52.2%** with no extra services to **5.3%** with all six
- Price is not the main driver; **competitor offers, service quality and support staff** explain **76%** of churn
- A 5-factor risk score is validated on the data: churn rises from **2.5%** to **72.3%**

## What I did

- **Cleaning:** set 11 blank Total Charges (new customers) to 0; removed constant and unused columns; added helper columns (Tenure Band, Addon Count, Reason Group, Risk Score)
- **Analysis:** 12 PivotTables and cross-tabs comparing churn by contract, tenure, internet service, payment method, add-ons, price and reasons
- **Risk score:** one point per churn driver found in the analysis, validated against actual churn
- **What-If model:** sized a 10% contract-upgrade offer for high-risk customers and stress-tested it with a 30-scenario Data Table
- **Dashboard:** KPI cards, 4 charts and slicers on one page

## Files

| File | Description |
|---|---|
| `Telco_Churn_Analysis.xlsx` | Full workbook; its README sheet has the cleaning log and assumptions |
| `Dashboard.pdf` | One-page dashboard |
| `Telco Dashboard.png` | Dashboard screenshot |

Download the `.xlsx` and open it in Excel to use the interactive slicers.

**Data:** [IBM Telco Customer Churn sample dataset](https://community.ibm.com/community/user/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)

**Author:** Arushi Vaishnav · [LinkedIn](https://linkedin.com/in/arushivaishnav)
