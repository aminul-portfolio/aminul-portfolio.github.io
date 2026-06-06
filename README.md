<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=4" width="100%"/>
</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=1a1814&height=180&text=aminul-portfolio.github.io&fontSize=32&fontColor=e8d5a3&fontAlignY=45&desc=Premium%20Analytics%20Engineering%20Portfolio%20Site&descSize=14&descAlignY=68&descColor=6b6760&animation=fadeIn" width="100%"/>

</div>

<br/>

<div align="center">

[![Live Site](https://img.shields.io/badge/◈_LIVE_SITE-e8d5a3?style=for-the-badge&logoColor=1a1814)](https://aminul-portfolio.github.io)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0a66c2?style=for-the-badge&logo=linkedin&logoColor=ffffff)](https://www.linkedin.com/in/aminul-islam-a71a871a2)&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-1a1814?style=for-the-badge&logo=gmail&logoColor=e8d5a3)](https://mail.google.com/mail/?view=cm&to=aminulislamkhan.tech@gmail.com)

</div>

<br/>

<div align="center">

![Stack](https://img.shields.io/badge/Python%20·%20SQL%20·%20dbt%20·%20Django%20·%20Excel%20·%20DuckDB-1a1814?style=flat-square&logoColor=e8d5a3)&nbsp;
![Location](https://img.shields.io/badge/📍_London,_UK-ede9e0?style=flat-square&color=ede9e0&labelColor=1a1814)&nbsp;
![Auth](https://img.shields.io/badge/Full_UK_Work_Authorisation-ede9e0?style=flat-square&color=ede9e0&labelColor=1a1814)

</div>

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=68&text=01%20%20/%20%20Overview&fontSize=20&fontColor=e8d5a3&fontAlign=10&fontAlignY=52&desc=Premium%20SaaS-style%20portfolio%20%C2%B7%20Editorial%20light-mode%20design%20%C2%B7%20Fully%20responsive&descSize=12&descColor=6b6760&descAlign=50&descAlignY=76" width="100%"/>
<!------------------------------------------------------------------>

<br/>

A self-directed, single-file portfolio site presenting my analytics and data-product work in a clean, editorial SaaS format — designed to give hiring managers and recruitment agents a precise, comprehensive overview in a single page.

**Design system:** Playfair Display editorial typography · DM Sans body · DM Mono data surfaces · warm cream base (`#FFFEF9`) · amber gold accent · dark terminal contrast panel.

**Interactions:** Animated scroll counters · hover-lift cards · intersection-observer reveal animations · fully responsive across five breakpoints · Gmail compose email integration.

**Hosted:** GitHub Pages — single `index.html`, no build tools, no dependencies beyond Google Fonts.

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=68&text=02%20%20/%20%20Portfolio%20Projects&fontSize=20&fontColor=e8d5a3&fontAlign=10&fontAlignY=52&desc=Analytics%20Engineering%20%C2%B7%20Django%20%C2%B7%20FinTech%20%C2%B7%20all%20public%20%C2%B7%20all%20claim-safe&descSize=12&descColor=6b6760&descAlign=50&descAlignY=76" width="100%"/>
<!------------------------------------------------------------------>

<br/>

### ◈ &nbsp;Featured — Analytics Engineering

<table width="100%">
<tr>
<td width="55%" valign="top">

**[bakeops-dbt](https://github.com/aminul-portfolio/bakeops-dbt)** &nbsp;`v1.0.1`

![dbt](https://img.shields.io/badge/dbt_Core-1a1814?style=flat-square&logo=dbt&logoColor=e8d5a3)&nbsp;![DuckDB](https://img.shields.io/badge/DuckDB-1a1814?style=flat-square&logo=duckdb&logoColor=e8d5a3)&nbsp;![7M](https://img.shields.io/badge/7_models-ede9e0?style=flat-square&color=ede9e0&labelColor=2d2a26)&nbsp;![26T](https://img.shields.io/badge/26_tests-ede9e0?style=flat-square&color=ede9e0&labelColor=2d2a26)&nbsp;![CI](https://img.shields.io/badge/PASS=33_ERR=0-ede9e0?style=flat-square&color=ede9e0&labelColor=2d2a26)

dbt + DuckDB analytics engineering project transforming BakeOps Intelligence CSV exports into tested product-performance marts across staging → intermediate → mart layers. Preserves the BakeOps signature insight end-to-end.

| Layer | Models |
|:---|:---|
| Staging | `stg_orders` · `stg_order_items` · `stg_snapshot` |
| Intermediate | `int_product_revenue` · `int_product_margins` |
| Mart | `mart_product_performance` · `mart_rank_inversion` |

Local DuckDB only — no cloud warehouse, no orchestration.

</td>
<td width="45%" valign="top">

**Signature insight — `mart_rank_inversion`**

```
revenue_rank              →  1
waste_adjusted_margin_rank →  4
margin_rank_gap           →  3
has_rank_inversion        →  1
action_flag               →  review
```

> Birthday Classic is revenue rank **#1** but drops to margin rank **#4** after waste-adjusted margin is applied. Rank inversion confirmed.

</td>
</tr>
</table>

<br/>

### ▦ &nbsp;Django Analytics Platform

<table width="100%">
<tr>
<td width="50%" valign="top">

**[BakeOps Intelligence](https://github.com/aminul-portfolio/bakeops-intelligence)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;![37T](https://img.shields.io/badge/37_tests-ede9e0?style=flat-square&color=ede9e0&labelColor=2d2a26)

| Feature | Detail |
|:---|:---|
| Dashboards | KPI cards · gold-layer metric snapshots |
| Exports | BI-ready CSV · 11 export contracts |
| Insight | Revenue rank vs waste-adjusted margin rank |

</td>
<td width="50%" valign="top">

**[CareerFunnel Tracker](https://github.com/aminul-portfolio/careerfunnel-tracker)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;![828T](https://img.shields.io/badge/828_tests-e8d5a3?style=flat-square&color=e8d5a3&labelColor=1a1814)

| Feature | Detail |
|:---|:---|
| Tracking | Funnel metrics · source performance |
| Workflows | CV A/B testing · Document Pack |
| Delivery | 828 automated tests · Sprint 60 |

</td>
</tr>
</table>

<br/>

### ▦ &nbsp;FinTech Analytics Suite

<table width="100%">
<tr>
<td width="50%" valign="top">

**[DataBridge Market API](https://github.com/aminul-portfolio/databridge-market-api)**

![Python](https://img.shields.io/badge/Python-1a1814?style=flat-square&logo=python&logoColor=e8d5a3)&nbsp;![ETL](https://img.shields.io/badge/ETL-2d2a26?style=flat-square)

| Layer | Detail |
|:---|:---|
| Ingestion | yfinance · ccxt · TwelveData |
| Storage | Normalised models · run logging |
| Delivery | Read-only JSON API layer |

</td>
<td width="50%" valign="top">

**[TradeIntel 360](https://github.com/aminul-portfolio/tradeintel-360)**

![Pandas](https://img.shields.io/badge/Pandas-1a1814?style=flat-square&logo=pandas&logoColor=e8d5a3)&nbsp;![17KPIs](https://img.shields.io/badge/17_KPIs-e8d5a3?style=flat-square&color=e8d5a3&labelColor=1a1814)

| Layer | Detail |
|:---|:---|
| Analytics | 17-metric KPI engine |
| Exports | Excel · optional KPI sheet · PDF |
| Stack | Pandas · Plotly · xhtml2pdf |

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[MarketVista Dashboard](https://github.com/aminul-portfolio/marketvista-dashboard)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)

| Layer | Detail |
|:---|:---|
| Signals | Severity-ranked signal logic |
| Monitoring | Watchlists · threshold alerts |
| Inspection | OHLC-backed asset visibility |

</td>
<td width="50%" valign="top">

**[RiskWise Planner](https://github.com/aminul-portfolio/riskwise-planner)**

![Django](https://img.shields.io/badge/Django-1a1814?style=flat-square&logo=django&logoColor=e8d5a3)&nbsp;![MC](https://img.shields.io/badge/Monte_Carlo-2d2a26?style=flat-square)

| Layer | Detail |
|:---|:---|
| Simulation | Monte Carlo scenario engine |
| Analysis | Downside-aware risk review |
| Output | Capital-preservation decisions |

</td>
</tr>
</table>

<br/><br/>

<!------------------------------------------------------------------>
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=68&text=03%20%20/%20%20Technical%20Stack&fontSize=20&fontColor=e8d5a3&fontAlign=9&fontAlignY=52&desc=dbt%20%C2%B7%20DuckDB%20%C2%B7%20Python%20%C2%B7%20Django%20%C2%B7%20SQL%20%C2%B7%20Excel%20%C2%B7%20Pandas%20%C2%B7%20Git&descSize=12&descColor=6b6760&descAlign=50&descAlignY=76" width="100%"/>
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
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=68&text=04%20%20/%20%20Claim-Safety%20Note&fontSize=20&fontColor=e8d5a3&fontAlign=10&fontAlignY=52&desc=Evidence-based%20%C2%B7%20No%20overclaiming%20%C2%B7%20All%20projects%20are%20reviewer-verifiable&descSize=12&descColor=6b6760&descAlign=50&descAlignY=76" width="100%"/>
<!------------------------------------------------------------------>

<br/>

This is a self-directed portfolio site. The following boundaries apply across all projects and all content on this site:

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
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814&height=68&text=05%20%20/%20%20Professional%20Background&fontSize=20&fontColor=e8d5a3&fontAlign=11&fontAlignY=52&desc=FX%20operations%20%C2%B7%20Money%20transfer%20%C2%B7%20KPI%20reporting%20%C2%B7%20Software%20platform%20support&descSize=12&descColor=6b6760&descAlign=50&descAlignY=76" width="100%"/>
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

[![◈ VIEW PORTFOLIO SITE](https://img.shields.io/badge/◈_VIEW_PORTFOLIO_SITE-e8d5a3?style=for-the-badge&logoColor=1a1814)](https://aminul-portfolio.github.io)

</div>

<br/>

---

<div align="center">
<sub>Self-directed portfolio · seeded demo data · local DuckDB · no cloud warehouse · no production deployment</sub>
</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=1a1814,2d2a26,1a1814&height=4" width="100%"/>
</div>
