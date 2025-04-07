# Valorant Stats Analyzer

**Valorant Stats Analyzer** is a community-focused web application that empowers Valorant players to analyze, understand, and improve their gameplay using Riot's official APIs and RSO (Riot Sign-On) authentication.

Our mission is to deliver **advanced insights**, **interactive visualizations**, and **AI-powered suggestions** through a clean, secure interface. This tool is designed to be **fully opt-in**, in compliance with Riot’s Developer Policy.

---

## 🔥 What Makes This App Unique?

Unlike existing trackers, our app focuses on **personalized, high-level insights** that go beyond basic K/D or agent usage. We aim to **transform data into coaching**, thanks to a mix of AI, UX, and statistical analysis.

### ✅ Innovative Features (Planned)

- 🔥 **Dynamic Heatmaps** – Visualize deaths, kills, or assists per map, agent, and round over time  
- 📊 **Behavioral Trend Tracking** – Analyze how your playstyle evolves across patches or roles  
- 🧠 **AI-powered Coaching** – Get custom suggestions for agent pick, map approach, or weapon usage  
- 📌 **Clutch Review Assistant** – Automatically extract rounds where you were the last alive or defused/planted  
- 📍 **Map-Specific Strategy Insights** – Identify your strongest and weakest bomb sites or map zones  
- 📈 **Performance Consistency Index** – See how stable your KDA, win rate, and HS% are across time  
- 🧪 **Experimental Agent Switch Simulation** – Estimate how a role/agent change could impact your results  
- 🕵️‍♂️ **Mirror Me Mode** – Compare your stats with similar players to detect growth potential  
- ⏱️ **Time-of-Day Impact** – Find your peak performance window based on game time  
- 🛠️ **Custom Training Targets** – Automatically suggest drills based on weaknesses (e.g., headshot % with rifles)

---

## 🔐 How it Works

1. Players securely authenticate via Riot's RSO (OAuth2 flow)
2. The app retrieves their PUUID and match history using `VAL-MATCH-V1`
3. Data is processed and enhanced using custom analytics
4. Players get visual dashboards, graphs, maps, and AI recommendations

All data is:
- 🔒 Stored locally (client-side or backend with encryption)
- 🔐 Displayed only to the authenticated user
- 📘 Fully compliant with Riot’s opt-in policy

---

## 🚀 Project Status

- ✅ GitHub Pages front-end prototype deployed
- ⚙️ Backend parsing & secure API integration in progress
- 🧪 AI models in R&D for performance prediction and player segmentation
- 🔐 RSO authentication flow planned and documented

---

## 🖼️ Prototype Preview

### 🧱 Application Architecture
![Application Architecture](Archi.png)

### 📊 Dashboard Mockup
![Dashboard Mockup](Mockup.png)

---

## 📦 Tech Stack

- Frontend: **HTML/CSS/JS**, fully responsive layout
- Backend: (Planned) **Node.js + Express + MongoDB**
- Data processing: (Planned) **Python + Pandas + scikit-learn**
- API Integration: **Riot Games Developer API (VAL-MATCH-V1, RSO)**

---

## ⚠️ Disclaimer

This is a **non-commercial, in-development** project made for educational and community purposes.  
It is **not affiliated with Riot Games**. All data is accessed through the official API, with player consent via RSO login.

> Riot Games, Valorant, and all related trademarks are property of Riot Games, Inc.

---

## 📫 Contact & Feedback

If you're a Riot developer reviewing this, feel free to reach out via the Developer Portal message section.  
We are open to suggestions and collaborations to improve the player experience.

