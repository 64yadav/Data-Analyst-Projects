<!-- ============ HEADER (animated waving banner) ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:00d4ff&height=220&section=header&text=Data%20Analytics%20Portfolio&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Excel%20%7C%20SQL%20%7C%20Power%20BI%20%7C%20Python&descSize=18&descAlignY=60" alt="Data Analytics Portfolio banner" width="100%"/>

<!-- Typing animation -->
<a href="https://github.com/YOUR-USERNAME">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=700&lines=Business+questions+%E2%86%92+Clean+data+%E2%86%92+Insights;Excel+%7C+SQL+%7C+Power+BI+%7C+Python;Hands-on+projects+on+messy%2C+real-world+style+data" alt="Typing animation" />
</a>

<br/>

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br/>

![Projects](https://img.shields.io/badge/Projects-4-00d4ff?style=flat-square)
![Status](https://img.shields.io/badge/Status-Actively_Updated-success?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Data_Analyst_Roles-blue?style=flat-square)

</div>

---

## 📑 Table of Contents

- [About Me](#-about-me)
- [Tools & Skills](#-tools--skills)
- [Projects](#-projects)
- [Featured Project: E-commerce Sales & Profit Analytics](#-featured-project-e-commerce-sales--profit-analytics)
- [Repository Structure](#-repository-structure)
- [Learning Roadmap](#-learning-roadmap)
- [Contact](#-contact)

---

## 👋 About Me

I'm **Ranjeet Yadav** from Bihar, India. I come from a B.Com background and taught myself data analytics using Excel, SQL, Power BI, and Python. I'm building my skills toward a **Data Analyst** role.

This repository is where I keep my project work. Each project follows the same flow:

```
Business Question  →  Data Cleaning  →  Analysis  →  Visualization  →  Insights
```

---

## 🛠 Tools & Skills

<table>
  <tr>
    <th align="center">Tool</th>
    <th align="left">What I use it for</th>
  </tr>
  <tr>
    <td align="center"><b>Excel</b></td>
    <td>Data cleaning, formulas, pivot tables, dashboards</td>
  </tr>
  <tr>
    <td align="center"><b>SQL</b></td>
    <td>Joins, aggregations, subqueries, window functions</td>
  </tr>
  <tr>
    <td align="center"><b>Power BI</b></td>
    <td>Data modelling, DAX measures, interactive dashboards</td>
  </tr>
  <tr>
    <td align="center"><b>Python</b></td>
    <td>NumPy for calculations, Pandas for cleaning and analysis (in progress)</td>
  </tr>
</table>

---

## 📂 Projects

| # | Project | Tools | What it covers | Link |
|:-:|---------|:-----:|----------------|:----:|
| 1 | **E-commerce Sales & Profit Analytics** | `Python` `NumPy` | Revenue, profit and margin by product and month, ranking, filtering, month-over-month trends | [View](./python/ecommerce-sales-profit-analytics) |
| 2 | **BiharMart: Messy Data Cleaning** | `Excel` | Cleaning and analysing a messy retail dataset | [View](./excel) |
| 3 | **BiharMart: Business Queries** | `SQL` | Answering business questions with SQL on the same dataset | [View](./sql) |
| 4 | **BiharMart: Dashboard** | `Power BI` | Interactive dashboard with KPIs and filters | [View](./power-bi) |

> 🔧 Replace the links above with your actual folder or file paths. Remove any row for a project that isn't finished yet.

---

## ⭐ Featured Project: E-commerce Sales & Profit Analytics

**Business question:** Which products and months drive revenue and profit, and where is the business at risk?

**Dataset:** 6 products (Laptop, Mobile, Tablet, Monitor, Keyboard, Headphones) across 4 months (Jan to Apr), with units sold, selling price, and cost price.

**Techniques used:** broadcasting, boolean masking, `np.select`, `argmax`, `argsort`, axis-wise aggregation.

<details>
<summary><b>📊 Key findings (click to expand)</b></summary>

<br/>

| Insight | Evidence |
|---------|----------|
| **Revenue is concentrated** | Laptop and Mobile together contribute about 68% of total revenue and about 65% of total profit |
| **Margin and volume don't match** | Keyboard has the highest margin (40%) but only about 2% of revenue. Tablet has the lowest margin (13.6%) but is the third-largest by revenue |
| **Growth is volume-driven** | Monthly revenue grew from ₹65.8L (Jan) to ₹82.8L (Apr), about +25.8%, while monthly margin stayed flat at roughly 17% |
| **One product is declining** | Monitor is the only product whose revenue fell from Jan to Apr (-8.57%) |

</details>

<details>
<summary><b>🧮 Questions solved</b></summary>

<br/>

- Total units, revenue, profit, and profit margin per product
- Monthly revenue and profit
- Top product by revenue and by profit, plus full revenue ranking
- Multi-condition filtering (high revenue and low margin)
- Best sales month per product, and best product per month
- January vs April revenue: absolute and percentage change
- March to April unit trend classification
- Monthly profit margin

</details>

---

## 🗂 Repository Structure

```
data-analytics-portfolio/
│
├── 📁 excel/
│   └── BiharMart cleaning workbook, screenshots, README
│
├── 📁 sql/
│   └── Queries (.sql), schema, README
│
├── 📁 power-bi/
│   └── Dashboard (.pbix), screenshots, README
│
├── 📁 python/
│   └── ecommerce-sales-profit-analytics/
│       └── notebook (.ipynb), README
│
└── 📄 README.md
```

Each project folder has its own README with the problem statement, dataset description, approach, key findings, and screenshots.

---

## 🎯 Learning Roadmap

- [x] Excel: cleaning, formulas, pivot tables
- [x] SQL: joins, aggregations, subqueries
- [x] Power BI: modelling and dashboards
- [x] Python: NumPy
- [ ] Python: Pandas
- [ ] Python: Matplotlib / Seaborn visualization
- [ ] End-to-end project combining SQL + Python + Power BI

---

## 📈 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top languages" />

</div>

---

## 📬 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:203a43,100:0f2027&height=120&section=footer" alt="footer" width="100%"/>

</div>
