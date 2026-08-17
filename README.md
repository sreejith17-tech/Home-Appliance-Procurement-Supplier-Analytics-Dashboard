# Home-Appliance-Procurement-Supplier-Analytics-Dashboard
This project focuses on analyzing the procurement and purchasing activities of a home-appliance distributor that purchases products from multiple suppliers. The dataset contains six months of purchasing data across 9 suppliers, covering different categories such as AC, Television, Mixer Grinder, Refrigerator, Washing Machine, Microwave Oven, Air Cooler, and Ceiling Fan. The objective is to understand purchasing patterns, supplier contribution, product demand, purchasing costs, discounts, GST, payment modes, and delivery performance.

1. Data Collection & Dataset Preparation

The purchasing dataset was structured to represent real-world procurement transactions. It contains information such as purchase date, supplier ID, supplier name, product category, product model, quantity, unit price, discount percentage, GST percentage, total purchase amount, warehouse, and payment mode. Separate supplier-level sheets were maintained along with an All_Purchases master sheet for consolidated analysis.

2. Data Cleaning & Transformation Using Excel

Excel was used for the initial data preparation and analysis. The data was checked for missing values, duplicate records, inconsistent formats, incorrect data types, and inconsistent product or supplier information. Supplier IDs were standardized for all nine suppliers, and calculated fields such as total purchase amount, delivery delay days, and delivery status were created.

3. Purchase Analysis

The purchasing data was analyzed to identify monthly purchase trends, total purchase value, quantity purchased, product-wise purchases, category-wise spending, average unit price, discounts, GST, warehouse-wise purchases, and payment-mode distribution. This helped identify which products and categories contributed most to overall procurement.

4. Supplier Analysis

A major part of the project was supplier-wise procurement analysis. Each supplier was analyzed individually to understand their purchase value, quantity supplied, product categories, average unit price, discounts, and purchasing trends. A comparative supplier dashboard was also created to identify the highest-value supplier, highest-volume supplier, supplier contribution, and differences in purchasing costs and discounts.

5. Delivery & Status Analysis

Delivery-related fields were incorporated to analyze procurement fulfillment. Delay days were calculated by comparing the expected delivery date with the received date. Based on the delay information, products were categorized into statuses such as Delivered, On Delivery, Delayed, and Pending. This helps evaluate product-level and supplier-level delivery performance.

6. Power BI Dashboard Development

The cleaned and prepared data was imported into Power BI to develop an interactive Purchase Analytics Dashboard. The dashboard includes KPI cards, monthly purchase trends, supplier comparisons, product/category analysis, warehouse analysis, payment-mode analysis, discount and GST analysis, product quantity cards, and detailed purchase tables.

The report was designed with individual supplier analysis pages, allowing each supplier to be evaluated separately, along with a Supplier Comparison Dashboard for comparing all nine suppliers.

7. Key Business Questions Answered

The project helps management answer questions such as:

Which supplier has the highest purchase value?
Which supplier provides the highest quantity?
Which products and categories are purchased the most?
Which supplier offers better discounts?
Which products have the highest purchasing cost?
Which warehouse handles the highest procurement volume?
Which payment mode is used most frequently?
Which products experience delivery delays?
How does purchasing change month by month?
Which supplier should receive more procurement consideration?
8. Business Outcome

The final solution provides a centralized procurement analytics system that converts raw purchasing data into actionable business insights. It can help management monitor supplier performance, control purchasing costs, identify high-demand products, evaluate discounts, track delivery performance, and make better supplier and procurement decisions.

Technology Stack:
Microsoft Excel | Power BI | Power Query | DAX | Data Cleaning | Data Visualization | Procurement Analytics
