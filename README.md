# AI Integrated Traffic Congestion and HGV Emission Forecasting

**Final Year Project (COM6001)**  
**Muhammad Sufyan Zafar** — Student ID: 22504928  
**Buckinghamshire New University**

---

## Project Overview

This project applies machine learning to forecast traffic congestion and quantify the environmental impact of Heavy Goods Vehicles (HGVs) using the UK Department for Transport’s **Annual Average Daily Flow (AADF)** dataset.

- **Dataset**: 555,880 records (2000–2023) across 11 UK regions
- **Key Insight**: HGVs represent **4.11%** of traffic but contribute **28.1%** of road CO₂ emissions (7× disproportionate impact)
- **Best Model**: XGBoost (R² = 0.5815)

---

## 🎯 Live Interactive Dashboard

**[🔗 Open Dashboard](https://fyp-sufyan-zafar-traffic.netlify.app)**

Features: Traffic Predictor • Regional Analysis • HGV Emission Calculator • Spatial Map • Chatbot

---

## Repository Structure

- `notebooks/` — Exploratory Data Analysis & Model Training
- `src/` — Python scripts for preprocessing and modelling
- `outputs/` — Charts and results
- `dashboard/` — Web dashboard code

---

## Technologies

**Python** • Pandas • Scikit-learn • XGBoost • Matplotlib • Seaborn • Plotly • Kepler.gl • Netlify

---

## Reproduce Locally

```bash
git clone https://github.com/Sufyan8888/AI-Traffic-Congestion-HGV-Emissions-FYP.git
cd AI-Traffic-Congestion-HGV-Emissions-FYP
pip install -r requirements.txt
jupyter notebook
