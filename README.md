🌤 SkyWhisper

NASA-Powered Long-Term Weather Insights & Preparedness Dashboard

🚧 Status: Prototype — Actively evolving
We’re iterating on data coverage, model accuracy, and UX. Expect changes and breaking updates.

✨ Overview

SkyWhisper transforms decades of NASA Earth observation datasets into actionable probabilities and plain-language preparedness tips. It helps people anticipate extreme weather events (heat, rainfall, wind, humidity, cloud cover) and make informed lifestyle or policy decisions.

Example insights:

“65% chance of >35°C in April — stay hydrated.”

“80% likelihood of heavy rain in July — carry an umbrella, secure belongings, avoid low-lying areas.”

Unlike real-time alerts, SkyWhisper focuses on long-term patterns and seasonal probabilities to support preparedness, planning, and resilience.

🚀 Features

📊 Extreme Weather Probabilities — by location, timeframe, and variable (heat, rainfall, humidity, wind, cloud cover).

📝 Plain-language Tips — hydration, umbrellas, sunscreen, safety guidance.

🌍 Interactive Dashboards — maps, graphs, and summaries.

🛰️ Open NASA Data Sources — multiple datasets combined into one view.

⚕️ Health Alerts (roadmap) — heat index, air quality hooks.

🌊 Disaster Readiness Modules (roadmap) — flood & wind advisories.

🌱 Crop Planning Tools (roadmap) — seasonal calendars for farmers.

🌐 Multilingual Support (roadmap) — accessibility across regions.

📤 Data Export (roadmap) — for researchers & policymakers.

🧱 Tech Stack

Python → NumPy, SciPy, pandas, xarray

Geospatial → rasterio, pyproj

Visualization/UI → Streamlit, Plotly

Design System → Figma AI (design tokens, UI specs, auto-layouts)

Illustrations/Assets → Gamma AI (icons, risk visuals)

Video Demos → Canva (storytelling & awareness content)

APIs/Datasets:

NASA POWER (temperature, rainfall)

MERRA-2 (humidity, wind)

MODIS (cloud cover)

GPM (precipitation & extremes)

⚙️ API Configuration

To run SkyWhisper, you’ll need NASA Earth data APIs:

NASA POWER API
Variables: temperature, rainfall

GES DISC (MERRA-2, MODIS, GPM)
Access via NASA EarthData Login

Python Environment

conda create -n skywhisper python=3.10
conda activate skywhisper
pip install numpy scipy pandas xarray rasterio pyproj streamlit plotly


🎨 Design & Communication System

Figma AI → Ideation, component variants, design tokens, code-ready specs.

Gamma AI → Lightweight illustrations, icons, hero images for dashboards.

Canva → Used to create video explainers, demos, and awareness campaigns to show SkyWhisper in action. Canva supports:

Short feature walkthroughs

Storytelling with real-life preparedness examples

Social media clips for outreach

🔗 Figma Prototype

https://www.figma.com/make/M7HhzhhuwtKWbSf4x5g25Q/Weather-Dashboard-Prototype?node-id=0-1&t=kcraxAIN2oforfze-1


📄 Main Plan & Flows (Google Drive)

https://drive.google.com/drive/folders/17gY5buTk7rH2Qgmaeid5F-SfQCC5Zc9O

🎓 Project Education & Impact

SkyWhisper is designed for:

General public — daily preparedness guidance.

Farmers — seasonal crop planning and water management.

Health sectors — anticipating heat stress or air-quality risks.

Policy makers — insights into long-term climate risks for planning.

Researchers — access to preprocessed datasets and probability outputs.

🗺️ Roadmap

✅ Prototype — Probabilities & dashboards
🔜 Health alerts, disaster modules, crop planning
🌐 Multilingual support
📤 Research/policy data exports

🙏 Acknowledgements

NASA Earth Science Division — for open datasets (POWER, MERRA-2, MODIS, GPM).

Figma AI — for rapid UI prototyping & design-to-code workflow.

Gamma AI — for lightweight illustrations and risk communication visuals.

Canva — for impactful storytelling and awareness videos.

Open-source community — Python, Streamlit, Plotly, and geospatial libraries.

⚠️ Disclaimer

SkyWhisper provides long-term probabilities and general preparedness suggestions.
It is not a real-time warning system and should not be used for emergency decision-making.
For immediate hazards, always consult official weather & emergency services.
