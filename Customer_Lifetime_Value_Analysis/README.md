# Customer Lifetime Value for Logistics — Prioritizing Supermarket Accounts

##  Project Objective
Python Logistics needed to evaluate supermarket customers to determine **which accounts deliver the highest long-term value** and how to **allocate limited trucking capacity efficiently**.  
This project builds a **customer valuation and targeting framework** using **RFM scoring, predictive choice models, and discounted CLV with transition matrices**.

---

## Methods & Approach
1. **RFM Scoring Model**  
   - Weighted Recency (20%), Frequency (40%), Monetary (40%)  
   - Segmented supermarkets into A/B/C tiers.  

2. **Choice Modeling (Predictive Targeting)**  
   - Logistic/multinomial regression to estimate probability of staying High Value.  
   - Decile ranking to design differentiated service levels.  

3. **Transition Matrix with Discounted CLV**  
   - Modeled customer movement between High/Medium/Inactive states.  
   - Applied a 10% discount rate to compute long-term value.  

---

## Insights & Recommendations
- **Truck Allocation:** prioritize A-tier/high-probability customers.  
- **Retention:** flag customers with declining recency/frequency for proactive outreach.  
- **Revenue Strategy:** medium-spend but persistent customers can outperform short-term big spenders.  

---

## Files
- `Rcha490_CLV.pdf` — full report  
- `README.md` — this project overview

