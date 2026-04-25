# Kaggle CSV Demo — Power BI Dashboard 📊

A lightweight data analysis and visualization project that loads a combined Kaggle CSV dataset into **Power BI** and produces an interactive dashboard. The repo includes the raw data, the `.pbix` workbook, and a PDF export of the finished visuals.

---

## Overview

This project demonstrates an end-to-end data analytics workflow:

1. Source a public CSV dataset from Kaggle
2. Clean and combine the raw data into a single flat file (`combined_output.csv`)
3. Load it into Power BI Desktop
4. Build an interactive dashboard with charts and filters
5. Export the visuals as a shareable PDF

It serves as a quick reference for anyone learning Power BI or looking for a minimal working example of CSV → dashboard.

---

## Files in this Repo

| File | Description |
|------|-------------|
| `combined_output.csv` | Cleaned and merged dataset ready for analysis |
| `data_visuals.pbix` | Power BI Desktop workbook (all visuals, relationships, and DAX measures) |
| `data_visuals (2).pdf` | Static PDF export of the completed dashboard |
| `README.md` | This file |

---


## Dashboard Highlights

The Power BI report (`data_visuals.pbix`) includes:

- **KPI Cards** — top-line summary metrics at a glance
- **Bar / Column Charts** — category-level breakdowns
- **Line Charts** — trend analysis over time (if the dataset contains dates)
- **Slicers / Filters** — interactive filtering by key dimensions
- **Data Table** — drill-down view of the underlying records

A static snapshot of every page is available in `data_visuals (2).pdf` — no Power BI licence needed to view it.

---

## Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — Windows only
- No Python, no packages, no environment setup required

### Open the Dashboard

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Divija2612/kaggle-csv-demo.git
   ```
2. Open **Power BI Desktop**.
3. Go to **File → Open report** and select `data_visuals.pbix`.
4. If prompted about the data source path, go to **Transform Data → Data Source Settings** and update the path to `combined_output.csv` on your machine.
5. Click **Refresh** to reload the data.

### Just want to see the visuals?

Open `data_visuals (2).pdf` directly in any PDF viewer — no Power BI needed.

---

## How the Data Was Prepared

1. **Downloaded** raw CSV file(s) from Kaggle.
2. **Combined** multiple files (if applicable) into `combined_output.csv`.
3. **Cleaned** in Power BI's Power Query Editor:
   - Removed null / duplicate rows
   - Standardised column names (no spaces, consistent casing)
   - Set correct data types (dates, numbers, text)

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard authoring, DAX, Power Query |
| Microsoft Excel / Python (optional) | Data pre-processing / CSV merging |
| Kaggle | Dataset source |
| Git / GitHub | Version control and sharing |

---

