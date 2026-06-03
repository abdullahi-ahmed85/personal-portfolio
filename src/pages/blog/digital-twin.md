\---

title: "Digital Twin Real-Time Input Parameter Calibration"

description: "Developing automated synchronization between live manufacturing lines and discrete event simulation engines using bootstrap particle filtering."

pubDate: 2025-10-15

\---



\### Institution: Politecnico di Milano

\*\*Position:\*\* Research Intern | \*\*Timeline:\*\* Jun 2025 - Oct 2025



\#### Executive Summary

This research addresses the challenge of fidelity loss in Discrete Event Simulation (DES) models due to shifting operational environments. We developed a robust Digital Twin framework capable of auto-calibrating physical asset behavior into simulated models in real time.



\#### Technical Implementations \& Architecture

\* \*\*Simulation Core:\*\* Designed complex operational models utilizing \*\*Arena Rockwell\*\*.

\* \*\*Data Layer Pipeline:\*\* Configured an asynchronous telemetry framework using \*\*MQTT protocols\*\* to capture live device events and pipe them into an \*\*InfluxDB time-series database\*\*.

\* \*\*Mathematical Calibration:\*\* Coded custom \*\*Python (Pandas, NumPy, SciPy)\*\* scripts integrating a \*\*Bootstrap Particle Filtering (BPF)\*\* algorithm. The filter dynamically tracks errors between live tracking metrics and baseline simulation data, adjusting core parameters automatically without stopping runtime engine frameworks.

\* \*\*Dashboard Visuals:\*\* Constructed a responsive telemetry interface using \*\*Flask\*\* to allow plant operators to track real-time parameter variations, OEE drift ratios, and synchronization accuracy indicators.



\*Note: This research methodology and resulting validation architecture have been co-authored and submitted to the \*\*CIRP CMS 2026\*\* conference.\*

