<div align="center">

╭─────────────────────────────────────────────────────────────╮
│                                                             │
│   hi. i'm punit.                                            │
│   i make data go places.                                    │
│   sometimes i also solder things at 1am.                    │
│                                                             │
╰─────────────────────────────────────────────────────────────╯

[![Portfolio](https://img.shields.io/badge/punitsingh.info-3d3d3a?style=flat-square&logoColor=white)](https://punitsingh.info)
[![GitHub](https://img.shields.io/badge/punit98-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/punit98)
[![Email](https://img.shields.io/badge/email-3d3d3a?style=flat-square&logo=protonmail&logoColor=white)](mailto:punit98@protonmail.com)
[![Dribbble](https://img.shields.io/badge/dribbble-EA4C89?style=flat-square&logo=dribbble&logoColor=white)](https://dribbble.com/Fab13)
![Location](https://img.shields.io/badge/West_Bromwich,_UK-lightgrey?style=flat-square)

</div>

---

currently: **data engineering** by day, **GNSS firmware** by night.  
also: robotics builder · automation architect · MSc Computer Science · person who once taught a virtual hummingbird to find flowers using only its eyes.

if something can be measured, i'll measure it.  
if it repeats, i'll automate it.  
if it's YAML, i'll be humbled eventually.

---

## 🚀 what i'm building right now

| | project | status |
|---|---|---|
| 🛰️ | **GNSS Keychain Logger** — custom PCB + RYS8830 + ultra-low-power firmware | 🟡 in progress |
| 📊 | **Quantified Self ETL** — raw life-logs → Databricks medallion pipeline → dashboards | 🟢 live |
| 🤖 | **Jobhunt Bot** — AI-assisted job application tooling | 🟢 live |
| 🧰 | **Python Automation Tools** — docx generators, CLI utilities, workflow engines | 🟡 in progress |

---

## 📊 the ETL pipeline

📱 Apple Shortcuts → raw CSV on iCloud  
↓  
📦 Unity Catalog Volume → landing zone (automated PUT)  
↓  
🥉 Bronze (DLT streaming) → immutable · append-only · timestamped  
↓  
🥈 Silver (DLT) → typed · deduplicated · trustworthy  
↓  
🥇 Gold (DLT) → weekly trends · workout splits · wellness scores  
↓  
⚙️ GitHub Actions → validate on PR · deploy on merge  
↓  
📈 Power BI → native Databricks connector · auto-refresh

---

## 🗂 featured projects

### `quantified_self` — personal data platform

A production-grade medallion-architecture pipeline on Databricks. Fitness and wellness CSVs are ingested via Apple Shortcuts into a Unity Catalog Volume, processed through Delta Live Tables (Bronze → Silver → Gold), and visualised in Power BI via the native Databricks connector.

Infrastructure is managed as code with Databricks Asset Bundles and deployed via GitHub Actions. No manual steps from export to dashboard.

---

### `jobhunt-bot` — AI-powered job application assistant

Playwright scrapes JavaScript-heavy and iframe-based job boards. The Anthropic Claude API grades each role A–D against a candidate profile, generates tailored CVs, and writes bespoke cover letters. Runs locally on macOS via a simple launcher.

---

### `gnss-keychain-logger` — keychain-sized GPS logger

Custom PCB around the RYS8830 GNSS module. Ultra-low-power firmware where you're counting microamps. Logs GPS position to flash storage, designed to live on a keychain and run for weeks on a small battery.

---

## 🛠 the stack

- Databricks · Unity Catalog · Delta Live Tables  
- Python · SQL · C/C++ · YAML · Bash  
- uv · Ruff · Playwright · Click · python-docx  
- ESP32 · Arduino · RYS8830 GNSS · custom PCB · 3D printing  
- GitHub Actions · Databricks Asset Bundles · Apple Shortcuts  
- Anthropic Claude API · OpenCV · TensorFlow/Keras · RL  
- Power BI  

---

## 📊 skill bars

Databricks            ████████████████████░░░  88%  
SQL                   ███████████████████░░░░░  87%  
Python                ██████████████████░░░░░░  85%  
Delta Live Tables     █████████████████░░░░░░░  83%  
ESP32 / C++           ████████████████░░░░░░░░  80%  
Claude API            ████████████████░░░░░░░░  80%  
ML / Deep Learning    ███████████████░░░░░░░░░  75%  
GitHub Actions        ███████████████░░░░░░░░░  76%  
PCB design            ██████████████░░░░░░░░░░  72%  
Power BI              ██████████████░░░░░░░░░░  72%  

---

## 🦾 robots i've built

**01 — GNSS Keychain Logger**  
Custom PCB around the RYS8830 GNSS module. Ultra-low-power firmware. Logs GPS to flash. Designed to run for weeks.

**02 — B.H.A.I (Basic Home Automation Interface)**  
Voice-controlled home automation over Bluetooth. Featured on Instructables.

**03 — Gesture-Controlled Vehicle**  
Tilt your wrist → robot turns. Accelerometer + RF + Arduino.

**04 — Pick-and-Place Robot Arm**  
4-servo arm, 3D-printed structure, joystick-controlled.

**05 — Servo-Controlled Line Following Robot**  
One motor + one steering servo. Weird idea. Worked beautifully.

---

## things i believe

→ if a pipeline needs a human to run it, it's not finished  
→ boring operations are a compliment  
→ measure before you optimise  
→ YAML will humble you  
→ uv and ruff are non-negotiable  
→ the best side project solves your own problem  

---

## currently curious about

- pushing GNSS power budgets into multi-day territory  
- richer Silver/Gold DLT transformations  
- turning `quantified_self` into a reusable open-source template  
- embedded hardware × cloud analytics  

---

<div align="center">

*somewhere in west bromwich, a pipeline is running*  
*and a GNSS module is logging.*  
*both are fine.*

</div>
