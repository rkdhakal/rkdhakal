# Hi, I'm Ram Krishna Dhakal 👋

### Data Quality & Governance Analyst | Canada

It started with a bad number. During my Data Quality Analyst internship at **CMHC** (Sept–Dec 2025), I watched a single bad record work its way through a live reporting pipeline before anyone caught it. That's the moment data governance stopped being an abstract discipline for me and became the thing I wanted to build a career on - not just cleaning data, but designing the rules, catalogs, and stewardship structures that catch problems like that before they reach a decision-maker.

Working hands-on with **Informatica IDMC**, **Collibra Data Intelligence Cloud**, and **Databricks SQL** inside a federal regulatory environment taught me that governance is equal parts technical and human - the SQL rules matter, but so does knowing exactly who owns a data element and who gets called when it breaks.

Since then, I've built out that same rigor independently, on my own time and on public datasets - full DQ rule catalogs, lineage diagrams, and stewardship RACI matrices, using open-source tools to mirror what enterprise platforms do. Beyond governance, I also apply Python and SQL to time series forecasting and ML pipelines — understanding how data gets used downstream makes me better at protecting it upstream.

- 🌍 Based in **Toronto, Ontario** · open to roles **across Canada**
- 💼 Open to **Data Governance · Data Quality · Data Stewardship · Data Analyst** roles
- 🧠 Preparing for **CDMP Foundation — DAMA International**
- ✉️ [dramkrishna19@gmail.com](mailto:dramkrishna19@gmail.com)

---

## 🗂️ Featured Projects

---

### 🏛️ [Canadian Housing Data Governance & Quality Framework](https://github.com/rkdhakal/canadian-housing-data-governance)
> *Solo project, designed and built end to end — the flagship project in this portfolio*

Enterprise governance programs follow well-established patterns — metadata catalogs, lineage, stewardship, DQ rule engines. I wanted to prove I could own that whole lifecycle myself, so I built one, end to end, on a real public Canadian housing dataset (**10,800 records · 10 provinces · 2018–2023**).

**Governance deliverables:**
| Component | Detail |
|---|---|
| **Data Quality Rules** | 15 SQL-based rules across 5 dimensions — completeness, validity, uniqueness, accuracy, consistency |
| **DQ Score** | 99.45% overall (Grade A) · 9 PASS · 6 WARN · 0 FAIL |
| **Exception Management** | 884 exceptions · 424 auto-remediated · 460 escalated with root cause analysis by province and dwelling type |
| **Critical Data Elements** | 6 CDEs with column-level data lineage across a 5-layer source-to-consumption pipeline |
| **Metadata Catalog** | Data dictionary · Business glossary · Sensitivity classifications · Stewardship RACI matrix |
| **Data Contract** | YAML-based producer-consumer agreement with tiered SLA thresholds and 15 mapped DQ rules |
| **Regulatory Compliance** | PIPEDA and OSFI B-20 applicability assessment |
| **Dashboard** | Streamlit Cloud — executive scorecard, exception explorer, live contract validator |

**🔗 [Explore this project →](https://github.com/rkdhakal/canadian-housing-data-governance)**

---

### 📈 [Toronto Crime Time Series Analysis](https://github.com/rkdhakal/toronto-crime-time-series)
> *End-to-end data pipeline with time series forecasting on Toronto Police open data*

Applied data cleaning, exploratory analysis, and forecasting models to **315,362 Major Crime Indicator records** (2014–2023).

| Component | Detail |
|---|---|
| **Data Pipeline** | 347K → 315K records · duplicates removed · divisions reconciled · external features merged |
| **EDA** | Crime trends by year, month, hour, day · outlier analysis · correlation heatmap |
| **ARIMA Model** | ARIMA(1,1,1) on log-transformed weekly data · RMSE: 0.097 |
| **LSTM Model** | 50 units · sequence length 10 · training loss: 0.0069 |

**🔗 [Explore this project →](https://github.com/rkdhakal/toronto-crime-time-series)**

---

### 🦅 [EcoEye — Bird Monitoring System](https://github.com/rkdhakal/Ecoeye-bird-monitoring)
> *Data pipeline, ML classification, and Power BI analytics for bird conservation*

Built the data collection pipeline and ML model for an AI-powered bird species monitoring platform.

| Component | Detail |
|---|---|
| **Data Pipeline** | Selenium scraper · 288,562 observations · 53 species · 170 countries |
| **ML Classifier** | EfficientNetB0 · 97.35% accuracy on 10 species · Grad-CAM interpretability |
| **Power BI Dashboard** | Global species presence map · migration trends · population analytics |

**🔗 [Explore this project →](https://github.com/rkdhakal/Ecoeye-bird-monitoring)**

---

## 🛠️ Skills

**Data Governance & Quality** ← *Core expertise*

![Informatica](https://img.shields.io/badge/Informatica_IDMC-FF6C00?style=flat-square&logo=informatica&logoColor=white)
![Collibra](https://img.shields.io/badge/Collibra-0057A8?style=flat-square&logoColor=white)
![DAMA](https://img.shields.io/badge/DAMA--DMBOK-4B0082?style=flat-square&logoColor=white)
![Data Quality](https://img.shields.io/badge/Data_Quality_Rules-2E8B57?style=flat-square&logoColor=white)
![Metadata Management](https://img.shields.io/badge/Metadata_Management-20B2AA?style=flat-square&logoColor=white)
![Data Lineage](https://img.shields.io/badge/Data_Lineage-5F9EA0?style=flat-square&logoColor=white)
![Data Contracts](https://img.shields.io/badge/Data_Contracts-6A5ACD?style=flat-square&logoColor=white)
![Data Stewardship](https://img.shields.io/badge/Data_Stewardship-8B0000?style=flat-square&logoColor=white)

**Programming & Data Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks_SQL-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Machine Learning & AI**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logoColor=white)

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramkrishnadhakal-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ramkrishnadhakal)
[![Email](https://img.shields.io/badge/Gmail-dramkrishna19@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dramkrishna19@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-rkdhakal-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rkdhakal)

---

*If you find any of my projects useful, please consider giving them a ⭐ — it means a lot!*
