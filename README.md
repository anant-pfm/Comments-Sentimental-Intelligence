# Sentiment Intelligence Dashboard

A fully self-contained, single-file interactive dashboard for analysing comment sentiment across audio series shows.

## 📁 Repository Files

| File | Description |
|------|-------------|
| `index.html` | The complete dashboard — all JS, CSS and data embedded. This is all you need. |
| `data.csv` | Raw comment source data (28,020 rows) for reference |

## 🚀 Live Demo via GitHub Pages

1. Upload both files to a GitHub repo
2. Go to **Settings → Pages**
3. Source → `Deploy from a branch` → `main` → `/ (root)` → **Save**
4. Live at `https://<your-username>.github.io/<repo-name>/`

> `index.html` is fully self-contained — all chart data is embedded inside it. No server, no build step, no dependencies to install.

## 📊 Dashboard Features

### Tab 1 — Analytics & Charts
- Sentiment Trend (daily line chart, Apr 1 – May 11 2026)
- KPI cards — Negative / Positive / Neutral / Mixed
- Action alert with top issue drivers
- Issue breakdown — Plot · Production · Platform · Technical
- Sentiment split donut · Top Shows bar · Stacked show breakdown · Top Issues bar
- **Filters:** Show Title ↔ Show ID (linked) · Date range

### Tab 2 — Comment Explorer
- 28,020 comments, paginated (50/page)
- **Filters:** Show Title · Show ID · Sentiment · Date From/To · Tags (59 sub-categories, multi-select) · Free-text search
- Active filter badge confirms when filters are applied

### 🌙 Light / Dark mode toggle

## 📦 Tech

Vanilla HTML/CSS/JS · Chart.js 4.4.1 · Pako 2.1.0 · DM Sans + DM Mono (Google Fonts)
