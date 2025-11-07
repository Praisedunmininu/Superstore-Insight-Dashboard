# Superstore Sales Performance Dashboard
---

## Project overview
This project analyzes sales and profit performance across different business areas in a retail superstore dataset.
The dashboard helps identify which categories, sub-categories, products, customer segments, and regions are performing well and which ones are under-performing.

---
## Recommendations

Based on the analysis of overall Superstore performance across - Product,region.Categorie, Sub-categories, here are actionable insights for Superstore:

1. Products to Target
   
Focus on high-profit, high-sales items like:

Canon ImageClass 2200 Advanced Copier

Fellowes PB500 Electric Punch Plastic Comb

HP LaserJet 3310 Copier

Within categories, Technology and Office Supplies are performing the best — prioritize these for promotions and inventory.

2. Products to Avoid or Review
   
- Be cautious with low-profit or loss-making items, such as:
  
- Boxoffice by design rectangular and Half meeting room table
   
- Balt solid wood round table
  
- Martin yale chadless opener ekectric letter opener
  
Also, review products with very high discounts (above 30%), as these are hurting profit margins.

3. Customer Segments to Focus On
   
 - Corporate and Consumer segments drive the most profit — target these for campaigns.
   
-  Home Office segment is smaller but profitable — use selective promotions.

4. Regions to Target

West and East regions generate strong revenue and profit — allocate resources accordingly.

South and Central regions underperform — investigate causes or limit investments until performance improves.

5. Discount Strategy

Apply strategic discounts only when necessary.

---

## Summary of Findings

Technology category generates the highest sales and profit with relatively lower discount rates.

Office Supplies also performs well but with slightly higher discounts.

Furniture has high sales but very low profit, suggesting high costs or heavy discounting.

Consumer Segment contributes the highest sales and profit, followed by Corporate, then Home Office.

Some products generate strong profit, while others result in consistent losses, which helps guide product improvement or removal decisions.

The performance across the region is not balanced , some regions make high profit while other make much less.

---

## Tools Used
| Tool | Purpose |
|-----|---------|
| Excel | Initial data inspection and import |
| Power BI | Data cleaning, modelling, and dashboard visualization |
|Power Query (Power BI Editor)** | Data cleaning and transformation

---

## Key Analysis Areas
Analysis Area |	 What Was Compared 	    |  Insight Purpose
Category	      Sales, Profit, Discounts	   To see which  product groups perform best
Sub-Category   Profit (with conditional formatting)	  To identify top and low performing product types
Product Level	  Top 10 & Bottom 10 by Profit	     To highlight best-sellers and product losses
Customer Segment	 Sales, Profit & Avg Discount	  To understand who contributes the most revenue
Region	          Profit & Sales comparison	      To identify best and weakest markets

---

## Data Cleaning Steps (Power Query)

- Standardized text fields for consistency
- Converted data types (dates, currency, etc.)
- Cleaned product and category names for consistency 

---

## Dashboard Insights

## **Top Performing Products**
The best-performing products in terms of profit are:
- Canon ImageClass 2200 Advanced Copier
- Fellowes PB500 Electric Punch Plastic Comb
- Hewlett Packard LaserJet 3310 Copier

## **Lowest Performing Products**
The products generating low or negative profit include:
- Boxoffice by design rectangular and Half meeting room table 
- Balt solid wood round table
- Martin yale chadless opener ekectric letter opener
- 

### **Profit Conditional Formatting**
The profit column was formatted using:
- **Black** = High profit
-  **Pink** = Loss or negative profit

---

##  Project Files in This Repository
| File/Folder | Description |
|------------|-------------|
| `/screenshots/` | Contains screenshots of the dashboard visuals |
| `Superstore_Dashboard.pbix` | Power BI report file |
| `Cleaned_Dataset.xlsx` | Cleaned dataset used for analysis |
| `Project_Cover_Document.pdf` | Summary/cover document |

---

##  Key Learnings
- How to clean and transform data using **Power Query**
- Creating **Matrix**, **column Chart**, and **donut chart**
- Applying **conditional formatting** to highlight performance
- Designing a clean and business-friendly dashboard layout

---

## How to View the Dashboard
1. Download `Superstore_Dashboard.pbix`
2. Open it in **Power BI Desktop**
3. Explore insights interactively



### ⭐ Feel free to give this repository a star if you find it useful!
