# Skywhisper

> **Status:** Prototype 🚧 — Actively evolving. We’re iterating on data coverage, model accuracy, and UX. Expect changes and breaking updates.


**NASA-powered long-term weather insights with real-life preparedness tips — built on open Earth data, AI, and human-centered design.**  
Skywhisper turns decades of NASA datasets into **actionable probabilities** (e.g., “70% chance of >35°C”) plus simple guidance (hydrate, umbrella, sunscreen, avoid low-lying areas). Designed with **Figma AI** for faster UI/code handoff and illustrated via **Gamma AI** for lightweight visuals.

> 🔗 **Figma **  
> https://www.figma.com/make/M7HhzhhuwtKWbSf4x5g25Q/Weather-Dashboard-Prototype?node-id=0-4&t=8b0fFihGjG30bISK-1

> 📄 **Main plan:**  
> https://drive.google.com/drive/folders/17gY5buTk7rH2Qgmaeid5F-SfQCC5Zc9O

---

## ✨ What it does
- **Probabilities of extremes** by location, timeframe, and variable (heat, heavy rain, wind, humidity, cloud cover).
- **Plain-language tips** to help people prepare in daily life.
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
2. Historical archives are fetched from NASA APIs and bulk files.  
3. Python pipelines apply **Fourier Transform** to detect seasonal cycles and compute **long-term probabilities** of extremes.  
4. Results render in dashboards with clear summaries and practical advice.

**Example outputs**
- *“65% chance of >35°C in April.”*  
- *“80% likelihood of heavy rain in July — carry an umbrella; secure belongings; avoid low-lying areas.”*

---

## 🎨 Design & Assets (Figma AI + Gamma AI)
- **Figma AI **: UI ideation, auto-layout refinements, and code-ready specs (design tokens, component variants, layout guidance) to streamline frontend handoff.  
  Prototype: https://www.figma.com/make/M7HhzhhuwtKWbSf4x5g25Q/Weather-Dashboard-Prototype?node-id=0-4&t=8b0fFihGjG30bISK-1
- **Main Plan (canonical)**: The authoritative plan, UX flows, and requirements live in **Google Drive** →  https://drive.google.com/drive/folders/17gY5buTk7rH2Qgmaeid5F-SfQCC5Zc9O 
- **Gamma AI**: Lightweight **illustrations, icons, and hero images** for dashboards and docs that communicate risk levels clearly.
- canva for video making 

🧱 Tech stack

Python (NumPy, SciPy, xarray, pandas)

Geospatial (rasterio, pyproj)

Viz/UI (Streamlit/Plotly)

Design (Figma AI for UI + code specs)

Assets (Gamma AI for images/illustrations)

APIs (NASA POWER, GES DISC for MERRA-2/MODIS/GPM)

## 🗺️ Roadmap
*Prototype priorities — exactly as planned.*

- Health alerts (heat index, air-quality hooks)
  
- Disaster readiness modules (flood/wind advisories)
  
- Crop-planning tools & calendars
  
- Multilingual support
  
- Data export for researchers & policymakers

## 🔭 Project status & next steps
Skywhisper+ is a **prototype**. We are focusing solely on the items in the roadmap:
1) Health alerts
   
2) Disaster readiness modules
 
3) Crop-planning tools & calendars
   
4) Multilingual support
   
5) Data export for researchers & policymakers


⚠️ Disclaimer

Skywhisper provides long-term probabilities and general preparedness suggestions.
It is not a real-time warning system and should not be used for emergency decision-making.
For immediate hazards, always consult official weather and emergency services.


