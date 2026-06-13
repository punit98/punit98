
<div>

## Data Nerd • Human • Tinkerer • Mixed Reality enthusiast


**Professionally, I am a data engineer.** 

**Personally, I build things that log life, automate chaos, and occasionally short-circuit (un-intentionally).**  

**I also teach machines how to think.**
</div>


[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square)](https://linkedin.com/in/punit98) [![GitHub](https://img.shields.io/badge/punit98-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/punit98) [![Email](https://img.shields.io/badge/email-3d3d3a?style=flat-square&logo=protonmail&logoColor=white)](mailto:punit98@protonmail.com) [![Dribbble](https://img.shields.io/badge/dribbble-EA4C89?style=flat-square&logo=dribbble&logoColor=white)](https://dribbble.com/Fab13)


---


## ⚙️ The stack
```
- Databricks · Unity Catalog · Delta Live Tables  
- Python · SQL · PySpark
- Power BI · Looker · Matplotlib
- Azure AI studio · Tensorflow / Keras · Machine Learning · Anthropic Claude API 
- ESP32 · Arduino · RYS8830 GNSS · 3D printing  
- GitHub Actions · Declarative Automation Bundles · Apple Shortcuts  
```
---

```
Also dabble in: 
Robotics · Automation · 3D animations · Augmented reality.

i once taught a bot to find flowers using only its "eyes". (not joking)

if something can be quantified, i'll measure it.  
```
---

## what i'm building right now

| | project | status |
|---|---|---|
| 📊 | **Quantified Self** — raw life-logs → Databricks medallion pipeline → dashboards | 🟢 live |
| 🛰️ | **Location Logging Keychain** — esp32 + RYS8830 + ultra-low-power firmware | 🟡 in progress |
| 🤖 | **Jobhunt Bot** — AI-assisted job application tooling | 🟢 live |
---

## 🗂 Featured projects


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
📱 Apps I use
🗒️ Micro‑journaling — one‑sentence emotional snapshots throughout the day

(Completely automated, each record triggers a location, weather and a timestamp log as well)

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
📈 Power BI → native Databricks connector · auto-refresh
```

</div>


---


### `jobhunt-bot` — AI-powered job application assistant

The bot takes a job description, The Anthropic Claude API grades each role A–D against my candidate profile (that I have in a csv because it is much better than a CV), generates bespoke cover letters. Runs locally on macOS via a simple launcher.
(I tried using Ollama for a truly local LLM, but my laptop started crying and I took pity on it)

---

### `keychain-location-logger` — keychain-sized GPS logger (in progress)

Logs GPS position to flash storage every 30 seconds, designed to live on a keychain and run for weeks on a small battery.
ESP32 module with the RYS8830 GNSS module in a 3d printed casing. Ultra-low-power firmware where you're counting microamps.

## 🦾 robots i've built

**01 — B.H.A.I (Basic Home Automation Interface)**  
Voice-controlled home automation over Bluetooth. Featured on Instructables.

**02 — Gesture-Controlled Vehicle**  
Tilt your wrist → robot turns. Accelerometer + RF + Arduino.

**03 — Pick-and-Place Robot Arm**  
4-servo arm, 3D-printed structure, joystick-controlled.

**04 — Servo-Controlled Line Following Robot**  
One driving motor to wheels + one steering servo motor. Weird idea. Worked beautifully.

---


<div align="center">

*somewhere in the world, a pipeline is running*  
*and a GNSS module is logging.*  
*both are fine. am I?*

</div>

