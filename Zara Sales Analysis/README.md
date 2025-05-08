# **🧾 ZARA Sales Analysis Report**

## **📌 Introduction**

This report presents a comprehensive data analysis of ZARA’s product sales using Power BI. The primary objective is to gain insights into sales performance across various dimensions—such as product category, positioning, promotions, pricing, sections (Men/Women), and seasonality. The dashboard enables stakeholders to make data-driven decisions regarding merchandising, inventory planning, marketing strategies, and store layout optimization.

![image](https://github.com/user-attachments/assets/2a341ca3-bdea-4ff4-bc28-4ddb058a381c)

---

## **📊 Dataset Overview**

The dataset includes 252 products with the following key fields:

* **Product ID, SKU, Name** – Unique identifiers and descriptions of products
* **Section** – Product segment (Men/Women)
* **Product Position** – Store placement (Aisle, End-cap, Front of Store)
* **Category (Terms)** – Sub-category like Jackets, Sweaters, Shoes, etc.
* **Promotion / Seasonal** – Indicators for marketing campaigns or seasonal collections
* **Sales Volume, Price, Revenue** – Core performance metrics
* **Scraped\_at** – Timestamp of data extraction

---

## **📝 Dashboard Summary KPIs**

| Metric                | Value    |
| --------------------- | -------- |
| Total Products        | 252      |
| Total Sales Volume    | 460,000+ |
| Sum of Revenue        | \$38.99M |
| Average Product Price | \$86.25  |

These KPIs provide a high-level view of ZARA's retail footprint in terms of product availability and financial performance.

---

## **📈 Key Visualizations & Insights**

#### 1. **Top-Selling Products**

* **Top Product:** *100% Feather Fill Puffer Jacket* – 3,003 units sold generating \$321K+
* **Most Revenue-Generating Categories:** Jackets, Sweaters, and Shoes.

#### 2. **Sales by Section**

* **Men’s Section** dominates with **396K units** sold (\~86.1%)
* **Women’s Section** accounts for only **63K units** (\~13.9%)

➡️ **Insight**: Men’s clothing significantly outperforms women’s in this dataset, indicating a potential gap or untapped market opportunity in women’s wear.

#### 3. **Sales by Promotion**

* Revenue is split almost evenly:

  * **Yes (Promoted):** \$18.99M
  * **No (Not Promoted):** \$19.83M
* Promotions have had a moderate influence, but many non-promoted items still perform well.

➡️ **Insight**: Promotions are helpful but not always necessary for product success.

#### 4. **Sales by Product Position**

* **Aisle Products:** Highest sales volume (\~177K units)
* **End-cap:** 153K units
* **Front of Store:** 129K units

➡️ **Insight**: Aisle placement leads to maximum visibility and conversion.

#### 5. **Sales by Category (Terms)**

* **Jackets** lead with 56.46% of total sales volume.
* Followed by **Sweaters (16.37%)**, **Shoes (12.6%)**, and **T-Shirts (11.67%)**

➡️ **Insight**: Jackets are ZARA’s flagship category. Seasonal variation and colder climate preferences may influence this.

#### 6. **Seasonal Sales**

* **Seasonal Sales:** 49.13% (\$19.16M)
* **Non-Seasonal Sales:** 50.87% (\$19.83M)

➡️ **Insight**: ZARA maintains balanced inventory distribution for seasonal and evergreen collections.

---

## **🧩 Business Insights & Recommendations**

#### 🔹 **Optimize Women’s Product Line**

With only \~14% of total sales volume coming from women’s section, there is room to expand women’s offerings or re-evaluate current selection, marketing, and pricing strategies.

#### 🔹 **Reinforce Jacket Category**

As jackets dominate both volume and revenue, doubling down on innovation, design, and supply chain for this category will pay off.

#### 🔹 **Aisle Positioning Is Key**

Strategically placing new or high-margin products in the **aisle** can help boost visibility and sales.

#### 🔹 **Evaluate Promotional ROI**

Since promoted and non-promoted sales are nearly equal, analyze cost-effectiveness of promotions and selectively target items needing a push.

#### 🔹 **Seasonal Strategy Balance**

Maintain the current approach with a slight focus on enhancing seasonal campaigns to boost seasonal product performance.

---

## **🚀 Future Enhancements**

To enrich this analysis, consider adding:

* **Time Series Analysis** using `Scraped_at` for trend forecasting.
* **Geo-mapping** if store location data becomes available.
* **Customer Behavior Data** to assess conversion rates, demographics, and return rates.
* **Profit Margins** (if cost data available) for more informed profitability analysis.

---

## **🔍 Conclusion**

This Power BI dashboard offers actionable insights into ZARA's product performance across various attributes. It is a powerful tool for decision-makers in merchandising, marketing, and inventory planning. By leveraging these insights, ZARA can continue to drive sales, reduce operational inefficiencies, and enhance customer satisfaction.

---
