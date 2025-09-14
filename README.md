## **Sales Performance Analysis Using SQLite and Pandas**

###  **Project Summary**

In this project, Ie built a **Sales Performance Dashboard** using Python’s Pandas library and SQLite. The dataset contained transactional data including products, quantities sold, and prices. The goal was to extract meaningful insights by aggregating data at the product level and visualizing it using bar graphs to understand overall sales performance.

The key steps included:

1. **Data Extraction:** Loaded sales data from a SQLite database into Pandas.
2. **Data Aggregation:** Used SQL queries to group the data by product, calculating total quantities sold and total revenue.
3. **Data Visualization:** Displayed the aggregated results using a bar graph to highlight top-selling products.
4. **Insights Generation:** Interpreted the data to identify trends and actionable recommendations.

---

###  **Dataset Columns**

* `product`: Name of the product sold.
* `total_qty`: Total quantity sold for each product.
* `revenue`: Total revenue generated for each product.

---

###  **Key Insights**

      product  total_qty  revenue
0  Headphones        135   6750.0
1      Laptop         45  36000.0
2  Smartphone         90  45000.0
3  Smartwatch         72  14400.0
4      Tablet         63  18900.0

* **Smartphone is the top-selling product**, contributing the highest revenue of ₹45,000 from 90 units sold.
* **Laptop is the second-highest in revenue**, with ₹36,000 from 45 units sold.
* **Headphones and Smartwatches have lower sales**, indicating potential areas for promotional focus.
* The distribution shows that a few products drive the majority of the sales, which is important for stock planning and marketing efforts.

---

###  **Visualization**

![Sales Performance Dashboard](https://github.com/Aastha-collab/SQLite-Database-using-Python/commit/d5ba026d7246cf907ecfc101e576a5354fd93cba)

> *Bar graph showing total quantity sold and revenue for each product. The visualization highlights that Smartphones and Laptops are the leading products contributing to overall sales.*

---

###  **Business Insights**

1. **Focus marketing on high-performing products:** Increasing advertising and promotions for Smartphones and Laptops could boost sales further.
2. **Review inventory management:** Allocate more stock to high-demand products to avoid stockouts.
3. **Explore opportunities in low-performing products:** Special offers or bundling could help improve sales for categories like Headphones and Smartwatches.
4. **Revenue optimization:** Products with higher profit margins should be prioritized in campaigns.

---

###  **Tools & Technologies Used**

* **SQLite:** For storing and querying sales data.
* **Pandas:** For data manipulation and analysis.
* **Matplotlib / Seaborn (Optional):** For visualizing the aggregated data.
* **Google Colab:** For scripting, executing, and presenting the workflow.

---
