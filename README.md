# 🧸 Digital Analytics

> **Client:** New e-commerce startup selling stuffed animal toys  
> **Goal:** Build dashboards and data-driven insights to help secure next-round funding and guide strategic decisions.

---

## 🎯 Objective
Analyze business data, build dashboards, and uncover insights to evaluate company performance and identify product opportunities.

---

## 🧾 Summary
Conducted exploratory data analysis on transactional and web traffic data to uncover monthly trends across products and devices.  
Analyzed conversion rates, identified top-performing pages, and prioritized optimization opportunities driving purchases.

---

## 🧠 Techniques Used
- Data Modeling (ER Diagram Creation)  
- Data Manipulation & Summarization  
- Exploratory Data Analysis (EDA)  
- Dashboard Creation (Power BI)  
- Report Building & Insight Generation  

---

## 🧮 Tools Used
![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-green?logo=microsoft-excel)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![SQL](https://img.shields.io/badge/SQL-Data%20Modeling-lightgrey?logo=sqlite)

---

## 📊 Key Performance Indicators (KPIs)
| KPI | Definition |
|-----|-------------|
| **Conversion Rate** | Percentage of visitors who make a purchase |
| **Traffic** | Number of users visiting the website |
| **Bounce Rate** | % of visitors leaving after one page |
| **Cart Abandonment Rate** | % of users leaving items in the cart without purchase |
| **Average Order Value** | Average spend per transaction |

---

## 🔍 Findings
<details>
<summary>📈 Click to expand</summary>

- **Desktop Dominance:** Desktop users show higher conversion rates than mobile users, likely due to better visibility and browsing control.  
- **Mobile Conversion Challenges:** Lower mobile conversion possibly due to small screens, distractions, or slower load times.  
- **Paid Search Power:** Paid search generates the highest revenue and profit across all channels.  
- **Top Product:** *The Original Mr. Fuzzy* leads in both revenue and engagement metrics (sessions and pageviews).  
- **Drop-Off Points:** Most drop-offs occur between “Home → Product” and “Cart → Shipping”, suggesting UX issues during checkout.  

</details>

---

## 💡 Recommendations
<details>
<summary>💬 Click to expand</summary>

- **Mobile Optimization:** Ensure a responsive design, faster load times, and simplified navigation.  
- **Cart Recovery:** Use push notifications or emails for abandoned cart reminders and offers.  
- **User Behavior Analysis:** Track and optimize mobile user flow to reduce drop-offs.  
- **Brand Trust:** Strengthen branding and direct search visibility.  
- **Checkout Simplification:** Reduce checkout steps and offer multiple payment methods.  

</details>

---

## 🚀 Dashboard Preview
![Power BI Dashboard](https://github.com/yourusername/yourrepo/blob/main/images/dashboard.png)

---

## 📈 Example Metrics Visualization
```sql
-- Top 5 Products by Revenue
SELECT TOP 5 
    ProductName, 
    SUM(Revenue) AS Total_Revenue
FROM Sales
GROUP BY ProductName
ORDER BY Total_Revenue DESC;


