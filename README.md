# 📊 Superstore Sales & Profitability Interactive Dashboard (Excel)

## 📌 Project Overview
This project focuses on analyzing retail sales data from the **Sample Superstore** dataset using **Microsoft Excel**. The primary goal is to evaluate profitability across categories, regions, and shipping modes to uncover actionable business insights and optimize profit margins.

---

## 📸 Interactive Dashboard Preview
![Dashboard Preview](Dashboard.png)

![Filtered Dashboard](Dashboard_filtered.png)

---

## 🔑 Key Business Insights (EDA)
1. **Category Performance:**
   * **Technology** generates the highest profit margin (~17%) and sales[cite: 10].
   * **Furniture** faces severe profitability issues with an extremely low profit margin (~2%) despite high sales volume, driven by excessive discounting[cite: 10].

2. **Regional Performance:**
   * **West Region** is the top-performing market in both total sales and profit margin (~14.94%)[cite: 10].
   * **Central Region** suffers from the lowest profit margin (~7.92%), indicating operational inefficiencies or aggressive pricing strategies[cite: 10].

3. **Logistics & Shipping:**
   * **Standard Class** handles over 50% of total sales volume while maintaining a stable ~12.08% profit margin[cite: 10].
   * **First Class** shipping achieves the highest profit margin (~13.93%), showing strong customer willingness to pay for premium delivery services[cite: 10].

---

## 🛠️ Tools & Excel Techniques Used
* **Power Query:** Data cleaning, custom column creation (`Delivery Days`, `Profit Margin`)[cite: 4].
* **Pivot Tables & Calculated Fields:** Dynamic KPI aggregations and calculated custom fields (`Profit / Sales`) to prevent percentage summation errors[cite: 8, 10].
* **Data Visualization:** Clustered Column, Bar, and Donut charts[cite: 10, 11].
* **Interactive Features:** Slicers (`Segment`, `Region`, `Category`) cross-connected via **Report Connections** for seamless multi-dimensional filtering[cite: 10, 11].

---

## 📁 Repository Structure
