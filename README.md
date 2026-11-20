# Smart Power Grid Rescue System (GridRescue AI)

Real-time power grid monitoring, emergency restoration control, and public outage tracking prototype built for hackathon demonstration[span_2](start_span)[span_2](end_span).

## Overview
GridRescue AI provides a split-view experience for **Public / Citizen Users** and **Grid Operators**, backed by a **13-node City Grid Digital Twin** (`S1`, `T1`, `T2`, `HOSP`, `TEL`, `WAT`, `R1`–`R3`, `SOL`, `BESS`, `GEN`)[span_3](start_span)[span_3](end_span).

## Key Features
- **Public Portal & Citizen Dashboard:** Live substation summary, hospital emergency power status, solar/BESS reserves, and citizen outage reporting (`Report Power Failure`)[span_4](start_span)[span_4](end_span).
- **Operator Control Room (10 Modules):**
  1. Operations Dashboard[span_5](start_span)[span_5](end_span)
  2. Grid Digital Twin (Interactive Cytoscape.js network graph & node/line inspector)[span_6](start_span)[span_6](end_span)
  3. Grid Monitoring (Voltage/frequency & generation vs. load charts + sensor matrix)[span_7](start_span)[span_7](end_span)
  4. Critical Services Management (Hospital Tier-1 priority, Microgrid islanding, Telecom/Water/Transport protection)[span_8](start_span)[span_8](end_span)
  5. AI Agent Control Center (10-step autonomous rescue pipeline & retry tracking)[span_9](start_span)[span_9](end_span)
  6. GNN Network Intelligence (Cascading risk & alternative routing paths)[span_10](start_span)[span_10](end_span)
  7. RAG Knowledge Center (Emergency SOP retrieval)[span_11](start_span)[span_11](end_span)
  8. Optimization & Restoration (Priority-based load allocation)[span_12](start_span)[span_12](end_span)
  9. Safety & Verification (Simulation-only interlocks & post-recovery checks)[span_13](start_span)[span_13](end_span)
  10. Reports & Audit Logs (Chronological logs & CSV export)[span_14](start_span)[span_14](end_span)
- **Fault & Scenario Simulator (Scenarios A–G):** Test normal operation, Line L4 fault, transformer overload, hospital ICU surge, low BESS SOC, multi-fault crisis, and recovery replanning[span_15](start_span)[span_15](end_span).

## How to Run
1. Open `smart_power_grid_rescue_system.html` directly in any modern web browser (or open via **GitHub Pages**)[span_16](start_span)[span_16](end_span).
2. Switch between **Public Portal**, **Citizen Dashboard**, and **Operator Control Room** (use **Demo Operator Login** for quick evaluation access)[span_17](start_span)[span_17](end_span).

## Disclaimer
All switching, islanding, and restoration actions run strictly in a browser-based simulation environment for demonstration and evaluation purposes[span_18](start_span)[span_18](end_span).
