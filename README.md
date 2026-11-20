# Balochistan Smart Highway & Weather Intelligence System

A tactical government command-and-control dashboard for real-time highway weather monitoring, corridor risk visualization, multilingual driver alerts (Urdu, Pashto, Balochi), and QR checkpoint verification across Balochistan.

## Key Modules
1. **Command Dashboard**: Dark navy & teal government operations center featuring live Balochistan highway map overlays, circular meteorological gauges (Wind, Rainfall, Pressure, Humidity, Road Risk), hourly forecast trends, and active route notifications.
2. **Highway Live Map**: Interactive Leaflet map covering N-50 (Quetta–Zhob), N-25 (Quetta–Karachi), N-65 (Quetta–Sibi), N-25N (Quetta–Chaman), N-40 (Quetta–Nushki–Taftan), and N-70 (Quetta–Loralai) with a 1–10 Road Danger Index.
3. **Driver Management & QR**: Fleet registration with automatic Digital Checkpoint QR Pass generation and gate scan simulation.
4. **Multilingual Alert Center**: Automated alert drafting in **Urdu**, **Pashto**, and **Balochi** with browser voice-call audio preview and travel guidance.
5. **Road Clearance Control**: Official highway segment closure/reopening verification and risk index management.

## Run Instructions
```bash
pip install -r requirements.txt
streamlit run app.py
```
