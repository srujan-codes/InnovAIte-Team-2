# AEGIS — AI-Enabled Global Intelligence for Systemic Resilience

A real-time cascading risk intelligence platform that models how existential threats (climate, pandemics, food crises, infrastructure failure) propagate across interconnected global systems — giving vulnerable communities transparent, explainable, actionable early warnings BEFORE the dominoes fall.

## Details

### What problem does this project solve?

Existential risks don't happen in isolation — they cascade. A drought triggers food shortages, which trigger mass migration, which overwhelms infrastructure, which sparks pandemics.

**Real example:** The 2010 Russian heat wave destroyed 25% of their wheat crop, doubled global wheat prices, caused food riots in North Africa, and contributed to the Arab Spring. One climate event. One cascade. Entire nations reshaped.

Yet every early warning system today watches ONE threat at a time in ONE region. Climate scientists track heat. Economists track prices. Political analysts track unrest. Nobody connects the chain.

AEGIS solves this by building a graph-based AI system that maps how risks flow between domains (climate → food → migration → health) and across geographies — giving communities and governments a real-time map interface showing how a single trigger event can cascade into a multi-system crisis. Every prediction is fully explainable through our Glass Box transparency engine.

---

### Did you use any interesting libraries or services?

**Commonstack.ai (CORE):**
- Multi-LLM orchestration gateway
- Smart routing: Complex analysis to Claude, translations to Gemini Flash
- Multi-model consensus: 3 LLMs must agree for critical alerts
- Provider failover for emergency reliability
- Cost optimization (~60% savings)

**DevSwarm:**
- Parallel AI-assisted coding
- 4 Builders on isolated Git branches
- Claude Code + Gemini running in parallel
- Zero merge conflicts, ~4x dev velocity

**Cascade Engine:**
- Graph Attention Networks — risk propagation
- BERT — parsing unstructured text
- Bayesian probability scoring — confidence levels
- K-Means + DBSCAN — vulnerability clustering

**Data Sources (12 APIs, 6 domains):**
- Climate: NASA GISS, NOAA, Copernicus ERA5
- Health: WHO GHO, ProMED
- Food: FAO GIEWS, USDA FAS
- Displacement: UNHCR
- Conflict: ACLED
- Economic: World Bank
- Infrastructure: OpenStreetMap
- Satellite: Sentinel-2

---

### What extension type(s) did you build?

1. **Interactive Map Interface** — Real-time cascade visualization with animated propagation arcs and pulsing epicenters

2. **Multi-Scenario Simulation Engine** — 9 pre-built scenarios: East Africa Drought, Bangladesh Cyclone, Zoonotic Pandemic, Arctic Permafrost Collapse, Amazon Tipping Point, Cyberattack, Antibiotic Resistance, Mega-Quake, Freshwater Crisis

3. **Glass Box Explainability Panel** — Confidence scores, data sources, LLM consensus, causal paths, bias checks, energy tracking

4. **Real-Time Statistics Dashboard** — Regions affected, cascade events, population at risk, severity percentage

5. **Commonstack.ai Multi-LLM Backbone** — Risk narratives, action plans, multi-model consensus

---

### If given longer, what would be the next improvement you would make?

1. **Live Data Integration** — Connect real-time feeds from NASA, WHO, FAO, NOAA APIs

2. **Federated Learning** — Regional organizations train localized models without sharing sensitive data

3. **Edge Deployment** — Core risk graph on edge devices for limited-connectivity communities

4. **Voice-First Multilingual Interface** — Natural language interaction in local languages via Commonstack.ai

5. **UN OCHA Integration** — Partner with disaster management agencies for real-world deployment

6. **Historical Backtesting** — Validate against documented cascades (2010 Arab Spring, 2020 COVID-19)

7. **Mobile App** — Push notifications with offline functionality

---

## Set Up Instructions

### Run the Live Demo (No installation required!)

Simply open `AEGIS_LIVE_DEMO.html` in any modern browser:
```bash
# Mac
open AEGIS_LIVE_DEMO.html

# Windows
start AEGIS_LIVE_DEMO.html

# Linux
xdg-open AEGIS_LIVE_DEMO.html
```

The demo is a standalone HTML file — works offline, no dependencies!


### Third-Party Registrations

| Service | Purpose | URL |
|---------|---------|-----|
| Commonstack.ai | Multi-LLM orchestration | commonstack.ai |
| DevSwarm | Parallel AI coding | (used during development) |

---

## Screenshots
<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/596d4c2c-5312-4082-8631-d36fb4e44a82" />


**Demo Features:**
- World map with animated cascade propagation
- Left sidebar: 9 scenario options
- Right feed: Real-time event log
- Bottom: Timeline scrubber with play/pause
- Glass Box: Click any event for full explainability

---

## Collaborators

- Karthik — Coordinator
- Ihika — Feasibility
- Banu — Architecture
- Raja — Tech Depth
- Srujan — Visualization
- Satwik — Ethics & Impact
