# Proformance Sales

Standalone HVAC sales presentation and pricing tool. This repository has no dependency on any other repository.

## Contents

| File | Purpose |
|---|---|
| `sales.html` | Presentation page and styling |
| `sales-data.js` | Price book data (furnaces, AC, dual fuel, ductless, rebates) |
| `sales-app.js` | Pricing and selection logic |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest` | Installable app manifest |

## Features

- Conventional / ductless toggle
- Good, Better, Best and Dual Fuel cards with combined installed totals per card
- Good card carries its own furnace stage selector; higher tiers always use a communicating furnace and are unaffected by that choice
- Shared higher-tier furnace type selector
- Dual fuel rebate display, with ThermWise suppressed on 80% furnaces
- Customer view and internal view (cost, margin, dealer incentives)
- Peak season pricing May 15 - Aug 31

## Deploy

Served with GitHub Pages from the default branch.
