# LOGIC Lunar Infrastructure Architecture

Live site: https://terrytrevino.github.io/logic-lunar-infrastructure/

This repository contains the current LOGIC lunar-surface infrastructure briefing site and its supporting engineering model.

## Current site

The site presents a modular lunar microgrid architecture built around:

- distributed generation and storage
- three baseline utility nodes
- high-voltage trunk distribution
- isolated DC/DC conversion and local 120 VDC service
- rover charging and service infrastructure
- hardened utility umbilicals
- plant-module expansion
- future firm-power integration
- cargo-limited settlement growth
- technology gaps and development priorities

## Engineering drawings

The current site uses technical drawings as the primary visual language:

- `settlement_blueprint.png`
- `utility_node_cutaway.png`
- `rover_service_blueprint.png`
- `habitat_blueprint.png`

The cinematic settlement rendering is retained for environmental context.

## Engineering model

`LOGIC_Lunar_Surface_Power_Dashboard_v3.xlsx`

The workbook includes facilities and loads, NASA-aligned timing, mission buildout, microgrid nodes, distribution, storage, charging, solar concentrators, supply forecast, technology gaps, development tasks, and the power-conversion layer.

## Deployment

GitHub Pages deploys from:

- branch: `main`
- folder: `/(root)`

The root-level `index.html` is the production homepage.
