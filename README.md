# Space 4 All Lunar Infrastructure Architecture

Live site: https://terrytrevino.github.io/logic-lunar-infrastructure/

Current engineering baseline: **v6.2 work in progress**.

This repository is the public technical layer for the Space 4 All lunar-surface infrastructure concept. The current workbook and website cover modular power generation, storage, conversion, distribution, surface service, survival, rescue endurance, mission buildout, and communications / positioning / navigation / timing (C&PNT).

## Major updates integrated

Version 6.2 includes:

- explicit operating modes from nominal service through deep hibernation;
- Utility Node electrical warm-core and thermal-recovery logic;
- six-crew Emergency Refuge at 5.25 kW;
- a 24-hour zero-generation battery bridge and 168-hour safe-haven target;
- modular generation and power-conversion architecture;
- mission buildout and technology-development tasks;
- NASA SCaN C&PNT and observability demand-signal translation; and
- a public-source audit using the current Moon-to-Mars Architecture Definition Document Revision C.

The occupied-load baselines, operating-mode totals, battery bridge, safe-haven target, and architecture conclusions are unchanged from v6.1. The v6.2 work focuses on source quality, public usability, and clear separation between NASA source statements and Space 4 All engineering allocations.

## Next engineering pass

The remaining major analyses are:

1. feeder electro-thermal sizing: voltage drop, conductor loss, insulation, exposure or burial, and heat rejection;
2. site-specific illumination and shadow histories;
3. geotechnical, foundation, trenching, road, berm, and construction-sequence assumptions; and
4. measured electrical and thermal states for representative C&PNT hardware.

## Current workbook

The working master is `Space4All_Lunar_Surface_Power_Dashboard_v6_2_WIP.xlsx`.

Electrical allocations and architecture assumptions remain preliminary pending hardware, thermal, illumination, site, and mission validation.

## Public data

- `data/operating_modes.csv`
- `data/rescue_endurance.csv`
- `data/model_summary.json`
- `data/export_manifest.json`
- `data/references.json`

## Historical material

`LOGIC_Lunar_Surface_Power_Dashboard_v5.xlsx`, earlier v3/v5 workbooks, and the nested `LOGIC_Infrastructure_Website_v5/` directory are retained only for provenance. They are not the current source of truth and should not be presented as the Space 4 All baseline.

GitHub Pages deploys from `main` / repository root.
