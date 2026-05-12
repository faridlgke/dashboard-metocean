# KAKAP Met-Ocean Dashboard

Web-based dashboard for **Star Energy KAKAP Field** met-ocean forecast service.

## Demo Access

Open the deployed URL and login with:

- **Username:** `admin`
- **Password:** `Nospro321.,`

## Features

- **Overview Page** — Spatial map, KPI cards, 7-day time-series, climate context, alerts
- **Archive Page** — Historical forecasts with calendar heatmap, search & filter, bulk export
- **Calendar Date Modal** — Click any date to see available forecast runs (06 UTC + 18 UTC) with sparkline preview
- **Multi-format Export** — Excel multi-sheet workbook + PDF report with auto-generated narrative
- **Threshold-based Alerts** — Configurable per-parameter tier (Safe/Caution/Warning/Danger)

## Coming Soon

- Wave Analysis · Wind & Gust · Current & Tide · Operability Window · Verification

## Stack

Single-file static HTML mockup using:

- Chart.js for visualizations
- Leaflet for spatial map
- SheetJS (xlsx) for Excel export
- jsPDF + autoTable for PDF reports
- Fonts: Plus Jakarta Sans, Space Grotesk, JetBrains Mono

## Deployment

Pure static site. Deploy to any static host (Vercel, Netlify, Cloudflare Pages):

```bash
vercel --prod
```

---

© 2026 · For demonstration purposes only.
