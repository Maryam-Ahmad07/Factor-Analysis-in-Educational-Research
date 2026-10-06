# Factor Analysis in Educational Research

An advanced analytical web application and backend pipeline designed to perform and visualize Factor Analysis on educational survey datasets.

---

## 🚀 Overview

This Final Year Project (FYP) implements an end-to-end data processing and analysis pipeline focused on **Factor Analysis in Educational Research**. The system features a robust Python/FastAPI backend that executes data cleaning and statistical factor pipelines, paired with an interactive frontend interface built for running diagnostics, viewing analytical models, and exploring survey insights.

---

## 📁 Repository Structure

```text
Factor_Analysis_in_Educational_Research/
│
├── backend/                  # Backend server, API endpoints, and data pipelines
│   ├── api.py                # FastAPI server application endpoints
│   └── run_factor_pipeline.py# Core script executing the factor analysis workflow
│
├── data/                     # Dataset storage directory
│   ├── raw/                  # Original datasets (e.g., educational survey data)
│   └── processed/            # Cleaned data and computed factor scores[cite: 1]
│
├── frontend/                 # Web-based user interface[cite: 1]
│   ├── index.html            # Main dashboard entry point[cite: 1]
│   ├── analysis.html         # Factor analysis configuration and results view[cite: 1]
│   ├── diagnostics.html      # Statistical diagnostics view[cite: 1]
│   ├── project.html          # Project overview documentation view[cite: 1]
│   ├── manual-demo.html      # Interactive demo page[cite: 1]
│   ├── css/                  # Styling sheets (styles.css)[cite: 1]
│   ├── js/                   # Frontend client application logic (app.js)[cite: 1]
│   └── vendor/               # Third-party libraries (Plotly.js for visualizations)[cite: 1]
│
└── docs/                     # Project documentation and briefings[cite: 1]
