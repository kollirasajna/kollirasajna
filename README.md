<div align="center">

<h1>Rasajna Kolli</h1>
<h3>📊 Data Analytics Portfolio</h3>

<p>
  <a href="https://www.linkedin.com/in/rasajna-kolli/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kollirasajna@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-success?style=for-the-badge&logo=briefcase&logoColor=white"/>
</p>

<p>Aspiring <b>Data Analyst</b> based in Hyderabad, India — turning raw data into decisions with SQL, Python, and BI tools.</p>

</div>

<br/>

## 🛠️ Technical Skills

<p>
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white"/>
</p>

<br/>

## 📁 Projects

<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>🏗️ SQL Data Warehouse Project</h3>
<p>A modern data warehouse built from scratch in SQL Server, following <b>Medallion Architecture</b> (Bronze → Silver → Gold). Consolidates raw ERP and CRM CSV data into a clean, business-ready star schema.</p>
<ul>
<li>Built ETL pipelines as stored procedures to move data through Bronze → Silver → Gold layers</li>
<li>Modeled <code>dim_customers</code>, <code>dim_products</code>, and <code>fact_sales</code> as Gold-layer views</li>
<li>Wrote data quality tests validating surrogate key uniqueness and referential integrity</li>
<li>Documented architecture, data flow, and naming conventions</li>
</ul>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white"/>
<img src="https://img.shields.io/badge/T--SQL-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/ETL-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/Star%20Schema-blueviolet?style=flat-square"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kollirasajna/sql-data-warehouse-project)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>📊 SQL Data Analytics Project</h3>
<p>13 progressive T-SQL analytics scripts on top of a star-schema warehouse — from basic exploration to advanced trend, segmentation, and cumulative analysis.</p>
<ul>
<li>Used CTEs, window functions (<code>RANK()</code>, <code>LAG()</code>), and <code>CASE</code>-based segmentation</li>
<li>Built running totals, moving averages, and YoY/MoM growth calculations</li>
<li>Consolidated everything into two reusable reporting views: <code>report_customers</code> and <code>report_products</code> (recency, AOV, lifespan, VIP/Regular/New segmentation)</li>
</ul>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white"/>
<img src="https://img.shields.io/badge/Window%20Functions-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/CTEs-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/Segmentation-blueviolet?style=flat-square"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kollirasajna/sql-data-analytics-project)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>💼 LinkedIn Job Postings Analysis</h3>
<p>End-to-end analysis of <b>20,500+ real LinkedIn job postings</b> (108 countries, 6,656 companies, May 2021–Apr 2023) using SQL, Python, and Power BI.</p>
<ul>
<li>Cleaned raw scraped data with a Python/pandas pipeline — deduplicated 34.9% of raw rows, stripped HTML/whitespace artifacts, parsed locations into city/region/country</li>
<li>Built a star-schema Gold layer (<code>fact_postings</code>, <code>dim_companies</code>, <code>dim_locations</code>) and analyzed it with 13 SQL scripts</li>
<li><b>Key findings:</b> Tech-related industries make up ~31% of postings; India, the US, and UK account for ~75% of all postings; data/ML/analytics roles are 11.3% of the market</li>
<li>Built an interactive Power BI dashboard visualizing hiring trends, in-demand skills, and salary/location patterns</li>
</ul>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kollirasajna/linkedin_jobpostings_insights)

</td>
</tr>
</table>

<br/>
<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>🚕 Uber Analytics Dashboard</h3>
<p>End-to-end Uber analytics project using SQL, Python, and Power BI to analyze bookings, revenue, customer behavior, cancellations, payment methods, vehicle types, and time-based trends.</p>
<ul>
<li>Used <b>Python and Pandas</b> to clean, transform, and prepare raw booking data, including handling missing values, duplicates, and inconsistent fields.</li>
<li>Wrote <b>SQL queries</b> to analyze booking performance, cancellation patterns, revenue, vehicle types, payment methods, and customer behavior.</li>
<li>Built an interactive <b>Power BI dashboard</b> with DAX measures and KPIs for bookings, revenue, distance, ratings, and operational performance.</li>
</ul>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kollirasajna/Uber-Analytics-Dashboard)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>📱 PhonePe Payment Insights Dashboard</h3>
<p>End-to-end digital payment analytics project using SQL, Python, and Power BI to analyze transaction trends, payment success, transaction value, user behavior, and service performance.</p>
<ul>
<li>Used <b>Python and Pandas</b> to clean and transform transaction data and prepare analysis-ready datasets for dashboard development.</li>
<li>Developed <b>SQL queries</b> to analyze transaction volume, transaction value, payment status, service performance, user activity, and demographic segments.</li>
<li>Built an interactive <b>Power BI dashboard</b> with DAX measures for transaction KPIs, successful transaction rate, unique users, service contribution, and usage patterns.</li>
</ul>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kollirasajna/PhonePe-Payment-Insights-Dashboard)

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="70%" valign="top">
<h3>🏠 Airbnb Performance Dashboard</h3>
<p>End-to-end Airbnb analytics project using SQL, Python, and Power BI to analyze listing growth, pricing, market share, ratings, reviews, seasonality, and host trust signals across 10 global cities.</p>
<ul>
<li>Used <b>Python and Pandas</b> for data cleaning, preprocessing, transformation, and exploratory analysis of Airbnb listing and review data.</li>
<li>Created <b>SQL queries</b> to analyze listing trends, city-level performance, pricing, reviews, ratings, property types, and host-related metrics.</li>
<li>Built an interactive <b>Power BI dashboard</b> with DAX measures to analyze market share, listing growth, review frequency, seasonal trends, and host trust signals.</li>
</ul>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
</td>
<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](YOUR_AIRBNB_REPO_LINK)

</td>
</tr>
</table>

<br/>
<table>
<tr>
<td width="70%" valign="top">

<h3>🧱 Concrete Strength Prediction & Analysis</h3>

<p>End-to-end concrete strength analytics project using <b>Python, SQL, Power BI, and Machine Learning</b> to analyze concrete mix composition, curing age, and compressive strength.</p>

<ul>
<li>Used <b>Python and Pandas</b> for data cleaning, preprocessing, exploratory analysis, and identifying relationships between mix components and concrete strength.</li>
<li>Developed <b>SQL queries</b> to analyze material composition, curing age, strength distribution, and key engineering patterns.</li>
<li>Built a <b>regression model</b> to predict compressive strength from mix composition and curing age, achieving approximately <b>80% prediction accuracy</b>.</li>
<li>Created an interactive <b>Power BI dashboard</b> with KPIs and visualizations to explore strength trends, material relationships, and analytical insights.</li>
</ul>

<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Machine%20Learning-Regression-green?style=flat-square"/>

</td>

<td width="30%" valign="top" align="center">
<br/>

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/kollirasajna/Concrete-Strength-Prediction-Analysis-)

</td>
</tr>
</table>

## 📈 GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kollirasajna&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kollirasajna&layout=compact&theme=dark&hide_border=true&bg_color=0d1117"/>

<img src="https://streak-stats.demolab.com/?user=kollirasajna&theme=dark&hide_border=true&background=0d1117"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kollirasajna&theme=react-dark&hide_border=true&bg_color=0d1117"/>

</div>

<br/>

<div align="center">
<sub>Thanks for stopping by — let's connect and turn data into decisions.</sub>
</div>


