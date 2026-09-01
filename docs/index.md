---
layout: default
title: AI Water-Aware Optimizer | Ranadeep Saha
---
# AI-Powered Water-Aware Workload & Cooling Optimizer

<div align="center">

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/unknown404-practice/water-aware-optimizer.svg)](https://github.com/unknown404-practice/water-aware-optimizer/stargazers)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ranadeep_Saha-blue?logo=linkedin)](https://www.linkedin.com/in/ranadeep-saha-a03296404)

**1st Place Competition Submission | Triple Optimization: Energy + Water + Carbon**

**By: Ranadeep Saha** | Member, Google Developer Group

[Results](#results) • [Quick Start](#quick-start) • [Project Structure](#project-structure) • [Contact](#contact)

</div>

---

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Results](#results)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

---

## Overview

This project builds an **AI-powered optimization system** that reduces energy, water, and carbon emissions in data centers by intelligently scheduling computational workloads based on:
- Real-time weather conditions (temperature, humidity)
- Predicted cooling demands
- Grid carbon intensity (CO2/kWh)
- Job priorities and deadlines (SLA)

### Our Solution
We combine **real production workload traces** (Alibaba) with **real weather data** (Open-Meteo) and **carbon intensity data** to train ML models that predict cooling demands, then use optimization algorithms to schedule workloads when cooling is most efficient and the grid is greenest.

---

## Key Features

- **Triple Optimization**: Energy + Water + Carbon simultaneously
- **Real-World Data**: Alibaba production traces + Open-Meteo weather
- **ML Models**: RandomForest predictors with measurable accuracy
- **Proactive Scheduling**: Uses weather forecasts to plan ahead
- **SLA Compliance**: 100% jobs finish on time
- **Professional Visualizations**: 7 high-quality charts

---

## Results

### Optimization Savings
| Metric | Savings |
|--------|---------|
| Energy | **10-25%** |
| Water | **10-25%** |
| Carbon | **15-30%** |

### SLA Compliance
- **100%** of jobs finish within deadline
- **0** SLA violations

---

## Quick Start

Copy the code block below to instantly install and run the project:

```bash
git clone https://github.com/unknown404-practice/water-aware-optimizer.git
cd water-aware-optimizer
pip install -r requirements.txt
jupyter notebook notebooks/00_workload_distributor_pipeline.ipynb
```

---

## Project Structure

```text
water-aware-optimizer/
├── notebooks/       # Jupyter notebooks (00 to 05)
├── data/            # Sample datasets for quick demo
├── outputs/         # Generated PNG visualizations
├── docs/            # GitHub Pages website files
├── README.md        # Main documentation
└── requirements.txt # Python dependencies
```

---

## Usage

Run the notebooks sequentially in your Jupyter environment:

1. `00_workload_distributor_pipeline.ipynb`
2. `01_workload_distributor_with_weather.ipynb`
3. `02_optimization_and_scheduling.ipynb`
4. `03_multi_job_scheduler.ipynb`
5. `04_realtime_weather_integration.ipynb`
6. `04b_carbon_aware_optimization.ipynb`
7. `05_visualization_dashboard.ipynb`

---

## Acknowledgments

- [Alibaba Cluster Trace v2018](https://github.com/alibaba/clusterdata)
- [Open-Meteo Weather API](https://open-meteo.com/)
- [UK Carbon Intensity API](https://api.carbonintensity.org.uk)

---

## Contact

**Project Lead:** Ranadeep Saha  
**Email:** ranadeep2021saha@gmail.com  
**GitHub:** [@unknown404-practice](https://github.com/unknown404-practice)  
**LinkedIn:** [Ranadeep Saha](https://www.linkedin.com/in/ranadeep-saha-a03296404)  
**Affiliation:** Member, Google Developer Group  
