<div align="center">

&nbsp;

<h1>Punit</h1>

**Data Engineer · Pipeline Architect · Automation Enthusiast**

*West Bromwich, UK*

&nbsp;

[![Email](https://img.shields.io/badge/Get%20in%20touch-punit98%40protonmail.com-3c3c3c?style=for-the-badge)](mailto:punit98@protonmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com)

&nbsp;

</div>

---

I design and build data systems that are clean by architecture and reliable by habit. My work sits at the intersection of data engineering, personal automation, and applied AI — with a particular interest in end-to-end pipelines that require no manual intervention once they're running.

I believe the best infrastructure is quiet. If a pipeline is drawing attention to itself, something has gone wrong.

---

## Featured Projects

### `quantified_self`
*A personal wellness data platform built on Databricks*

A full medallion-architecture pipeline that ingests fitness and wellness data from CSV exports, processes it through Bronze → Silver → Gold transformation layers via Delta Live Tables, and surfaces insights through Power BI dashboards connected natively to the Delta tables.

The ingestion layer is fully automated: Apple Shortcuts handles the file upload from iCloud to a Unity Catalog Volume, meaning new data enters the pipeline without any manual steps. Deployment is managed via Databricks Asset Bundles with a GitHub Actions CI/CD workflow — validate on pull request, deploy to production on merge.

**Stack:** Databricks · Delta Live Tables · Unity Catalog · Python · SQL · Power BI · GitHub Actions

---

### `jobhunt-bot`
*An AI-powered job application assistant*

A Python application that automates the most time-intensive parts of a job search. Playwright (with Firefox) scrapes job descriptions from JavaScript-rendered and iframe-embedded job boards. The Claude API grades each role against a candidate profile (A through D), generates tailored CVs, and writes bespoke cover letters — all launched from a simple Mac launcher.

**Stack:** Python · Playwright · Anthropic Claude API · macOS

---

## Technical Profile

```
Data Engineering    Databricks · Delta Live Tables · Unity Catalog · Medallion Architecture
Languages           Python · SQL · YAML
Automation          Apple Shortcuts · GitHub Actions · Playwright  
Visualisation       Power BI
AI Integration      Anthropic Claude API
CI/CD               GitHub Actions · Databricks Asset Bundles
```

---

## Principles

**Automate what repeats.** Any manual step that runs more than twice is a candidate for removal.

**Layer your architecture.** Raw data is immutable. Transformations are versioned. Visualisation is decoupled from storage.

**Design for the folder, not the file.** Automations should accommodate new additions without requiring changes to the automation itself.

**Boring operations, interesting engineering.** The goal is a system you stop thinking about — not one that demands constant attention.

---

## In Progress

- Expanding Silver and Gold DLT transformation layers with richer modelling
- Establishing the Power BI ↔ Databricks native connector
- Preparing `quantified_self` as a reusable open-source template

---

<div align="center">

&nbsp;

*Available for interesting conversations about data architecture, pipeline design, or automation.*

&nbsp;

</div>