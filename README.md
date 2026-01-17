# Covid-19 India Dashboard

A Tableau dashboard tracking Covid-19 cases, deaths, and recoveries across Indian states and districts.

**Dashboard:** [View on Tableau Public](https://public.tableau.com/views/COVID19-India_Dashboard)

---

## What It Does

Visualizes India's Covid-19 data with district-level granularity. Built during the pandemic when existing dashboards were either too slow to update or lacked the geographic detail I wanted.

Data comes from covid19india.org's API through a custom Web Data Connector.

---

## Features

- **District-level data** — Drill down from national to state to district
- **Daily updates** — Pulls fresh data on each refresh
- **Key metrics** — Active cases, total deaths, recovery rates
- **Trend analysis** — See how curves flattened (or didn't) over time

---

## Tech

- **Tableau Public** — Dashboard and visualizations
- **Web Data Connector** — Custom JSON API connector for covid19india.org
- **JavaScript** — WDC implementation

---

## The .twbx File

`COVID19-India_Dashboard.twbx` is the packaged Tableau workbook. Open it in Tableau Desktop or upload to Tableau Public.

---

Built in 2020 when understanding the spread mattered. The API has since been deprecated as the pandemic evolved.
