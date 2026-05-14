# QA Assessment — Full Grading Sheet

> **Assessor:** Aashish Kant  
> **Role applied for:** Quality Assurance Engineer — Spotter AI  
> **Date:** May 2026  
> **Scale:** 1 (Poor) → 5 (Excellent) per criterion  

---

## Scoring Key

| Score | Meaning |
|-------|---------|
| 5 | Excellent — fully meets or exceeds requirement |
| 4 | Good — mostly meets requirement with minor gaps |
| 3 | Average — partially meets requirement |
| 2 | Below average — significant gaps |
| 1 | Poor — requirement not met |

---

## Grading Table

| # | GitHub | Hosted | ELD Accuracy | I/O Criteria | UI Aesthetics | UX Intuitiveness | Bugs | **Overall** | Notes |
|---|--------|--------|:------------:|:------------:|:-------------:|:----------------:|:----:|:-----------:|-------|
| 1 | [fless-lab/truck-trip-planner-frontend](https://github.com/fless-lab/truck-trip-planner-frontend) | [truck-trip-planner.vercel.app](https://truck-trip-planner.vercel.app) | 2 | 3 | 3 | 3 | 3 | **2.8** | GitHub repo returned 404; hosted app unreachable for deep inspection. Insufficient evidence to score higher. |
| 2 | [MoNader99/spotter-hos-frontend](https://github.com/MoNader99/spotter-hos-frontend/tree/main) | [spotter-hos-frontend…vercel.app](https://spotter-hos-frontend-git-main-monader99s-projects.vercel.app/) | 2 | 2 | 2 | 2 | 3 | **2.2** | Standard Create React App scaffold with minimal documentation. No evidence of ELD canvas drawing, map integration, or HOS logic in the repo overview. Very thin implementation. |
| 3 | [okaycodes/we_haul_frontend](https://github.com/okaycodes/we_haul_frontend) | [we-haul-frontend.vercel.app/trips](https://we-haul-frontend.vercel.app/trips) | 4 | 4 | 4 | 4 | 3 | **3.8** | React TypeScript + Vite + Konva (canvas ELD) + Leaflet + OpenRouteService. Enforces 70 hr/8-day cycle. All 4 required inputs present. Modern stack; only 6 commits so testing coverage is uncertain. |
| 4 | [BeniyamL/tripPlaner](https://github.com/BeniyamL/tripPlaner) | [tripplanner.zeaye.com](https://tripplanner.zeaye.com/) | 4 | 5 | 4 | 4 | 4 | **4.2** | Django + MySQL + React + Konva + Leaflet + OpenRouteService. All inputs/outputs documented. Fuel stops every 1,000 mi, 1-hr pickup/dropoff, 70 hr/8-day rule, multi-day log sheets. Well-documented README. Solid overall. |
| 5 | [derek-dv/eld-frontend](https://github.com/derek-dv/eld-frontend) | [eld-frontend-sand.vercel.app](https://eld-frontend-sand.vercel.app/) | 2 | 3 | 3 | 3 | 3 | **2.8** | React + Vite + JS. README is a default Vite template only; no project-specific documentation. Unclear ELD drawing method. |
| 6 | [ademcck/trucktracker-backend](https://github.com/ademcck/trucktracker-backend) | [trucktrack-frontend.vercel.app](https://trucktrack-frontend.vercel.app/) | 2 | 2 | 3 | 2 | 3 | **2.4** | Limited documentation on both front and backend repos. No clear evidence of HOS rules, ELD log drawing, or multi-day sheet generation. |
| 7 | [derickddo/transportation-frontend](https://github.com/derickddo/transportation-frontend) | [transportation-frontend-five.vercel.app](https://transportation-frontend-five.vercel.app) | 3 | 3 | 3 | 3 | 3 | **3.0** | React + Vite + JS with a proper `components/`, `pages/`, `services/` folder structure suggesting some separation of concerns. Documentation still thin; ELD drawing method unclear. |
| 8 | [fedhako7/electronic-logging-device](https://github.com/fedhako7/electronic-logging-device) | [fedesaeld.vercel.app](https://fedesaeld.vercel.app/) | 3 | 4 | 3 | 3 | 3 | **3.2** | Django REST + Tailwind + Leaflet + Nominatim/OSRM. Implements 3 core HOS rules (8-hr break, 11-hr driving, 70-hr cycle). Multi-day log support. Map with location markers. Solid but UI is utilitarian. |
| 9 | [boubacar-mdg/spotter-trip-planner-frontend-react](https://github.com/boubacar-mdg/spotter-trip-planner-frontend-react) | [spotter.lavandesn.com](https://spotter.lavandesn.com/) | 2 | 3 | 3 | 3 | 2 | **2.6** | React TypeScript + Vite, 20 commits but **5 open issues** suggesting known bugs. Deployment uses custom domain. Insufficient README detail on ELD drawing. |
| 10 | [pbnjaay/spotter-front](https://github.com/pbnjaay/spotter-front) | [spotter-front…vercel.app](https://spotter-front-git-master-pbnjaays-projects.vercel.app/) | 3 | 3 | 3 | 3 | 3 | **3.0** | Next.js + TypeScript with clean directory structure (`/app`, `/components`, `/lib`, `/types`). 1 open issue. Documentation minimal; ELD drawing not described. |
| 11 | [abdirehim/Trip-Planner](https://github.com/abdirehim/Trip-Planner) | [trip-planner-g4mm.vercel.app](https://trip-planner-g4mm.vercel.app/) | 2 | 2 | 2 | 2 | 3 | **2.2** | Python-heavy codebase (94%); no Loom submission. Frontend is minimal JS/CSS. No documentation of ELD drawing or map integration. |
| 12 | [devolami/trip-planner](https://github.com/devolami/trip-planner.git) | [eld-generator.netlify.app](https://eld-generator.netlify.app) | 3 | 3 | 3 | 3 | 2 | **2.8** | Next.js + TypeScript, 24 commits. Presence of `error.txt` in repo root is a red flag for unresolved issues. Netlify deployment (not Vercel) is a minor deviation. |
| 13 | [Royweru/truck_planner_frontend](https://github.com/Royweru/truck_planner_frontend) | [truck-pro-driver.vercel.app](https://truck-pro-driver.vercel.app/) | 3 | 3 | 4 | 3 | 3 | **3.2** | React TypeScript + Vite + Tailwind CSS. Styling appears polished based on Tailwind + TypeScript setup. Both frontend and backend repos present. Minimal README detail on ELD logic. |
| 14 | [LM-Fighter-10/TripPlanner](https://github.com/LM-Fighter-10/TripPlanner) | [trip-planner-frontend-tau.vercel.app](https://trip-planner-frontend-tau.vercel.app) | **5** | **5** | **5** | 4 | 4 | **4.6** | 🥇 **RANK 1.** Material-UI + Mapbox Directions API + Django. 24-cell/hour grid with 15-min increments. Implements ALL HOS rules: 11-hr driving, 14-hr window, 10-hr off-duty, 30-min break. Supports BOTH 70-hr/8-day AND 60-hr/7-day cycles with A/B/C recap options. Color-coded duty status. Most complete HOS implementation in the batch. |
| 15 | [UmizDemud/trips-frontend](https://github.com/UmizDemud/trips-frontend) | [trips-frontend-dusky.vercel.app](https://trips-frontend-dusky.vercel.app) | 2 | 2 | 3 | 3 | 3 | **2.6** | No Loom submission. Limited documentation. Insufficient evidence to score highly on ELD accuracy or I/O completeness. |
| 16 | [nikodimosewnetu/Truck-route-planner](https://github.com/nikodimosewnetu/Truck-route-planner) | [pro-truck-route-planner.vercel.app](https://pro-truck-route-planner.vercel.app/) | 1 | 2 | 2 | 2 | 2 | **1.8** | Plain JavaScript + HTML (no React/Django). Stack does not meet the assessment requirement of Django + React. No canvas ELD drawing evident. Very limited. |
| 17 | [itMakai/trip-planner-frontend](https://github.com/itMakai/trip-planner-frontend) | [eld-log-generator.vercel.app](https://eld-log-generator.vercel.app/) | 2 | 2 | 2 | 2 | 3 | **2.2** | Plain JavaScript (89%), 8 commits. Submitted a YouTube link instead of Loom — minor deviation from instructions. No documentation on ELD drawing or HOS rules. |
| 18 | [mumoj/frontend](https://github.com/mumoj/frontend) | [eld-planner.vercel.app](https://eld-planner.vercel.app/) | 4 | 4 | 4 | 4 | 3 | **3.8** | Django backend with dedicated `Routes` and `Logs` apps. Has a `log_generator` module + `/generate_image/` API endpoint producing visual ELD log images. OSRM routing. React 18 + TypeScript + React Bootstrap + Tailwind. TripForm, RouteMap, ELDLogGenerator components. Good architecture. |
| 19 | [dynamodenis/eld_trip_planner_frontend](https://github.com/dynamodenis/eld_trip_planner_frontend) | [eld-trip-planner-frontend.vercel.app](https://eld-trip-planner-frontend.vercel.app/) | 2 | 3 | 3 | 3 | 3 | **2.8** | React + Vite + JS (75% JS, 24% CSS). 11 commits. Documentation is default Vite README. ELD drawing method and HOS logic not described. |
| 20 | [mahdertesf/fullstack_driver_log](https://github.com/mahdertesf/fullstack_driver_log) | [fullstack-driver-log.vercel.app](https://fullstack-driver-log.vercel.app/) | **5** | **5** | 4 | 4 | 4 | **4.4** | 🥈 **RANK 2.** Django REST + React 18 + Vite + Tailwind + Leaflet + OpenRouteService. Implements the full HOS decision hierarchy: weekly 70-hr reset → 14-hr window → 8-hr break → task scheduling. 30-min breaks every 8 hrs. Multi-day trip planning. PDF export for DOT-compliant official log sheets. Trip history management. Structured JSON API response. |

---

## Rankings — Top 3

| Rank | Candidate | Overall Score |
|------|-----------|:--------------:|
| 🥇 1st | **LM-Fighter-10** (Candidate 14) | **4.6 / 5** |
| 🥈 2nd | **mahdertesf** (Candidate 20) | **4.4 / 5** |
| 🥉 3rd | **BeniyamL** (Candidate 4) | **4.2 / 5** |

See [top3_analysis.md](top3_analysis.md) for the full Loom-ready analysis of these three.
