# SkyWhisper
**Long-term weather probabilities with real-life preparedness tips — powered by NASA Earth data, AI analysis, and human-centered design.**

> “What are the chances of extreme weather, and how should we prepare?”  
Skywhisper+ transforms decades of open NASA datasets into **actionable probabilities** (e.g., “70% chance of >35°C”) plus simple guidance (hydrate, umbrella, sunscreen, avoid low-lying areas).
 Designed with **Figma AI** to accelerate UI/code handoff and illustrated with **Gamma AI** for lightweight visuals.

---

## ✨ What it does
- **Probability of extremes** by location, timeframe, and variable (heat, heavy rain, wind, humidity, cloud cover).
- **Plain-language tips** for everyday preparation.
- **Interactive dashboards** with graphs, maps, and summaries.

---

## 🛰️ Data sources
- **NASA POWER** – temperature & rainfall  
- **MERRA-2** – humidity & wind  
- **MODIS** – cloud cover  
- **GPM** – precipitation & extremes

---

## 🧠 How it works
1. Users select **location**, **timeframe**, and **variable**.  
2. We fetch historical archives from NASA APIs and bulk files.  
3. Python pipelines apply **Fourier Transform** to detect seasonal cycles and compute **long-term probabilities** of extremes.  
4. Results render in dashboards with clear summaries and practical advice.

**Example outputs**
- *“65% chance of >35°C in April.”*  
- *“80% likelihood of heavy rain in July — carry an umbrella; secure belongings; avoid low-lying areas.”*

---

## 🎨 Design & Assets (Figma AI + Gamma AI)
- **Figma AI**: Used for UI ideation, auto-layout refinements, and generating code-ready component specs to streamline handoff to the frontend (design tokens, component variants, and layout guidance).  
- **Gamma AI**: Used to generate lightweight **illustrations, icons, and hero images** for dashboards and docs, ensuring clear communication of risk levels without heavy asset pipelines.
