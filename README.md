# David Tejkl

**Junior Data / BI Analyst** 

· SQL Server · Python · Power BI

14 years of working with operational data in industry · 4 years of requirements analysis — now moving into data analytics.

For 14 years I have worked in industry, where the answer to almost every problem
is in the data. My job has always been to collect it, read it and find out what it is telling us.

**Operational data — collection and analysis**

- Collect and record energy consumption for each production line
- Analyse alarm and signal histories from the control system (AVEVA InTouch, Siemens S7 PLCs in TIA Portal)
  to find the root cause of faults — filtering the records until the data explains what happened
- Example: a kiln stopped calculating its fuel dose. By filtering the previous day's signal records I traced it
  to a single sensor that never sent its "open" signal — one missing data point stopped the whole calculation.
  That is why I check data before I trust it.

**Requirements and change analysis** · since 2022

- Gather and analyse requirements from operators and production staff
- Turn them into specifications for an external Siemens programmer — including data inputs such as the exact
  fault timestamps for the history analysis or an inventory of drives (name, converter type, serial number)
- Test every change on site and with the operators (user acceptance), train users, keep the documentation up to date
- Example: an unclear fault message and a manual reset made the kiln wait 10–60 minutes for maintenance.
  After the change, operators see the cause and reset the fault from the control room in about 20 seconds.

**Data analytics** · now

- End-to-end project on real Czech energy data: Python → SQL Server star schema → T-SQL analysis → Power BI _(in progress)_
- I bring what many junior analysts are still learning: domain knowledge of industry and energy, and the habit
  of proving a number before reporting it

Technical education in automation and industrial informatics.

**Open to Data / BI Analyst roles** · Olomouc · Brno · Prague · hybrid

---

## Featured project

### [Energy Crisis Cost Analysis](https://github.com/DavidTejkl/energy-crisis-cost-analysis)

How much did the 2021–2023 energy crisis cost a Czech company — and could it have been hedged?

- **Finding:** in 2022 the Czech day-ahead market traded electricity worth **7.5× more than in 2020**,
  while the volume grew only **8 %** — the price did almost all of it.
- **Pipeline:** Python download → cleaning → SQL Server star schema → T-SQL analysis
  (CTE, window functions) → Power BI _(in progress)_
- **Data:** 43,848 hourly prices from OTE-ČR, EUR/CZK and repo rate from ČNB — real public data, no Kaggle
- **Quality:** 27 data-quality tests; the data layer rebuilds byte-identical from a clean clone
- **Outlier ≠ error:** a price spike of 844 EUR/MWh on 12 Dec 2024 traced to a _Dunkelflaute_
  in Germany — verified against the raw source and kept in the data

---

## How I work

- **Verify, then trust** — every result is executed and cross-checked by a second, independent query
- **Document decisions** — grain of every table, KPI definitions, decision records (ADRs)
- **Explain it simply** — findings with numbers, written for a CFO, not for another analyst

---

## Stack

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

`T-SQL` · `CTE` · `window functions` · `star schema` · `data quality testing` · `ETL` ·
`requirements analysis` · `user acceptance testing` · `technical documentation` · `Siemens TIA Portal / SCADA`

---

## Certifications

| Certificate                                                          | Issuer               | Date     | Verify                                                               |
| -------------------------------------------------------------------- | -------------------- | -------- | -------------------------------------------------------------------- |
| IBM Data Analyst Professional Certificate (11 courses)               | IBM · Coursera       | Jan 2026 | [verify](https://coursera.org/verify/professional-cert/PI2M929BV7PQ) |
| Microsoft Power BI Data Analyst Professional Certificate (8 courses) | Microsoft · Coursera | May 2026 | [verify](https://coursera.org/verify/professional-cert/VMJCV0XS51HU) |
| Microsoft SQL Server Professional Certificate (5 courses)            | Microsoft · Coursera | Jun 2026 | [verify](https://coursera.org/verify/professional-cert/5UCGTNEZW21K) |

---

📧 davidtejkl94@gmail.com &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/david-tejkl-1155b1384/)
