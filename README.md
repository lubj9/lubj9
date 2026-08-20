# Lucas Zeferino Baracat

**Information Systems Student | Data & Back-end**

Information Systems student in the 4th semester at Universidade Presbiteriana Mackenzie, focused on data and development.
Software Development, automation and Quality Assurance Intern for Diebold Nixdorf in Brazil.

---

## Technical Skills

**Programming Languages**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Back-end & APIs**

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring](https://img.shields.io/badge/-Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![REST](https://img.shields.io/badge/-REST-02569B?style=flat-square&logo=fastapi&logoColor=white)
![Maven](https://img.shields.io/badge/-Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**DevOps & Tools**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Excel](https://img.shields.io/badge/-Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

---

## Projects

### BI Dashboard — E-commerce Sales Analysis

[Repository](https://github.com/lubj9/dashboard-vendas-bi-python)

Interactive dashboard for sales analysis with KPIs and dynamic visualizations, deployed on Streamlit Cloud. Features KPIs for revenue, average ticket, orders, and units sold, recalculated in real time based on multi-select filters (region, category, period). Includes four Plotly visualizations (time-series evolution, ranking by category, top 10 products, regional distribution), data caching via `@st.cache_data` to avoid rereading the dataset on each interaction, and export of filtered data to CSV.

**Technologies:** Python, Streamlit, pandas, Plotly, NumPy

---

### ETL Pipeline — Currency and Cryptocurrency Quotes

[Repository](https://github.com/lubj9/etl-cotacoes-pipeline-python)

Python ETL pipeline that collects quotes via public APIs, applies quality rules, and persists to PostgreSQL. Runs automatically every 6 hours via GitHub Actions. Extracts quotes from Frankfurter (forex) and CoinGecko (crypto) with retry and exponential backoff for resilience to network failures. Applies quality transformations (deduplication, type validation, enrichment with spread and trend classification) and persists idempotently with UPSERT (`ON CONFLICT DO NOTHING`), with portability between SQLite (dev) and PostgreSQL (Supabase, prod). Serverless orchestration scheduled by cron, with log upload as an artifact on every run.

**Technologies:** Python, pandas, requests, SQLAlchemy, PostgreSQL, GitHub Actions, Supabase

---

### URL Shortener — REST API in Spring Boot

[Repository](https://github.com/lubj9/url-shortener)

URL shortener built in Spring Boot 3 and Java 21, with in-memory caching, Base62 encoding, and non-blocking click tracking. Base62 algorithm implemented from scratch to generate deterministic short codes from the ID, eliminating collision risk. Caffeine cache on the critical redirect path and asynchronous click tracking via `@Async` over Virtual Threads (Java 21), avoiding additional latency. Anti-XSS validation blocking dangerous schemes (`javascript:`, `data:`, `file:`), X-Forwarded-For support, and coverage by 14 automated tests (unit + integration with MockMvc).

**Technologies:** Java 21, Spring Boot 3, Spring Data JPA, Caffeine, PostgreSQL/H2, JUnit 5, Mockito, Docker

---

## Education

**Universidade Presbiteriana Mackenzie** — Bachelor's in Information Systems — Jun/2024 to Jun/2028

### Additional Courses

- **ALURA Online Technology Courses** (2025) — Excel, SQL and PostgreSQL
- **Bradesco** — Databases
- **Cisco Networking Academy** — Networking Concepts

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=lubj9&show_icons=true&theme=default&hide_border=true&count_private=true)

![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=lubj9&layout=compact&theme=default&hide_border=true)

---

## Contact

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasbaracat9/)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucasbaracatprofissional@gmail.com)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lubj9)
