# Field Shift — Satellite Agriculture Intelligence

**Field Shift** is a bilingual (English & Urdu) geospatial agriculture decision-support web application built for all **36 districts of Punjab**, integrating **NASA POWER** climate telemetry, **NASA SMAP L4** soil moisture metrics, and **Punjab Crop Reporting Service (2024–25)** statistics.

## Features
- **Beginning Guide Portal**: Clean destination selector for quick entry into the workspace or guided walkthrough.
- **36-District Interactive Punjab Map**: Geospatial five-river map with live district rainfall, SMAP wetness, mean temperature, and solar radiation.
- **7-Rotation Decision Engine**: Scores 7 crop rotations out of 100 based on farm area, water source (Canal, Tube-well, Saline, Rain-fed), primary goal, and weather stress scenarios.
- **12-Month Sow & Harvest Gantt Calendar**: Visualized planting, growth/irrigation, and harvest windows.
- **District Yields & PKR Profit Calculator**: Real-time harvest volume and net profit estimation in Pakistani Rupees.
- **Soil Texture & NASA Labs**: Clay/Sand/Silt breakdown, soil pH scale, and organic carbon indicators.
- **Open Data & CSV Export**: Inspect, upload custom CSV/JSON datasets, or export the full 36-district dataset.

## Deploy to GitHub Pages (2 Minutes)
1. Create a new repository on GitHub (e.g., `field-shift`).
2. Upload all files from this package to the `main` branch (preserving `.github/workflows/deploy-pages.yml`).
3. Go to **Settings → Pages** in your GitHub repository.
4. Under **Build and deployment → Source**, select **GitHub Actions**.
5. Your app will automatically build and go live at `https://<your-username>.github.io/<repo-name>/`.

## Local Preview
Run locally with any static server:
```bash
npx serve .
```
