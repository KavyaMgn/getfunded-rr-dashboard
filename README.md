# R&R Lead Intelligence Dashboard
### GetFunded × Data Service Corps | April 2026

A prototype dashboard for the Research & Recovery (R&R) system built for GetFunded, a consulting firm that helps schools recover denied E-Rate funding.

## What This Does
- Pulls denied E-Rate FRN (Funding Request Number) data from USAC's public API
- Classifies each denial as Green (prime lead), Yellow (past deadline), or Red (fatal violation)
- Displays a prioritized lead list for GetFunded's sales team
- Shows verbatim DR1 denial remarks and plain language summaries per FRN
- Includes filters by state, classification, and denial reason

## Status
🚧 Draft prototype — for discussion only. Data shown is a sample subset from Wave 48. Numbers will reflect live USAC data in the production system.

## Tech Stack (Current — Phase 1)
- HTML / CSS / JavaScript (static prototype)
- Data sourced from USAC Socrata Open Data API

## Roadmap
- Phase 2: Python / Flask backend
- Phase 3: Tableau / Streamlit dashboard connected to live API
- Phase 4: Automated R&R bot with Human-in-the-Loop

## Built By
Kavya Murugan — Data Service Corps
