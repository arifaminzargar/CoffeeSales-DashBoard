### “Coffee Sales Dashboard (2019–2022)”

🚀 Just wrapped up an exciting Coffee Sales Dashboard project in Excel! ☕📊

Here’s how I turned raw sales data into actionable insights using data cleaning, enrichment, and visualization techniques:


✅ Data Formatting, Cleaning & Analysis Summary
🔧 Data Cleaning & Formatting

Formatted the Order Date column as dd-mmm-yyyy (e.g., 05-Sep-2019) for better readability.

Added a Sales column by calculating Quantity × Unit Price to derive total order value per line item.

Created Coffee Type Name and Roast Type Name columns by mapping coded values to readable labels (e.g., Ara → Arabica, M → Medium).

Applied number formatting for better interpretation:

Size column formatted with a kg suffix (e.g., 1.0 kg).

Unit Price and Sales columns formatted with a $ symbol (e.g., $12.95).

🔗 Data Enrichment Using Formulas

Used XLOOKUP in the orders table to fetch:

Customer Name

Email

Country
Loyalty Card
based on Customer ID from the customers sheet.

Applied INDEX + MATCH to dynamically pull:

Coffee Type

Roast Type

Size
Unit Price
based on Product ID from the products sheet.

📊 Data Analysis Enhancements


Added 4 slicers for interactive analysis:

Coffee Type Name

Roast Type Name

Size

Loyalty Card

Enabled deeper insight through summary visuals on:

Total Sales Over Time

Sales by Country

Top 5 Customers

Coffee Type Preference 

Roast Type Preference

Customer Loyalty Sales Card

Quantity sold by size


Chart-specific insights and real-world business recommendations:

🔹 1. Top 5 Customers (Bar Chart - Horizontal)
Chart Insight:

The top customer is Allis Wilmore with $317 in sales.

The sales gap between top 5 customers is minimal (~$40 difference).

Recommendation:

Personalized loyalty incentives (e.g., discounts, early access) can retain top customers.

Encourage referrals through top buyers to leverage their influence.

🔹 2. Quantity Sold by Size (Vertical Bar Chart)
Chart Insight:

0.5 kg packs are the most sold (943 units), followed by 0.2 kg and 1.0 kg.

2.5 kg is the least sold.

Recommendation:

Promote combo offers for larger sizes (like 2.5 kg) to improve sales.

Use 0.5 kg as the default recommendation in online ordering for faster conversions.

🔹 3. Customer Loyalty Card Sales
Chart Insight:

Surprisingly, non-loyalty customers ($24,216) have higher total sales than loyalty customers ($20,918).

Recommendation:

Audit loyalty program value—ensure it provides visible benefits to customers.

Improve awareness and enrollment—e.g., through POS promotions or app nudges.

🔹 4. Coffee Type Preference
Chart Insight:

Excelsa ($12,306) and Liberica ($12,054) have higher sales than Arabica and Robusta.

Robusta has the lowest preference.

Recommendation:

Market Excelsa and Liberica prominently; emphasize their taste profiles.

Use bundle deals to promote Robusta and improve its visibility.

🔹 5. Total Sales Over Time (Line Chart)
Chart Insight:

Peak sales in 2021 ($13,766).

Sharp decline in 2022 to $7,063, nearly half of 2021.

Recommendation:

Investigate 2022 drop—possible causes: price hikes, supply issues, competition.

Implement seasonal campaigns to regain lost momentum in future years.

🔹 6. Sales by Country
Chart Insight:

U.S. dominates with $356 in sales; Ireland ($67), UK ($28) are negligible.

Recommendation:

Focus on geo-expansion strategies—localized ads, region-specific flavors, or promotions in UK/Ireland.

Consider regional partnerships with local cafés or online delivery platforms.

🔹 7. Roast Type Preference
Chart Insight:

Light roast is the most popular ($17,354), followed by Medium ($14,600) and Dark ($13,179).

Recommendation:

Feature light roast in promotional materials and top placements.

Explore launching new variants or blends under light roast category.

🔹 8. KPI Cards (Top)
Total Quantity Sold: 3,551 units

Total Sales: $45,134.26

Average Sales per Customer: $49.44

Recommendation:

Use average sale value to set personalized upsell targets in email campaigns.

Aim to increase average sales per customer by 10–15% via bundling or upselling.

✅ Overall Business Recommendations:
Area	Recommendation
Loyalty Program	Improve benefits and communication to encourage higher adoption.
Product Strategy	Focus marketing on Excelsa & Liberica; revive Robusta via bundles or deals.
Sales Recovery	Investigate sharp 2022 decline and boost sales via targeted campaigns.
Geographic Focus	Explore marketing and sales channels in underperforming countries.
Customer Retention	Engage top 5 customers with exclusive deals or referrals.
Size Promotions	Push sales for 2.5 kg via value packs or family-size offers.




