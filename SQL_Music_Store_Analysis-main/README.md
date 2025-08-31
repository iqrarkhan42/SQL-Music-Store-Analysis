# 🎵 SQL Music Store Analysis

## 📌 Project Summary
This project is a complete **data analysis case study** of a fictional digital music store.  
Using SQL, I explored **customer behavior, sales performance, and music preferences** to answer key business questions.  

The analysis demonstrates my ability to:  
✔ Work with relational databases  
✔ Clean and prepare data for analysis  
✔ Translate business requirements into SQL queries  
✔ Deliver clear insights to support decision-making  

---

## 🗂 Dataset & Schema
The dataset simulates a digital music store similar to iTunes. It includes:  

- **Employees** – company staff and sales agents  
- **Customers** – buyers across different countries  
- **Invoices & Invoice Lines** – purchase transactions and revenue  
- **Tracks, Albums, Artists** – the music catalog  
- **Genres & Media Types** – classification of tracks  
- **Playlists** – curated song collections  

The schema shows how these tables are connected:  

- A **customer** places an **invoice**  
- Each **invoice** contains multiple **invoice lines** (tracks purchased)  
- **Tracks** belong to **albums**, which belong to **artists**  
- Each track has a **genre** and **media type**

---

## 🔄 Workflow

### 1. Data Understanding
- Reviewed the **Entity Relationship Diagram (ERD)**.  
- Explored tables and confirmed relationships via **primary and foreign keys**.  
- Counted rows in each table to check completeness.  

### 2. Data Cleaning
- Checked for duplicate records in customers and tracks.  
- Verified data consistency (e.g., numeric totals in invoices = sum of invoice lines).  
- Ensured consistent data types (dates, text, numeric).  

### 3. Analysis (SQL Queries)
I structured the business questions into three levels:  

#### 🔹 Easy (Descriptive Analysis)
- Senior-most employee by job title.  
- Countries with the most invoices.  
- Top 3 invoices by total amount.  
- City generating the most revenue.  
- Customer with the highest lifetime spend.  

#### 🔹 Moderate (Customer & Catalog Analysis)
- All Rock music listeners (name, email, genre).  
- Top 10 Rock artists by track count.  
- Tracks longer than the **average track length**.  

#### 🔹 Advanced (Strategic Insights)
- How much each customer spent on each artist.  
- Most popular genre in each country (with ties).  
- Highest-spending customer in each country (with ties).  

### 4. Insights & Results
Below are the **findings from the SQL analysis**:

#### 🏆 Customer Insights
- The **best customer** is **Pragathi Bodike**, with the highest total spend.  
- Customers from the **USA, Canada, and Brazil** generate the majority of sales.  
- High-value customers can be targeted with loyalty programs.  

#### 🌍 Market Insights
- The **city with the highest revenue** is **Prague**, followed closely by other metropolitan areas.  
- The **USA** has the largest customer base, while **Czech Republic and Brazil** are also strong markets.  

#### 🎸 Music Insights
- **Rock** is the most popular genre globally, followed by Latin and Metal.  
- Top Rock artists include **Led Zeppelin** and **U2**, with the highest number of tracks sold.  
- Tracks longer than average (over 3.9 minutes) show potential for **premium offerings**.  

#### 📊 Strategic Insights
- Spending patterns differ by country — some countries prefer Rock, others Latin or Pop.  
- In many countries, multiple genres are equally popular, suggesting diverse music tastes.  
- Identifying **top customers per country** allows for **localized promotions**.  

---

## 📈 Key Learnings
Through this project, I demonstrated:  
- **SQL Proficiency**: Joins, aggregations, subqueries, CTEs, window functions.  
- **Business Acumen**: Translating stakeholder questions into data queries.  
- **Analytical Thinking**: Finding not just answers, but insights that inform decisions.  
- **Storytelling with Data**: Presenting results in a way that stakeholders can act on.  

---

## 💡 Business Value
If this were a real company, the analysis would help management to:  
- Focus marketing campaigns in **top revenue-generating cities**.  
- Develop **loyalty rewards** for best customers.  
- Promote **popular genres and artists** in targeted regions.  
- Localize playlists and promotions to match **regional preferences**.  

---

## 🔮 Future Enhancements
- Create a **dashboard** in Power BI / Tableau to visualize insights.  
- Automate reporting using scheduled SQL scripts.  
- Expand dataset with **streaming data** for real-time analysis.  
- Add **predictive analytics** (e.g., forecasting sales by country).  

---

## 📌 Portfolio Positioning
This project highlights my ability to:  
- Work end-to-end on a SQL analysis project.  
- Derive **insights that drive business strategy**.  
- Showcase technical and analytical skills in a professional case study format.  

