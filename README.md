# 🏦 Chicago Atlantic | Investment Platform Intelligence Dashboard

**Live Demo → [https://prince-092002.github.io/chicago-atlantic-dashboard/](https://prince-092002.github.io/chicago-atlantic-dashboard/)**

An interactive, single-page investment intelligence dashboard analyzing **Chicago Atlantic Real Estate Finance (REFI)** and **Chicago Atlantic BDC (LIEN)** — two specialty finance vehicles providing senior-secured lending to regulated cannabis operators.

Built as a post-interview follow-up to demonstrate deep company research, financial data analysis, and dashboard design skills.

---

## 📊 Dashboard Features

| Section | Description |
|---|---|
| **KPI Row** | Key metrics: REFI $410M AUM @ 17.2% yield · LIEN $275M FMV @ 16.5% gross yield |
| **Yield Benchmarking** | Cannabis credit premium vs IG bonds, HY bonds, leveraged loans, BDC avg |
| **REFI Quarterly Trend** | Net Interest Income + Distributable EPS by quarter (FY2024) |
| **LIEN Portfolio Composition** | Donut chart — Cannabis 78%, Life Sciences 10%, Healthcare 7% |
| **Geographic Mix** | Top 10 states by loan principal (sourced from `REFI GEOGRAPHY.csv`) |
| **Credit Quality Scorecard** | Senior-secured %, floating-rate %, non-accrual rate |
| **Stock Price History** | 24-month REFI & LIEN monthly close prices (NASDAQ data) |
| **Risk Rating by Vintage** | REFI internal ratings 1–4 by origination year ($M) |
| **Illinois Cannabis Sales** | Monthly adult-use vs medical revenue trend (IL IDFPR data) |
| **SQL Queries Tab** | Full data extraction logic for each visualization |
| **Methodology Tab** | 7-step analyst research workflow with data sources |

---

## 🗄️ Data Sources

| File | Source | Used For |
|---|---|---|
| `REFI GEOGRAPHY.csv` | Chicago Atlantic IR | Geographic loan concentration |
| `REFI RISK RATING.csv` | Chicago Atlantic IR | Internal credit risk ratings by vintage |
| `HistoricalData REFI.csv` | NASDAQ | REFI daily stock prices (1,060 rows) |
| `HistoricalData LIEN.csv` | NASDAQ | LIEN daily stock prices (1,020 rows) |
| `Retail Sales_data.csv` | IL IDFPR | Monthly cannabis sales 2015–2025 |
| `Cannabis_Retail_Sales_by_Week_Ending.csv` | IL IDFPR | Weekly retail sales with pricing |

---

## 🧠 Investment Thesis

> **Regulated-state cannabis lending delivers superior risk-adjusted returns** because federal prohibition excludes traditional banks, allowing specialty lenders like Chicago Atlantic to capture 800–1,000 bps spread premiums on senior-secured, first-lien loans to supply-constrained, license-limited operators.

**Three structural moats:**
1. **Banking Exclusion Premium** — Federal Schedule I locks out traditional capital
2. **Limited-License Scarcity** — ~25 states cap operators, creating monopoly-like cash flows
3. **First-Lien Collateral Stack** — RE + equipment + IP + licenses at 1.5x net leverage

---

## 🛠️ Tech Stack

- **Pure HTML/CSS/JavaScript** — zero dependencies, no build step
- **Chart.js** — all 9 interactive charts
- **CSS Grid + Variables** — responsive dark-mode layout
- **GitHub Pages** — instant static hosting

---

## 🚀 Run Locally

Just open `index.html` in any browser. No server needed.

```bash
# Or clone and open
git clone https://github.com/prince-092002/chicago-atlantic-dashboard.git
cd chicago-atlantic-dashboard
open index.html   # macOS
start index.html  # Windows
```

---

*Prepared by Abel P. · Internship Follow-Up Analysis · March 2026*
*All figures FY2024 unless noted · Sources: Chicago Atlantic IR, SEC Filings, IL IDFPR, NASDAQ*
