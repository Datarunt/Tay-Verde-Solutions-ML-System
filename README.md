## ML System: System context

This repository is part of a larger **reliability-first industrial IoT system**.
The system is intentionally split into four focused, frozen repositories.

**Explore the full system:**
1. [Edge-reliability](https://github.com/Datarunt/Tay-Verde-Solutions-Edge-Reliability)
2. [Data-ingestion](https://github.com/Datarunt/Tay-Verde-Solutions-Data-Ingestion)
3. [Control-plane](https://github.com/yourusername/risk-control-plane-airflow)
4. [ML-system](https://github.com/Datarunt/Tay-Verde-Solutions-ML-System)

You are currently viewing: **<Edge-Reliability>**

Purpose: prove ML is bounded, calibrated, and safely reversible

ML is optional; system defaults to rules under uncertainty

- How to reproduce training + evaluation
- Where calibration plots are
- How abstention works
- How fallback works
- What triggers rollback

Deliverables

- Label logic (two labels)
- Time-based splits dataset builder
- Logistic baseline vs rules metrics
- Tree model comparison
- Calibration plots
- Abstention (“no-predict”) zones
- Drift detection on features + predictions
- Automatic fallback to rules
- Simulated bad data → safe degradation
- Lifecycle + rollback doc
