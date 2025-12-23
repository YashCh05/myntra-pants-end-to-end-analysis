# <img width="303" height="166" alt="myntra_logo-removebg-preview" src="https://github.com/user-attachments/assets/aafa7117-2641-403e-90cb-0a56787f5049" />
Myntra Pants End-to-End Data Analysis Project

## 📊 Project Overview
This project presents an **end-to-end data analysis** of Myntra pants product data using **Python, SQL, and Power BI**.  
The objective is to analyze pricing, discounts, ratings, and brand positioning to uncover **business insights** that can support merchandising and pricing decisions.

The dataset contains only **pants category products**, allowing focused and deeper analysis rather than generic category-level insights.

---

## 🧠 Business Objectives
- Understand Myntra’s pants catalog structure
- Identify **premium vs budget brands**
- Analyze the impact of **discounts on customer ratings**
- Find **best value products** with high ratings and high discounts
- Support decision-making for **pricing and promotions**

---

## 🗂️ Project Workflow

### 🔹 Phase 1: Python (EDA & Data Cleaning)
- Loaded and explored raw scraped Myntra data
- Removed duplicate records caused by web scraping
- Handled missing values and corrected data types
- Created derived features such as:
  - Discount buckets
  - Rating buckets
  - Price buckets
- Exported a clean dataset for further analysis

**Tools used:**  
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

---

### 🔹 Phase 2: SQL (MySQL Analysis)
- Imported cleaned data into MySQL
- Wrote business-focused SQL queries to analyze:
  - Brand-level pricing and rating trends
  - Discount strategies across brands
  - Best-rated and best-discounted products
- Used:
  - Aggregations
  - HAVING clauses
  - CTEs
  - Window functions

**Tools used:**  
`MySQL`

---

### 🔹 Phase 3: Power BI (Dashboard & Storytelling)
Built a **4-page interactive dashboard**:

#### 📄 Page 1: Executive Overview
- Catalog size, average price, discount, and rating
- Top brands by product count
- Discount and rating distributions
  <img width="883" height="547" alt="Screenshot 2025-12-23 183123" src="https://github.com/user-attachments/assets/0e8b9c0f-b3cb-4a4a-b3f5-310876901dac" />


#### 📄 Page 2: Brand Analysis
- Average price, rating, and discount by brand
- Identification of premium, budget, and value brands
<img width="883" height="549" alt="Screenshot 2025-12-23 183154" src="https://github.com/user-attachments/assets/3dd43e8b-d8ee-4e23-923f-cdb4da827ea0" />


#### 📄 Page 3: Pricing & Discount Insights
- Relationship between discount percentage and ratings
- Discount and rating behavior across price segments
<img width="883" height="547" alt="Screenshot 2025-12-23 183219" src="https://github.com/user-attachments/assets/78f4aecb-5d2c-4377-adc5-d1e64dbecc00" />


#### 📄 Page 4: Best Value Products
- Action-focused table showing products with:
  - Rating ≥ 4.5
  - Discount ≥ 40%
- Brand-level filtering for deal selection
<img width="883" height="548" alt="Screenshot 2025-12-23 183242" src="https://github.com/user-attachments/assets/503c1365-5475-4adb-990e-f918a5f493d9" />


**Tools used:**  
`Power BI`, `DAX`

---

## 📊 Key Insights
- High discounts do not always guarantee higher ratings
- Some mid-range price segments offer the **best balance of rating and discount**
- Certain brands consistently deliver **high perceived value**
- Premium-priced pants generally receive better ratings, but fewer discounts

---

## 🛠️ Tools & Technologies
- **Python** (EDA & data cleaning)
- **MySQL** (business queries & analysis)
- **Power BI** (interactive dashboard & visualization)


---

## 🚀 Outcome
This project demonstrates **real-world data analyst skills**, including:
- End-to-end data pipeline execution
- Business-driven SQL querying
- Insight-focused dashboard design
- Strong data storytelling

---

## 👤 Author
**Yash Chauhan**  
Aspiring Data Analyst  

