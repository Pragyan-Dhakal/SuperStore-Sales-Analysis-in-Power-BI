# SuperStore-Sales-Analysis-in-Power-BI

## 🎯 Objective
> To contribute to the success of the business by utilizing data analysis techniques—specifically time-series analytics—to provide valuable insights and accurate 15-day sales forecasting.

## 📋 Overview
This repository contains:
- The **Power BI dashboard** (`.pbix`) visualizing key sales metrics (Jan 2019–Oct 2020)  
- A **15-day ARIMA-based forecast** of daily sales  
- This **README** outlining methodology, findings, and actionable recommendations

---

## 🚀 Key Findings
- **Total Sales:** \$1.57 M  
- **Total Profit:** \$175.3 K  
- **Top Category:** Office Supplies (\$644 K; 41 % of revenue)  
- **Leading Segment:** Consumer (48 % of revenue)  
- **Primary Ship Mode:** Standard Class (58 % of orders)  
- **Forecasted Daily Sales:** \$2.2 K–\$5.3 K over next 15 days  

---

## 🛠 Methodology
1. **Data Preparation**  
   - Source: Super Store transactional dataset  
   - Period: January 2019–October 2020  
   - Cleaned for returns, missing shipping info, and date consistency  
2. **Dashboard Design**  
   - KPIs selected for executive visibility  
   - Visual types: bar charts, pie/donut charts, line trends, geographic maps  
3. **Time-Series Forecasting**  
   - Model: ARIMA with parameters tuned via AIC/BIC  
   - Validation: Back-test on October 2020 hold-out  
   - Output: 15-day point forecasts + 95 % prediction intervals  

---

## 📊 KPI Summary  
| KPI                         | Value         |
|-----------------------------|---------------|
| **Total Sales**             | \$1,570,000   |
| **Total Profit**            | \$175,260     |
| **Units Sold**              | 22,000        |
| **Units Returned**          | 287           |
| **Avg. Shipping Time (days)** | 3.93        |

---

## 🔍 Detailed Analysis

### 1. Sales by Category   
- **Office Supplies:** \$644 K (41 %)  
- **Technology:** \$471 K (30 %)  
- **Furniture:** \$452 K (29 %)

### 2. Top 3 Sub-Categories   
- **Phones:** \$197 K  
- **Chairs:** \$182 K  
- **Binders:** \$175 K

### 3. Sales by Ship Mode  
- **Standard Class:** \$912 K (58 %)  
- **Second Class:** \$315 K (20 %)  
- **First Class:** \$243 K (15 %)  
- **Same Day:** \$96 K (6 %)

### 4. Sales by Segment   
- **Consumer:** 48 %  
- **Corporate:** 33 %  
- **Home Office:** 19 %

### 5. Sales by Payment Mode  
- **COD:** 42.6 %  
- **Online:** 35.3 %  
- **Cards:** 22.0 %

### 6. Sales by Region  
- **South:** 33.4 %  
- **West:** 28.8 %  
- **East:** 21.8 %  
- **Central:** 16.0 %

### 7. Monthly Sales & Profit Trends  
- **Seasonality:** Peaks in December; troughs in Feb & Apr  
- **YoY Growth:** ~10 % increase in 2020 vs. 2019  

---

## 🔮 15-Day Sales Forecast

| Date       | Forecast ($) | Lower 95 % | Upper 95 % |
|------------|--------------|------------|------------|
| 2021-01-01 | 5,263        | 1,940      | 8,586      |
| 2021-01-02 | 4,026        |   703      | 7,349      |
| 2021-01-03 | 2,914        |  –409      | 6,237      |
| …          | …            | …          | …          |
| 2021-01-15 | 3,699        |   374      | 7,025      |

> *Figure B-1:* Point forecasts with 95 % confidence intervals, more in report on sales analysis.

---

## 💡 Actionable Recommendations
1. **Inventory & Logistics**  
   - Prioritize restocking Office Supplies & Phones  
   - Scale Standard Class shipping capacity  
2. **Pricing & Promotions**  
   - Bundle high-margin sub-categories (e.g., phone accessories)  
   - Incentivize pre-paid orders to reduce COD share  
3. **Regional Marketing**  
   - Target South & West with regional campaigns  
   - Offer free-shipping thresholds in Central to boost penetration  
4. **Seasonal Planning**  
   - Staff up & increase inventory in Q4 (Nov–Dec)  
   - Launch a mid-year clearance to smooth off-peak dips  
5. **Forecast-Driven Operations**  
   - Align procurement and staffing to 15-day forecasts  
   - Monthly model retraining with fresh data


## 📞 Contact
For questions or freelance engagements, please reach out via my [Linked profile](https://www.linkedin.com/in/pragyan-dhakal-b3a952319/) or email at **pragyan036@gmail.com**.  
Happy analyzing! 🚀  
