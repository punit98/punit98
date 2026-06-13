<div align="center">

## 🛰️ PUNIT SINGH  

### Data Nerd • Embedded Tinkerer • Mixed Reality enthusiast • 

**Professionally, I am a data engineer.** 
**Personally, I build things that log life, automate chaos, and occasionally short-circuit (un-intentionally).**  

<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZDR5dmdwYXQ3cTM2YXRjMTJkaDJnZnQ3bThqa2c3dGNmZDkxb2N5OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MuPe4OFkceuChGQk1L/giphy.gif" width="150" />

[![GitHub](https://img.shields.io/badge/punit98-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/punit98) [![Email](https://img.shields.io/badge/email-3d3d3a?style=flat-square&logo=protonmail&logoColor=white)](mailto:punit98@protonmail.com) [![Dribbble](https://img.shields.io/badge/dribbble-EA4C89?style=flat-square&logo=dribbble&logoColor=white)](https://dribbble.com/Fab13) ![Location](https://img.shields.io/badge/UK-lightgrey?style=flat-square)

</div>

---

I also dabble in: 
Machine Learning · Robotics · automation · 3D animations · Augmented reality
I once taught a virtual hummingbird to find flowers using only its "eyes". (not joking)

if something can be quantified, i'll measure it.  
if it repeats, i'll automate it.  

---

## 🚀 what i'm building right now

| | project | status |
|---|---|---|
| 🛰️ | **Location Logging Keychain** — esp32 + RYS8830 + ultra-low-power firmware | 🟡 in progress |
| 📊 | **Quantified Self ETL** — raw life-logs → Databricks medallion pipeline → dashboards | 🟠 almost done |
| 🤖 | **Jobhunt Bot** — AI-assisted job application tooling | 🟢 live |
---

## 🚀 the Quantified Self Project

The goal is simple: log life so obsessively that Future Me can answer extremely important questions like “what did I eat for breakfast last Tuesday?” without guessing.

On a serious note, by tracking the tiny details, I can actually see what helped me grow, what slowed me down, and what habits secretly sabotaged my progress.

It’s part self‑experiment, part personal analytics, part “I wonder what happens if I measure everything.”

<div align="centre">

```
What I currently log :

🏋🏽‍♀️ Every workout set in the gym (7k+ sets and counting)
📍 My location every 2 minutes
♥️ Hourly health Metrics exported from the health app
⚡️ Energy / Stress / Mood at various points in the day
🍗 Everything that I've eaten
📱 Apps that I've opened
🗒️ Micro‑journaling — one‑sentence emotional snapshots throughout the day

(automated, each record with a location, weather at said location and a timestamps)

How I log and what happens to the logs, you ask? 


⛃ Apple shortcuts and automations → log it to a raw CSV on iCloud  
            ↓  
☁️ Apple Shortcuts → Automatic upload to a Unity Catalog volume
            ↓  
📦 Unity Catalog Volume → raw schema (scheduled pipeline)  
            ↓  
🥉 Bronze (DLT streaming) →  streaming · append-only · timestamped  
            ↓  
🥈 Silver (DLT) → typed · deduplicated · trustworthy  
            ↓  
🥇 Gold (DLT) → weekly trends · category splits · daily and weekly scores  
            ↓  
⚙️ GitHub Actions → validate on PR · deploy on merge  
            ↓  
📈 Power BI → native Databricks connector · auto-refresh
```

</div>


---

## 🗂 featured projects

### `quantified_self` — personal data platform 

An enterprise-grade medallion-architecture pipeline on Databricks for my personal life logs. CSVs are ingested via Apple Shortcuts into a Unity Catalog Volume, processed through Delta Live Tables (Bronze → Silver → Gold), and visualised in Power BI via the native Databricks connector.

Infrastructure is managed as code with Databricks Asset Bundles and deployed via GitHub Actions. No manual steps from export to dashboard.

---

### `jobhunt-bot` — AI-powered job application assistant

Playwright scrapes JavaScript-heavy and iframe-based job boards. The Anthropic Claude API grades each role A–D against my candidate profile (that I have in a csv because it is much better than a CV), generates tailored CVs, and writes bespoke cover letters. Runs locally on macOS via a simple launcher.
(I tried using Ollama for a truly local LLM, but my laptop started crying and I took pity on it)

---

### `gnss-keychain-logger` — keychain-sized GPS logger (in progress)

ESP032 module with the RYS8830 GNSS module in a 3d printed casing. Ultra-low-power firmware where you're counting microamps. Logs GPS position to flash storage every 30 seconds, designed to live on a keychain and run for weeks on a small battery.

---


## 🗺️ Visual: My Projects at a Glance
<p align="center">
  <img src="https://github.com/punit98/punit98/blob/main/assets/network-map.svg" width="80%" />
</p>


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
