# ecommerce-store-sales-analysis-excel
Annual ecommerce sales report built in Excel —  customer demographics, channel performance &amp;  state-wise revenue breakdown using Pivot Tables &amp; Slicers.

# 🛍️ Ecommerce Store Data Analysis | Excel Project

## About This Project

This was an annual sales analysis project for an ecommerce store 
covering the full year of 2022. The goal was straightforward — 
understand who is buying, from where, through which platform, 
and give the store something actionable to act on for 2023.

The dataset had 31,047 rows across 19 columns covering order IDs, 
customer demographics, sales channels, product categories, 
shipping states, and order status. Everything from data cleaning 
to the final dashboard was done in Excel.

Total Revenue Analyzed: ₹2.11 Crore+ across 12 months.

---

## What I Was Trying to Find Out

These were the actual business questions I built the analysis around:

- Are men or women buying more — and by how much?
- Which age group is placing the most orders?
- Which states are generating the highest sales?
- Which platform — Amazon, Flipkart, Myntra etc. — 
  is driving the most orders?
- What is the order fulfillment rate? How many got 
  cancelled, returned, or refunded?
- Which months had the highest sales activity?
- What product categories are most popular?

---

## What I Actually Did — Step by Step

**Data Cleaning**
- Removed irrelevant columns like currency and ship-country 
  since the entire dataset was India-specific
- Checked and removed duplicate records
- Handled null and incomplete values
- Fixed typographical errors in Gender and Size columns 
  (e.g. inconsistent entries like "M" and "Men" for the same value)

**Data Processing**
- Age column alone wasn't useful for analysis so I created 
  an Age Group bucket column using:
  =IF(E2>=50,"Senior",IF(E2>=30,"Adult","Young"))
- Extracted Month from the date column for month-wise 
  trend analysis using:
  =TEXT(H2,"mmm")

**Data Analysis — Pivot Tables Built**
- Order vs Sales (monthly trend)
- Order Status breakdown
- Top 10 States by Sales
- Men vs Women comparison
- Age vs Gender relationship
- Channel-wise sales share

**Final Report**
- Merged all pivot tables into one dashboard
- Connected everything using Slicers with Report Connections 
  so the entire dashboard filters together from one click

---

## Key Findings

A few things that stood out once the data was cleaned and analyzed:

- **Women dominate the buying** — 69% of orders came from 
  women vs 31% from men. This wasn't surprising but the 
  gap being this wide was.

- **Adults aged 30-49 are the core customer base** — 
  this age group contributed roughly 50% of all orders. 
  Young buyers existed but weren't the primary revenue driver.

- **Maharashtra, Karnataka, and Uttar Pradesh** were the 
  top 3 states by revenue. Maharashtra alone led by a 
  significant margin.

- **Amazon was the dominant channel** with 11,016 orders — 
  nearly double Myntra (7,254) and Flipkart (6,703).

- **92% order fulfillment rate** — 28,641 out of 31,047 
  orders were successfully delivered. Returns and cancellations 
  were relatively low which is a healthy sign.

- **Sets and Kurtas** were the most ordered categories — 
  which aligns well with the women 30-49 buyer profile.

---

## Final Recommendation Given to Client

Target women customers aged 30-49 living in Maharashtra, 
Karnataka, and Uttar Pradesh by running ads, offers, and 
coupons specifically on Amazon, Flipkart, and Myntra — 
since that is where this exact audience is already buying.

---

## Tools Used

- **Microsoft Excel** — Data cleaning, processing, Pivot Tables, 
  Functions , formulas, Slicers, Dashboard design, Powerpivot, Data Modelling


---

## Excel Concepts Covered

- Data Cleaning techniques (duplicates, nulls, typo fixes)
- IF & nested IF formulas for age grouping
- TEXT formula for date extraction
- Pivot Tables — multiple tables from one dataset
- Slicer + Report Connection for interactive filtering
- Dashboard layout and design within Excel

  📸 Screenshots
  
  <img width="1223" height="622" alt="Screenshot 2026-04-02 045407" src="https://github.com/user-attachments/assets/5e702a02-d9fc-4fe7-9494-90d58fbddacc" />
