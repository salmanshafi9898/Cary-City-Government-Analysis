# 🏛️ Cary City Government Analysis — Public Safety & Economic Development

> **District-level Tableau dashboard** built for the Mayor of Cary — analyzing Public Safety and Economic Development indicators across all city districts to surface actionable priorities and resource allocation decisions.

---

## 📌 Project Overview

City governments generate enormous amounts of data — crime reports, traffic incidents, fire & EMS logs, building permits — but that data is rarely synthesized into a clear, district-level picture that elected officials can actually act on.

This project does exactly that. Built for the **Mayor of Cary's office**, the analysis cuts across two core pillars — **Public Safety** and **Economic Development** — at the district level, so the mayor's office can coordinate directly with individual district representatives to address bottlenecks and allocate resources where they're needed most.

**Team:** Weihan Liu, Sam MacArthur, Suhas Padi, Arya Pednekar, Salman Shafi
**Course:** DECISION 522Q | Duke Fuqua — Section C, Team 11
**Audience:** Mayor of Cary

---

## 🎯 Two Core Pillars

### 🚔 Public Safety
Crime rates, traffic crashes, and Fire & EMS incident data — analyzed by district, type, and trend to reveal where safety resources are stretched thin.

### 🏗️ Economic Development
Building permit volumes, investment dollars, and processing timelines — analyzed end-to-end (application → final inspection) to identify where development momentum is at risk.

---

## 🔍 Key Findings

### Crime Analysis
- **District C** (Rep. Jack Smith) is the most crime-affected area in Cary — its crime rate is roughly **80% higher than the city-wide average**
- Despite this, overall crime is trending positively — down nearly **20% year-over-year**
- Shoplifting and petty theft make up the bulk of incidents; violent crime remains relatively low at ~8 per 1,000 residents
- ⚠️ **Notable concern:** While crime rates have ticked up in some areas, case resolution times have *decreased* — suggesting possible efficiency gaps within the police force worth investigating

### Traffic Safety
- Cary recorded **over 17,000 crashes** between 2021 and 2024, with incidents rising gradually each year
- Geographically concentrated: **Eastern Cary accounts for ~40% of all crashes**, predominantly on State Secondary Routes
- Encouraging: severe crash rates remain relatively low — frequency is rising, but not severity

### Fire & EMS
- Nearly **28,000 incidents** recorded across the city
- Medical emergencies dominate in every district
- **District C bears the heaviest burden** — handling over **35% of all incidents**

### Building Permits & Development
- Cary issued **over 54,000 building permits** between 2020 and 2025, with volumes rising each year
- Growth driven predominantly by **renovation and upgrades** rather than new construction
- **District C** leads in permit volume; **District B** leads in total investment
- **District D** leads in new housing production — but carries the **longest processing times** in the city:
  - Average of nearly **118 days** end-to-end
  - New construction permits stretching **beyond 400 days at peak**
  - A bottleneck that directly threatens Cary's development momentum

---

## 🗺️ Dashboard Structure (Tableau)

The Tableau workbook (`SectionC_Team11_Tableau.twbx`) contains interactive dashboards across:

| Dashboard | Focus |
|---|---|
| **Crime Overview** | District-level crime rates, YoY trends, crime type breakdown |
| **Traffic Safety** | Crash volume by year, geography, and route type |
| **Fire & EMS** | Incident type distribution, district burden analysis |
| **Building Permits** | Permit pipeline volume, investment by district, processing time analysis |
| **Executive Summary** | Top-line KPIs and priority recommendations for the Mayor |

---

## 🎯 Strategic Recommendations

The analysis points to **two clear city-level priorities:**

**1. District D — Capacity & Infrastructure Investment**
Processing times of 118+ days (and 400+ days for new construction) are a direct threat to Cary's economic growth engine. Targeted investment in permitting capacity and infrastructure is needed to keep development momentum running.

**2. District C — On-the-Ground Safety Presence**
With crime rates 80% above the city average AND the heaviest Fire & EMS burden, District C's residents need a meaningfully stronger safety presence — more resources, faster case resolution, and coordinated multi-agency response.

---

## 📁 Repository Structure

```
├── datasets/                        # Source data files
├── SectionC_Team11_Tableau.twbx     # Full Tableau workbook (open in Tableau Desktop)
├── SectionC_Team11_Summary.docx     # Executive summary report for the Mayor
└── README.md
```

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Visualization | Tableau Desktop (.twbx) |
| Data Sources | Cary City open data (crime, traffic, EMS, permits) |
| Analysis | District-level aggregation, YoY trend analysis, geographic mapping |
| Deliverable | Executive dashboard for Mayor's office |

---

## 👤 Author

**Salman Khan Shafi**
MS Business Analytics — Duke Fuqua '26
[LinkedIn](https://linkedin.com/in/salmankhanshafi) • [GitHub](https://github.com/salmanshafi9898)
