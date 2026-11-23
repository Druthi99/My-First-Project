## Sales Dashboard – Restaurant Delivery Analytics

This is my first project on GitHub. It's a Power BI dashboard analyzing restaurant order and delivery performance, built to practice data modeling and DAX.

## Preview
<img width="1617" height="777" alt="image" src="https://github.com/user-attachments/assets/48f20879-3151-4023-aa6d-bae4831c974e" />
<img width="1630" height="785" alt="image" src="https://github.com/user-attachments/assets/335f8c9a-eb6e-4343-97c6-71a856e52a2a" />
<img width="1612" height="787" alt="image" src="https://github.com/user-attachments/assets/28603708-a0d3-49c9-832b-d4429ab68d36" />
<img width="1605" height="772" alt="image" src="https://github.com/user-attachments/assets/3cc18733-b797-4cac-880b-cf1be4a84e66" />

- **Summary** – KPI cards, revenue map, restaurant scatter Summary page
- **City** – revenue, orders and delivery time by city City page
- **Month** – monthly trends in revenue, orders and discounts Month page
- **Restaurant** – revenue, orders, discount and rating by restaurant Restaurant page

## About the Project
A 4-page Power BI report analyzing 86.8K+ food delivery orders across 10 restaurants in 4 cities. It tracks key metrics like Total Orders, Net Revenue, Average Order Value (AOV), Discounts, Delivery Time, and Customer Ratings — helping surface performance trends by city, restaurant, and month.

## Data
- **Period:** Jan–Dec 2015
- **Size:** 86,894 orders · 10 restaurants · 4 cities
- **Tables and relationships:** Order[Order_ID] → City[Order_ID]; City[Order_ID] → Customer[Order_ID]
- **Currency:** INR (₹); Cr = crore (10 million)
- **Data connection:** Excel files

## KPI definitions
- **Total Orders**	Count of all orders 
- **Net Revenue**	Total Revenue - Total Discount 
- **AOV**	Net Revenue ÷ Total Orders
- **Total Time**	Delivery time + preparation time, in minutes
- **Rating**	average customer rating, scale 1–5

## Key findings
- Delhi generated the highest revenue (₹1.34Cr) among the 4 cities; Barbeque Nation was the top restaurant by revenue.
- Average delivery + preparation time was ~33 minutes.
- At order level, delivery time and customer rating were essentially uncorrelated (Pearson r = -0.004, n = 86,894), suggesting delivery speed alone did not explain satisfaction
  
## Report Pages
- **Summary** – high-level KPI overview
- **City** – performance breakdown by city (includes a map visual)
- **Month** – trends over time
- **Restaurant** – performance by individual restaurant

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)

## File
- `Sales Dashboard.pbix` – open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

How to open: click "Download" on the file page (GitHub can't preview .pbix files), then open it in Power BI Desktop. 
