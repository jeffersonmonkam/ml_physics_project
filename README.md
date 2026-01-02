# ML-assisted Modeling of Physical Systems

[![Python Version](https://img.shields.io/badge/python-3.12+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)


---

## 🎯 Project Goal
This project aims to:

- Simulate different **physical systems**:
  - Brownian Motion
  - Harmonic Oscillator
  - Pendulum
- Train **ML models** to predict the behavior of these systems
- Verify **physical coherence** using `formal_reasoning.py`
- Visualize **trajectories, prediction errors, and scores**
- Provide an **Azure ML pipeline** ready for training and cloud deployment

---

## 📂 Project Structure

```text
ml_physics_project/
│
├── src/                 # Main Python scripts
│   ├── simulation.py
│   ├── preprocessing.py
│   ├── train_model.py
│   ├── validate_model.py
│   ├── formal_reasoning.py
│   └── visualization.py
│
├── data/
│   ├── raw/             # Simulated datasets
│   │   ├── brownian_motion.csv
│   │   ├── harmonic_oscillator.csv
│   │   └── pendulum.csv
│   └── processed/       # Transformed datasets + JSON reports
│       ├── brownian_report.json
│       ├── harmonic_report.json
│       └── pendulum_report.json
│
├── models/              # Trained ML models (.joblib)
├── notebooks/           # Exploration & testing notebooks
├── dashboard/           # Interactive Plotly Dash app
├── azure_pipeline/      # Azure ML setup & pipelines
├── tests/               # Unit tests
├── requirements.txt     # Python dependencies
├── environment.yml      # Conda environment
└── README.md            # Full documentation

