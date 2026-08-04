# 📊 Advanced Threat Incident Analytics and Security Visualization Framework
### Microsoft Power BI Dashboard · Infosys Springboard Virtual Internship 7.0

> A five-page interactive cybersecurity incident analytics dashboard built with Microsoft Power BI, transforming 10,228+ real-world cybersecurity incident records into structured, actionable visual intelligence.

---

## 🧾 Project Details

| Field | Details |
|---|---|
| **Team** | Team D — Batch 1, Group 1 |
| **Members** | Subhashree Subhasmita, Vennela, Tejasri, Twinkle |
| **Mentor** | Mrs. Nithyasri S J |
| **Duration** | June 28 – August 2, 2026 (8 Weeks) |
| **Platform** | Infosys Springboard Virtual Internship 7.0 |

---

## 🎯 Objective

Design and develop an interactive, multi-page cybersecurity incident analytics dashboard to:

- Identify the most prevalent **attack types** and threat levels
- Understand the **geographic origin** of cyber attackers and most targeted countries
- Analyse **attacker profiles**, actor types, and their motivations
- Assess **vulnerabilities** across different asset types and cloud environments
- Measure **Year-over-Year (YoY) incident growth** and monthly severity trends

---

## 🗂️ Dataset

- **Source:** Kaggle (publicly available cybersecurity incident records)
- **Size:** 10,228+ incidents
- **Scope:** Spans multiple decades · 141 countries
- **Key Fields:** Attack Type, Actor Type, Attacker Country, Target Country, Asset Variety, Cloud Environment, Motive, Incident ID, Year/Month

---

## 🛠️ Tech Stack

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Primary dashboard design, data modelling & visualization |
| DAX (Data Analysis Expressions) | KPI logic — YoY Growth, Threat Level, averages |
| Power Query (M Language) | Data cleaning, null handling, column derivation |
| Microsoft Bing Maps | Geo-visualization of global threat distribution |
| Kaggle Dataset (CSV) | Source of 10,228+ cybersecurity incident records |
| Copilot Default Theme | Dark-mode professional dashboard theme |

---

## 📋 Dashboard Pages

### Page 1 — Executive Summary
High-level overview for senior stakeholders and security managers.
- **KPIs:** Total Incidents (10K), Avg Incidents (330), Total Countries (141), Highest Attack Type (Hacking)
- Global threat distribution map, pie chart by attack type, Top 10 Targeted Countries bar chart

### Page 2 — Threat Analysis
Deep dive into threat nature, attacker motivations, and trends over time.
- **KPIs:** Threat Level (CRITICAL)
- Incident breakdown by motive: Unknown (4,690) · Financial (3,951) · Fun (464)
- Attack Type × Motive pivot table, yearly trend area chart

### Page 3 — Attacker & Actor Intelligence
Profiles who initiates cyberattacks and from where.
- Average incidents per actor type, Top attacker origins matrix
- Treemap of actor descriptions, world map of attacker countries

### Page 4 — Target & Asset Vulnerability Analysis
Identifies the most targeted assets and environments.
- Asset Type Targeting Trend by Year (line chart)
- Asset Type × Motive intelligence matrix
- Attacker Country share per asset type (100% stacked bar chart)

### Page 5 — Impact & Incident Severity
Measures consequences and severity of cybersecurity incidents.
- **KPIs:** YoY Growth Rate (-90.83%)
- Cloud vs On-Premise breakdown, monthly incident trend line chart
- Most targeted asset types treemap, attack detail column chart

---

## 🔍 Key Insights

- **10,228** total cybersecurity incidents across **141 countries**
- **Hacking** is the most prevalent attack type (~3K incidents)
- **Financial gain** is the leading motive (3,951 incidents)
- **United States** is the most targeted country (~5K incidents)
- **External actors** (Organized Crime, Unknown) initiate the overwhelming majority of incidents
- **Web Applications** and **Databases** are the most frequently targeted asset types
- Overall threat level classified as **CRITICAL** based on incident volume thresholds

---

## 🔄 Project Workflow

```
Problem Understanding → Data Collection → Data Understanding → Data Connection
→ Data Preprocessing → Data Modelling → Data Visualization → Publish / Share
```

---

## 🚧 Challenges & Solutions

| Challenge | Solution |
|---|---|
| Missing values in Actor Type, Country, Motive | Power Query conditional logic → replaced nulls with "Unknown" |
| Complex DAX measures (YoY, Threat Level) | Iterative validation against raw row counts + Microsoft DAX docs |
| Visual overload in early drafts | Prioritized top-impact visuals per page; used slicers to replace static charts |
| Slow dashboard load times | Removed high-cardinality columns; optimized DAX dependencies |

---

## 🚀 Future Enhancements

- 🔗 Real-time integration with threat intelligence APIs (VirusTotal, MITRE ATT&CK)
- 🤖 Predictive analytics using Azure Machine Learning or Python models
- 🔍 Drill-through pages for incident-level detail
- 💬 Natural Language Q&A visual for plain-English querying
- 📧 Automated scheduled PDF reports via Power BI Service
- 📱 Mobile-responsive layout for field analysts

---

## 📁 Repository Contents

```
📂 Threat-Analytics-PowerBI/
├── 📊 threat-analytics.pbix        ← Power BI dashboard file
├── 📄 Milestone_3_report.docx      ← Full project report
├── 📂 screenshots/                 ← Dashboard page screenshots
│   ├── page1-executive-summary.png
│   ├── page2-threat-analysis.png
│   ├── page3-attacker-intelligence.png
│   ├── page4-asset-vulnerability.png
│   └── page5-impact-severity.png
└── 📄 README.md
```

---

## 👩‍💻 Author

**Subhashree Subhasmita**
B.Tech CSE · ITER, SOA University · CGPA 9.36

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/subhashree-subhasmita-97a45a331)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Subhashree012005)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:subhashree012005@gmail.com)

---

*Built as part of Infosys Springboard Virtual Internship 7.0 · July–August 2026*
