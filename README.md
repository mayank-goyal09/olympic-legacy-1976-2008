# 🏅 Olympic Data Analytics Project (1976-2008)
## Advanced SQL Analysis of 32 Years of Olympic Excellence

<div align="center">

[![SQL](https://img.shields.io/badge/SQL-Advanced-blue?style=for-the-badge&logo=postgresql)](https://github.com/mayank-goyal09/olympic-legacy-1976-2008)
[![Data Analysis](https://img.shields.io/badge/Analysis-Sports%20Data-green?style=for-the-badge)](https://github.com/mayank-goyal09/olympic-legacy-1976-2008)
[![Records](https://img.shields.io/badge/Records-15500%2B-orange?style=for-the-badge)](https://github.com/mayank-goyal09/olympic-legacy-1976-2008)

</div>

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Technical Skills Demonstrated](#-technical-skills-demonstrated)
- [Key SQL Analyses](#-key-sql-analyses-16-business-questions-solved)
- [Dataset Information](#-dataset-information)
- [Business Impact](#-business-impact--insights)
- [How to Use](#-how-to-use-this-project)
- [Contact](#-lets-connect)

---

## 🎯 Project Overview

This project demonstrates **advanced SQL analytics** on Olympic Games data spanning **32 years (1976-2008)** with **15,500+ records**. Through **16 comprehensive analytical queries**, I extract actionable insights about country performance, medal trends, efficiency metrics, and competitive intelligence.

**What makes this project valuable:**
- ✅ Real-world sports analytics using SQL
- ✅ Complex queries: JOINs, Window Functions, CTEs, Subqueries, Aggregations
- ✅ Business intelligence approach to sports data
- ✅ Performance tracking, growth analysis, and strategic insights

---

## 💼 Technical Skills Demonstrated

<table>
<tr>
<td width="50%">

### SQL Techniques
- **Aggregate Functions** (COUNT, SUM, AVG)
- **Window Functions** (RANK, ROW_NUMBER, DENSE_RANK)
- **CTEs & Subqueries**
- **Complex JOINs** (INNER, LEFT, SELF)
- **CASE Statements** (Conditional Logic)
- **GROUP BY & HAVING**
- **Percentage Calculations**
- **Growth Rate Analysis**

</td>
<td width="50%">

### Analytics Skills
- **Performance Benchmarking**
- **Trend Analysis** (Year-over-Year)
- **Efficiency Metrics**
- **Ranking & Classification**
- **Comparative Analysis**
- **Data Categorization**
- **Statistical Summaries**
- **Insight Generation**

</td>
</tr>
</table>

---

## 🔍 Key SQL Analyses (16 Business Questions Solved)

Each query below solves a specific **analytical challenge** that mirrors real-world business intelligence problems:

### **1️⃣ Basic Data Retrieval**
**Question:** List the sports for every medal record in the 2000 Summer Olympics.
- **SQL Skills:** Filtering, SELECT statements, WHERE clause
- **Business Value:** Understanding event coverage and diversity

---

### **2️⃣ Medal Count Analysis**
**Question:** How many medals were awarded in the 2000 Olympics?
- **SQL Skills:** COUNT aggregate function
- **Business Value:** Quantifying competition scale

---

### **3️⃣ Country Performance Summary**
**Question:** List the total medals won by each country (show top 10 countries).
- **SQL Skills:** GROUP BY, ORDER BY, LIMIT
- **Business Value:** Identifying top-performing nations

---

### **4️⃣ Medal Type Distribution**
**Question:** For 2008, count the number of Gold, Silver, and Bronze medals won by each country.
- **SQL Skills:** Conditional aggregation (CASE with COUNT)
- **Business Value:** Understanding medal composition by country

---

### **5️⃣ Performance Classification**
**Question:** Categorize each country's Olympic performance in 2008 as 'Excellent', 'Good', or 'Average' based on total medal count.
- **SQL Skills:** CASE statements, conditional logic
- **Business Value:** Performance segmentation for strategic insights

---

### **6️⃣ Competitive Ranking**
**Question:** Rank countries by their total medal count for the 2008 Olympics.
- **SQL Skills:** Window functions (RANK, DENSE_RANK)
- **Business Value:** Creating leaderboards and competitive analysis

---

### **7️⃣ Sport-Specific Dominance**
**Question:** For each country in 2008, identify the sport in which they won the most medals.
- **SQL Skills:** Subqueries, GROUP BY, MAX function, correlated queries
- **Business Value:** Identifying competitive advantages by sport

---

### **8️⃣ Growth & Decline Analysis**
**Question:** Compare medal totals by country between 2004 and 2008 Olympics and calculate growth or decline.
- **SQL Skills:** Self-JOIN, percentage change calculations, year-over-year comparison
- **Business Value:** Tracking performance trends and momentum

---

### **9️⃣ Focused Country Analysis**
**Question:** For the United States in 2008, show sport names and count of Gold medals for sports with 5+ global Golds.
- **SQL Skills:** Multi-level filtering, HAVING clause, nested conditions
- **Business Value:** Deep-dive analysis for specific stakeholders

---

### **🔟 Comprehensive Sport Summary**
**Question:** Create a summary table of medals by sport for 2008, showing Gold/Silver/Bronze counts and ranking sports by total medals.
- **SQL Skills:** Pivot-style aggregation, conditional counting, ranking
- **Business Value:** Executive-level sport performance dashboard

---

### **1️⃣1️⃣ High-Growth Countries**
**Question:** List countries that increased their medal count by at least 50% from 2004 to 2008, with percentage growth.
- **SQL Skills:** Percentage calculations, filtering on computed values, comparative analysis
- **Business Value:** Identifying emerging competitors and success patterns

---

### **1️⃣2️⃣ Top Performers by Sport with Zones**
**Question:** For each sport in 2008, rank the top 3 countries by medals and label them 'Golden', 'Silver', 'Bronze Zone'.
- **SQL Skills:** Window functions (PARTITION BY, RANK), conditional labeling
- **Business Value:** Creating tiered performance classifications

---

### **1️⃣3️⃣ Olympics Overview Dashboard**
**Question:** Summarize the 2008 Olympics: count countries, sports, total medals, average medals per country, and top winner.
- **SQL Skills:** Multiple aggregations, subqueries, statistical summaries
- **Business Value:** Executive summary for stakeholders

---

### **1️⃣4️⃣ Gold Win Percentage Analysis**
**Question:** Find the country-plus-sport combinations in 2008 where athletes had highest percentage of Gold wins (minimum 3 medals).
- **SQL Skills:** Percentage calculations, multi-column grouping, filtering thresholds
- **Business Value:** Identifying peak performance scenarios

---

### **1️⃣5️⃣ Gold Medal Efficiency Ranking**
**Question:** In 2008, rank countries by "Gold Medal Efficiency" (Gold as % of total medals), only for those with 5+ medals.
- **SQL Skills:** Efficiency metrics, ratio calculations, conditional filtering
- **Business Value:** Quality-over-quantity performance measurement

---

### **1️⃣6️⃣ Underdog Country Identification**
**Question:** Label 2008 "underdog" countries who won 10 or fewer medals but had Gold efficiency ≥ 40%.
- **SQL Skills:** Multi-condition filtering, percentage thresholds, strategic classification
- **Business Value:** Spotting high-impact small players for investment insights

---

## 📊 Dataset Information

```
📁 Dataset: olympics_1976_2008.csv
📝 Records: 15,500+
📅 Time Period: 1976 - 2008 (32 years)
🏅 Olympics Covered: 9 Summer Olympics
```

### **Key Attributes:**
- **Athlete Name** — Individual competitor identification
- **Country** — Nation representation
- **Sport & Event** — Competition category
- **Medal Type** — Gold, Silver, Bronze
- **Year** — Olympic year
- **Gender** — Male/Female athlete classification
- **Age** — Athlete age at competition time

---

## 💡 Business Impact & Insights

### **What Decision-Makers Can Learn:**

🎯 **Performance Benchmarking**  
→ Compare countries, sports, and athletes to identify best practices

📈 **Trend Forecasting**  
→ Use historical growth patterns to predict future performance

🏆 **Resource Allocation**  
→ Identify which sports yield highest medal returns for investment

⚡ **Efficiency Optimization**  
→ Discover which nations maximize results with fewer resources

🌍 **Competitive Intelligence**  
→ Track emerging competitors and declining powers

---

## 🚀 How to Use This Project

### **For Recruiters:**
1. Review the [SQL Analyses](#-key-sql-analyses-16-business-questions-solved) section to see demonstrated SQL skills
2. Each question showcases a different analytical technique
3. Check the `/queries` folder for actual SQL code

### **For Data Analysts:**
```bash
# Clone the repository
git clone https://github.com/mayank-goyal09/olympic-legacy-1976-2008.git

# Navigate to project folder
cd olympic-legacy-1976-2008

# Import dataset to your SQL database (PostgreSQL/MySQL)
# Run queries from the queries/ folder
```

### **Technology Stack:**
- **Database:** PostgreSQL / MySQL
- **Language:** SQL
- **Data Format:** CSV
- **Analysis:** 16 analytical queries solving real-world problems

---

## 📈 Why This Project Stands Out

❌ **Not just queries** → Business-focused analytical thinking  
❌ **Not just data** → Actionable insights for decision-makers  
❌ **Not just sports** → Transferable skills to any industry (finance, retail, SaaS)  

✅ **Demonstrates ability to:**
- Translate business questions into SQL queries
- Extract insights from large datasets (15,500+ rows)
- Use advanced SQL techniques (CTEs, Window Functions, Complex JOINs)
- Present findings in a clear, business-friendly format

---

## 🤝 Let's Connect!

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-mayank--goyal09-black?style=for-the-badge&logo=github)](https://github.com/mayank-goyal09)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mayank%20Goyal-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mayank-goyal09)

**Interested in discussing this project or exploring collaboration opportunities?**  
📧 Feel free to reach out!

</div>

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use this as a learning resource or portfolio reference.

---

<div align="center">

### ⭐ If you found this project valuable, please star the repository!

**Built with 💙 by Mayank Goyal**

</div>