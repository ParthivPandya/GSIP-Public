# 🌌 GSIP — Global Space Intelligence Platform

<div align="center">
  <a href="https://github.com/ParthivPandya/GSIP-Public/blob/master/GSIP-demo.webm?raw=true">
    <img src="thumbnail-play.png" width="100%" alt="Watch the GSIP Demo">
  </a>
</div>

---

## 🔒 Restricted Access Notice
**The source code for GSIP is proprietary and currently hosted in a private repository.** 

This repository serves as a public showcase of the platform's capabilities, architecture, and research-grade features. If you are interested in a full demonstration, technical collaboration, or licensing the software, please reach out directly:

*   **📧 Email**: [parthiv88@gmail.com](mailto:parthiv88@gmail.com)
*   **🔗 LinkedIn**: [linkedin.com/in/parthiv88](https://www.linkedin.com/in/parthiv88)

---

A production-grade, queue-less, high-performance Space Domain Awareness (SDA) platform. GSIP is designed for military, commercial, and scientific space organizations to ingest real telemetry and run advanced physics and ML models locally, without reliance on cloud processing.

### Architecture Stack
*   **Frontend**: Angular 17 + CesiumJS (Local OSM maps)
*   **API Gateway**: .NET 8 (C#) Proxy & Routing
*   **Compute Engine**: Python 3.11 (Flask, Scikit-Learn, NumPy)
*   **Database**: PostgreSQL 16
*   **Pattern**: Queue-less (Cron/APScheduler-driven DB updates)

---

## 🎯 Target Audience & Strategic Use Cases

GSIP is a multi-domain platform designed to serve diverse organizations across the space sector by providing offline, high-fidelity intelligence:

### 1. 🛡️ Military & Defense (Space Command, Intelligence Agencies)
*   **Space Domain Awareness (SDA)**: Uses the **Dark Fleet / RPO Detector** and **Satellite Intent Recognition Engine** to classify non-cooperative objects and identify enemy "inspector" satellites secretly shadowing critical assets.
*   **Threat Modeling & Wargaming**: The **ASAT Kinetic Kill Simulator** models the collateral damage of anti-satellite missile strikes. The **Game Theory Conflict Predictor** anticipates orbital escalation between nation-states, while the **Cross-Domain Impact Chain Simulator** computes the downstream economic/civilian consequences if GPS or communications constellations are destroyed.

### 2. 🛰️ Commercial Satellite Operators (Mega-Constellations, Telecoms)
*   **Asset Protection & Navigation**: The **Conjunction Assessment (COLA)** and **3D Uncertainty Ellipsoid Visualization** engines provide automated, high-precision warnings when space debris approaches multi-million dollar satellites, calculating the exact Delta-v needed for evasive maneuvers.
*   **Environment & Health Monitoring**: The **Solar RF Interference Heatmap** and **Lunar Shadow Thermal Simulator** predict exactly when solar flares will cause GPS/Ku-band signal dropouts or when satellites will suffer 100% solar power loss during eclipses. 

### 3. ⛏️ Asteroid Mining & Deep Space Startups
*   **Resource Prospecting**: The **Asteroid Mining Valuation Engine** evaluates incoming Near Earth Objects (NEOs) based on spectral class (C, S, M, X) to calculate precise Water, Platinum, and Nickel content, outputting a USD ($) Return on Investment against the required LEO intercept Delta-v.
*   **Deep Space Operations**: The **Cislunar Space Tracking** module continuously computes object proximities to Earth-Moon Lagrange Points (L1-L5) for tracking lunar assets and infrastructure.

### 4. 🔭 Academic Researchers & Observatories
*   **Orbital Dynamics Research**: Researchers can utilize the **Yarkovsky Drift Predictor** and **Full Orbital Digital Twin** (using Keplerian propagation with J2 perturbations) to study long-term orbital decay.
*   **Debris & Impact Science**: The **Kessler Cascade Simulator** (using the NASA Breakup Model) allows study of space debris chain reactions. The **Evacuation Zone Simulator** and **Kinetic Impactor Deflection Simulator** model asteroid impacts and planetary defense strategies (like the DART mission).
*   **Collaborative Open Science**: Integrates 100% free, global APIs (CelesTrak, SatNOGS) and provides **Federated Learning Across Observatories**, allowing universities to train ML models (like **Behavioral Fingerprinting**) on satellite maneuvers without sharing underlying proprietary tracking data.

---

## 🌟 Implemented Features

GSIP offers a comprehensive suite of advanced space intelligence tools.

### 🔬 Core Intelligence
1.  **NEO Tracking & Live Alerts**: Ingests real data from NASA NeoWs, NOAA, and Space-Track to track over 700+ space objects.
2.  **Free Global Satellite Tracking (CelesTrak)**: Pulls real-time active TLE orbital elements from CelesTrak's open API, updating altitude and velocity bands automatically.
3.  **SatNOGS Amateur Telemetry Integration**: Merges live satellite health, radio observations, and telemetry from the global open-source SatNOGS ground station network.
4.  **Kessler Cascade Simulator**: Implements the NASA Breakup Model to simulate long-term orbital decay and debris cascades.
5.  **Evacuation Zone Simulator**: Uses the Imperial College Earth Impact Effects model to calculate blast radii and affected civilian populations.
6.  **Cislunar Space Tracking**: Computes object proximities to Earth-Moon Lagrange Points (L1-L5) for tracking deep space lunar assets.
7.  **Behavioral Fingerprinting (ML)**: Uses an unsupervised `IsolationForest` machine learning model to categorize objects based on 6 orbital vectors.
8.  **Yarkovsky Drift Predictor**: Uses the Vokrouhlický 1998 thermal re-emission model to predict semi-major axis drift.
9.  **Crowd-sourced Observatory**: Validates amateur astronomical observations and generates MPC ADES XML formats.
10. **NLP Query Interface**: A hardcoded NLP-to-SQL fallback engine supporting 25+ intent mappings.

### ⚔️ Advanced Space Domain Awareness
11. **Asteroid Mining Valuation Engine**: Assesses NEOs based on their spectral class (C, S, M, X) to estimate resource content and USD ROI.
12. **Conjunction Assessment & COLA**: Predicts satellite-on-debris close approaches and provides actionable Delta-v evasive maneuver recommendations.
13. **Dark Fleet / RPO Detector**: Scans for "Inspector" satellites that are actively shadowing or trailing other assets.
14. **Atmospheric Re-entry Predictor**: Uses a ballistic drag proxy to predict burn-up dates and ground footprints.
15. **ASAT Kinetic Kill Simulator**: Simulates Anti-Satellite missile strikes and computes immediate debris cloud expansion.
16. **Solar RF Interference Heatmap**: Maps how solar weather impacts global ground-to-space communications.
17. **Lunar Shadow / Thermal Outage Simulator**: Predicts 100% solar power loss and thermal shock for cislunar orbiters.
18. **Automated LLM Threat Briefings**: Generates highly formatted daily intelligence summaries.

### 🔬 2025 Research-Grade Features — World Firsts (BSOA)
GSIP integrates "Beyond State-of-the-Art" research engines that move the platform from simple tracking to predictive Battlespace Management.

19. **OrbitGuard JEPA (Joint-Embedding Predictive Architecture)**: World-First mission intent engine that predicts maneuvers *before* they start by analyzing latent state-space variables and historical behavior profiles.
20. **QG-DOE (Quantum Gravitational "Dark-Object" Engine)**: Uses simulated cold-atom interferometry mass-signatures to detect "Dark Objects" (stealth satellites/debris) that are invisible to radar and optical sensors.
21. **H-pCP (Hypersonic pLEO Convergence Predictor)**: Specialized tracking engine for Hypersonic Glider Vehicles (HGVs). It fuses data from distributed pLEO constellations to predict Mach 10+ trajectories and convergence points.
22. **CL-IA (Cislunar Lagrange Intent Analyzer)**: Analyzes strategic behavior in the Earth-Moon Lagrange points (L1-L5) using CR3BP (Circular Restricted Three-Body Problem) stability and non-Keplerian divergence models.
23. **PP-FC (Privacy-Preserving Federated Catalog)**: Uses Differential Privacy (Laplacian Noise injection) to allow cross-observatory intelligence sharing without exposing raw sovereign tracking data or asset locations.
24. **Full Orbital Digital Twin**: Projects state 24hrs ahead using Keplerian propagation with J2 perturbation and atmospheric drag decay models.
25. **Neuromorphic Event Camera Simulation**: Software simulation of asynchronous brightness-change tracking with sub-pixel localization accuracy.
26. **Micro-Doppler Radar Characterization**: Extracts rotation period and shape classification from simulated radar signatures.
27. **Kinetic Impactor Deflection Simulator**: Physics engine simulating kinetic impactor strikes on NEOs (post-DART).
28. **3D Uncertainty Ellipsoid Visualization**: Computes covariance-based 3D probability ellipsoids for along-track/cross-track/radial uncertainty.
29. **Orbital Game Theory Conflict Predictor**: Models nation-state interactions as strategic games to predict escalation outcomes.
30. **Cross-Domain Impact Chain Simulator**: Simulates cascading real-world consequences (GPS → Aviation → Finance) when constellations are destroyed.

---

## 🇮🇳 Bharat-SDA Strategic Suite (ISRO 2025-2030)
GSIP includes a sovereign intelligence layer specifically designed for the **Indian Space Ecosystem**, aligning with the roadmap of **ISRO** and **IN-SPACe**.

1.  **Bharatiya Antariksha Station (BAS) Safe-Zone Monitor**: High-precision corridor tracking (400-450km) to protect India's future crewed modules from orbital debris.
2.  **NETRA-Grade Intentional Maneuver Predictor (IMP)**: AI-driven detection of foreign "Inspector" satellites shadowing critical Indian assets like **GSAT-7A**.
3.  **DFSM-2030 Compliance Engine**: Automated auditing for the **Debris-Free Space Mission** mandate, ensuring all Indian launches have perigee-lowering Delta-v margins.
4.  **Gaganyaan Crewed Safety Predictor**: Real-time abort scenario modeling and environmental gating for India's human spaceflight missions.
5.  **ISDC: Indigenous Signal De-Collision**: Advanced decoding of **ADS-B/AIS** telemetry for the Indian Ocean Region (IOR) using low-SNR optimized algorithms.

---

## 🌐 About Us

**GSIP (Global Space Intelligence Platform)** was born out of a mission to democratize research-grade Space Domain Awareness (SDA). We believe that high-fidelity orbital intelligence should be accessible to more than just a few world powers. 

Our platform is built by a distributed team of aerospace engineers, data scientists, and software architects dedicated to bridging the gap between academic orbital mechanics research and production-ready monitoring tools. GSIP is 100% cloud-independent, ensuring that critical space intelligence remains operational even in the most restricted or disconnected environments.

---

## ⚡ Architecture Philosophy: No Queue / No Cache
GSIP avoids heavy dependencies like Redis, RabbitMQ, or Kafka. It operates using:
- **Event tables** instead of queues.
- **Embedded APScheduler** for Python-driven background jobs that query external APIs (NASA, CelesTrak, SatNOGS).
- **Direct Python Compute Endpoints** for heavy physics, ML, and math operations, keeping the .NET gateway lightweight.
