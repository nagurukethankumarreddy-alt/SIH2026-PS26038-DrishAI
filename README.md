# Drish-AI: Explainable Retinal Diagnostic Engine

**Smart India Hackathon 2026**
**Problem Statement ID:** 26038
**Team Name:** RetinaX

## Technical Architecture
* **PHC Edge Tier (MATLAB):** Multi-metric IQA utilizing Tenengrad focus. 
* **Cloud Tier (Python):** `app.py` handles the API and diagnostic verification routing.
* **Digital Twin:** `rural_tele_triage.slx` schedules PHC nodes into the district hospital.

## Execution
1. Run `IQA_Tenengrad_Otsu.mlx` in MATLAB for edge-tier image assessment.
2. Execute `rural_tele_triage.slx` in Simulink for network simulation.
3. Run `pip install -r requirements.txt` and execute `app.py` for the cloud backend.
