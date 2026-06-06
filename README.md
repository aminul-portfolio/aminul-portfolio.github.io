<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814,2d2a26,1a1814&height=3" width="100%"/>
</div>

<br/>

<div align="center">
<a href="https://aminul-portfolio.github.io">
<img src="https://capsule-render.vercel.app/api?type=soft&color=1a1814&height=200&text=aminul-portfolio.github.io&fontSize=30&fontColor=e8d5a3&fontAlignY=44&desc=Premium%20Analytics%20Engineering%20Portfolio%20%E2%80%94%20Aminul%20Islam&descSize=14&descAlignY=64&descColor=9c9890&animation=fadeIn" width="100%"/>
</a>
</div>

<br/>

<div align="center">

[![Live Site](https://img.shields.io/badge/◈%20LIVE%20SITE-e8d5a3?style=for-the-badge&logoColor=1a1814)](https://aminul-portfolio.github.io)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0a66c2?style=for-the-badge&logo=linkedin&logoColor=ffffff)](https://www.linkedin.com/in/aminul-islam-a71a871a2)&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-1a1814?style=for-the-badge&logo=gmail&logoColor=e8d5a3)](https://mail.google.com/mail/?view=cm&to=aminulislamkhan.tech@gmail.com)

</div>

<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-1a1814?style=flat-square&logo=python&logoColor=e8d5a3)&nbsp;
![SQL](https://img.shields.io/badge/SQL-1a1814?style=flat-square&logo=postgresql&logoColor=e8d5a3)&nbsp;
![dbt](https://img.shields.io/badge/dbt-1a1814?style=flat-square&logo=dbt&logoColor=e8d5a3)&nbsp;
![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;
![Excel](https://img.shields.io/badge/Excel-1a1814?style=flat-square&logo=microsoftexcel&logoColor=e8d5a3)&nbsp;
![DuckDB](https://img.shields.io/badge/DuckDB-1a1814?style=flat-square&logo=duckdb&logoColor=e8d5a3)&nbsp;
![London](https://img.shields.io/badge/📍_London_UK-2d2a26?style=flat-square)&nbsp;
![Auth](https://img.shields.io/badge/Full_UK_Work_Authorisation-2d2a26?style=flat-square)

</div>

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=72&text=%2001%20%2F%20Overview&fontSize=20&fontColor=e8d5a3&fontAlign=12&fontAlignY=52&desc=Single-file%20SaaS-style%20portfolio%20%C2%B7%20Editorial%20light-mode%20design%20%C2%B7%20Fully%20responsive&descSize=12&descColor=9c9890&descAlign=50&descAlignY=78" width="100%"/>
<!------------------------------------------------------------------>

<br/>

A self-directed, single-file portfolio site presenting my analytics and data-product work in a clean, editorial SaaS format — designed to give hiring managers and recruitment agents a precise, comprehensive overview in a single page.

**Design system:** Playfair Display editorial headlines · Plus Jakarta Sans body text · JetBrains Mono data surfaces · warm cream base (`#FFFEF9`) · amber gold accent · dark terminal contrast panel.

**Interactions:** Animated scroll counters · marquee ticker strip · hover-lift cards with gold top-line reveal · intersection-observer reveal animations · fully responsive across five breakpoints · Gmail compose email integration.

**Hosted:** GitHub Pages — single `index.html`, no build tools, no dependencies beyond Google Fonts.

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=72&text=%2002%20%2F%20Portfolio%20Projects&fontSize=20&fontColor=e8d5a3&fontAlign=14&fontAlignY=52&desc=Analytics%20Engineering%20%C2%B7%20Django%20%C2%B7%20FinTech%20%C2%B7%20all%20public%20%C2%B7%20all%20claim-safe&descSize=12&descColor=9c9890&descAlign=50&descAlignY=78" width="100%"/>
<!------------------------------------------------------------------>

<br/>

### ◈ &nbsp;Featured — Analytics Engineering

<table width="100%">
<tr>
<td width="58%" valign="top">

**[bakeops-dbt](https://github.com/aminul-portfolio/bakeops-dbt)** &nbsp;`v1.0.1`

![dbt](https://img.shields.io/badge/dbt_Core-1a1814?style=flat-square&logo=dbt&logoColor=e8d5a3)&nbsp;
![DuckDB](https://img.shields.io/badge/DuckDB-1a1814?style=flat-square&logo=duckdb&logoColor=e8d5a3)&nbsp;
![Models](https://img.shields.io/badge/7_models-2d2a26?style=flat-square)&nbsp;
![Tests](https://img.shields.io/badge/26_tests-2d2a26?style=flat-square)&nbsp;
![CI](https://img.shields.io/badge/PASS=33_ERR=0-2d2a26?style=flat-square)

dbt + DuckDB analytics engineering project transforming BakeOps Intelligence CSV exports into tested product-performance marts. Preserves the BakeOps signature insight end-to-end across three implementations.

| Layer | Models |
|:---|:---|
| Staging | `stg_orders` · `stg_order_items` · `stg_snapshot` |
| Intermediate | `int_product_revenue` · `int_product_margins` |
| Mart | `mart_product_performance` · `mart_rank_inversion` |

Local DuckDB only — no cloud warehouse, no orchestration, no production claim.

[![View Repo](https://img.shields.io/badge/view_repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/bakeops-dbt)

</td>
<td width="42%" valign="top">

**Signature insight — `mart_rank_inversion`**

```
cake_name              Birthday Classic
revenue_rank                          1
waste_adj_margin_rank                 4
margin_rank_gap                       3
has_rank_inversion                    1
action_flag                      review
```

> Revenue rank **#1** drops to margin rank **#4** after waste-adjusted margin is applied. Rank inversion confirmed.

</td>
</tr>
</table>

---

### ▦ &nbsp;Django Analytics Platform

<table width="100%">
<tr>
<td width="50%" valign="top">

**[BakeOps Intelligence](https://github.com/aminul-portfolio/bakeops-intelligence)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;
![Tests](https://img.shields.io/badge/37_tests-2d2a26?style=flat-square)

| Feature | Detail |
|:---|:---|
| Dashboards | KPI cards · gold-layer metric snapshots |
| Exports | BI-ready CSV · 11 export contracts |
| Quality | Data-quality review · lineage docs |
| Insight | Revenue rank vs waste-adjusted margin rank |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/bakeops-intelligence)

</td>
<td width="50%" valign="top">

**[CareerFunnel Tracker](https://github.com/aminul-portfolio/careerfunnel-tracker)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;
![Tests](https://img.shields.io/badge/828_tests-e8d5a3?style=flat-square&color=e8d5a3&labelColor=1a1814)

| Feature | Detail |
|:---|:---|
| Tracking | Funnel metrics · source performance |
| Workflows | CV A/B testing · Document Pack |
| Delivery | 828 automated tests · Sprint 60 |
| Advisory | No auto-apply · no scraping |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/careerfunnel-tracker)

</td>
</tr>
</table>

---

### ▦ &nbsp;FinTech Analytics Suite

<table width="100%">
<tr>
<td width="50%" valign="top">

**[DataBridge Market API](https://github.com/aminul-portfolio/databridge-market-api)**

![Python](https://img.shields.io/badge/Python-1a1814?style=flat-square&logo=python&logoColor=e8d5a3)&nbsp;
![ETL](https://img.shields.io/badge/ETL-2d2a26?style=flat-square)

| Layer | Detail |
|:---|:---|
| Ingestion | yfinance · ccxt · TwelveData |
| Storage | Normalised models · run logging |
| Delivery | Read-only JSON API layer |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/databridge-market-api)

</td>
<td width="50%" valign="top">

**[TradeIntel 360](https://github.com/aminul-portfolio/tradeintel-360)**

![Pandas](https://img.shields.io/badge/Pandas-1a1814?style=flat-square&logo=pandas&logoColor=e8d5a3)&nbsp;
![KPIs](https://img.shields.io/badge/17_KPIs-e8d5a3?style=flat-square&color=e8d5a3&labelColor=1a1814)

| Layer | Detail |
|:---|:---|
| Analytics | 17-metric KPI engine |
| Exports | Excel · optional KPI sheet · PDF |
| Stack | Pandas · Plotly · xhtml2pdf |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/tradeintel-360)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[MarketVista Dashboard](https://github.com/aminul-portfolio/marketvista-dashboard)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;
![Plotly](https://img.shields.io/badge/Plotly-2d2a26?style=flat-square)

| Layer | Detail |
|:---|:---|
| Signals | Severity-ranked signal logic |
| Monitoring | Watchlists · threshold alerts |
| Inspection | OHLC-backed asset visibility |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/marketvista-dashboard)

</td>
<td width="50%" valign="top">

**[RiskWise Planner](https://github.com/aminul-portfolio/riskwise-planner)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;
![MC](https://img.shields.io/badge/Monte_Carlo-2d2a26?style=flat-square)

| Layer | Detail |
|:---|:---|
| Simulation | Monte Carlo scenario engine |
| Analysis | Downside-aware risk review |
| Output | Capital-preservation decisions |

[![View Repo](https://img.shields.io/badge/repo-2d2a26?style=flat-square&logo=github&logoColor=e8d5a3)](https://github.com/aminul-portfolio/riskwise-planner)

</td>
</tr>
</table>

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=72&text=%2003%20%2F%20Technical%20Stack&fontSize=20&fontColor=e8d5a3&fontAlign=13&fontAlignY=52&desc=dbt%20%C2%B7%20DuckDB%20%C2%B7%20Python%20%C2%B7%20Django%20%C2%B7%20SQL%20%C2%B7%20Excel%20%C2%B7%20Pandas%20%C2%B7%20Git&descSize=12&descColor=9c9890&descAlign=50&descAlignY=78" width="100%"/>
<!------------------------------------------------------------------>

<br/>

| Category | Primary | Supporting |
|:---|:---|:---|
| **Analytics Engineering** | `dbt Core` `DuckDB` `SQL` | dimensional modelling · mart design · data quality · sources |
| **Data Processing** | `Python` `Pandas` | NumPy · openpyxl · Plotly · Chart.js · xhtml2pdf |
| **Backend & APIs** | `Django` | Django ORM · REST APIs · management commands · ETL workflows |
| **Reporting & BI** | `Excel` `Power Query` | DAX · VBA · KPI dashboards · BI-ready exports · PDF reports |
| **Delivery** | `Git` `GitHub` | sprint delivery · dbt tests · Django TestCase · claim-safe docs |
| **Domain** | `FX operations` `FinTech` | money transfer · reconciliation · KPI reporting · AML |

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=72&text=%2004%20%2F%20Claim-Safety%20Note&fontSize=20&fontColor=e8d5a3&fontAlign=14&fontAlignY=52&desc=Evidence-based%20%C2%B7%20No%20overclaiming%20%C2%B7%20All%20projects%20are%20reviewer-verifiable&descSize=12&descColor=9c9890&descAlign=50&descAlignY=78" width="100%"/>
<!------------------------------------------------------------------>

<br/>

This is a self-directed portfolio site. The following boundaries apply across all projects and all content:

| Boundary | Status |
|:---|:---|
| Portfolio data | Seeded, demo, or public data only |
| Cloud warehouse | Not implemented — local DuckDB only |
| Orchestration platform | Not implemented |
| Production SaaS customers | None — not claimed |
| Live commercial users | None — not claimed |
| bakeops-dbt environment | Local DuckDB · `dbt build` · no deployment |

Any capability not listed in a linked repository as merged, tagged, and test-passing is not claimed.

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=72&text=%2005%20%2F%20Professional%20Background&fontSize=20&fontColor=e8d5a3&fontAlign=17&fontAlignY=52&desc=FX%20operations%20%C2%B7%20Money%20transfer%20%C2%B7%20KPI%20reporting%20%C2%B7%20Software%20platform%20support&descSize=12&descColor=9c9890&descAlign=50&descAlignY=78" width="100%"/>
<!------------------------------------------------------------------>

<br/>

<table width="100%">
<tr>
<td align="center" width="33%" valign="top">

<br/>

![£30k](https://img.shields.io/badge/%C2%A330k-e8d5a3?style=for-the-badge&logoColor=1a1814)

**Daily cash volumes managed**

| | |
|:---|:---|
| Company | Acaelus Services Ltd |
| Domain | FX & money transfer |
| Controls | AML · audit-ready records |
| Built | In-house Excel cashflow platform |

<br/>

</td>
<td align="center" width="33%" valign="top">

<br/>

![~800](https://img.shields.io/badge/~800-e8d5a3?style=for-the-badge&logoColor=1a1814)

**UK agents supported**

| | |
|:---|:---|
| Company | Bliss Services Ltd |
| Platform | Python-based sales platform |
| Reporting | Monthly KPI reports |
| Bridge | User → developer translation |

<br/>

</td>
<td align="center" width="33%" valign="top">

<br/>

![ILR](https://img.shields.io/badge/ILR-e8d5a3?style=for-the-badge&logoColor=1a1814)

**Full UK work authorisation**

| | |
|:---|:---|
| Status | No sponsorship required |
| Availability | Immediate |
| Location | London · Remote · Hybrid |
| Range | Within 90 min of Purley |

<br/>

</td>
</tr>
</table>

<br/><br/>

---

<div align="center">

[![◈ VIEW PORTFOLIO SITE](https://img.shields.io/badge/◈%20VIEW%20PORTFOLIO%20SITE-e8d5a3?style=for-the-badge&logoColor=1a1814)](https://aminul-portfolio.github.io)

</div>

<br/>

---

<div align="center">
<sub>Self-directed portfolio · seeded demo data · local DuckDB · no cloud warehouse · no production deployment</sub>
</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814,2d2a26,1a1814&height=3" width="100%"/>
</div>
