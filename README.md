# LOGIC Lunar Infrastructure Architecture

Live site: https://terrytrevino.github.io/logic-lunar-infrastructure/

Current engineering baseline: **v6.1 work in progress — Rescue / Survival Modes plus NASA SCaN C&PNT and observability requirements**.

The site now includes explicit operating-state power logic, Utility Node warm-core survival, Emergency Refuge, a 24-hour battery-only bridge, a 7-day safe-haven target, and machine-readable model data.

## Machine-readable data
- `data/operating_modes.csv`
- `data/rescue_endurance.csv`
- `data/model_summary.json`

## Current workbook
The current working master is `LOGIC_Lunar_Surface_Power_Dashboard_v6_1_WIP.xlsx`.

Version 6.1 contains non-material audit corrections to dashboard references and Utility Node warm-core consistency. The occupied-load baselines, operating-mode totals, 24-hour refuge bridge, 168-hour safe-haven target, and architecture conclusions are unchanged. Electrical allocations and system architecture remain engineering work in progress pending hardware, thermal, illumination, site, and mission validation.

`LOGIC_Lunar_Surface_Power_Dashboard_v5.xlsx` is retained only as a historical baseline and should not be used as the current source of truth.

## Data provenance
`data/export_manifest.json` identifies the workbook version and status represented by the published CSV and JSON files.

GitHub Pages deploys from `main` / repository root.
