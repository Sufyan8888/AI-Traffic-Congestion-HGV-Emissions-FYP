# AI-Traffic-Congestion-HGV-Emissions-FYP

**Final Year Project (COM6001)**  
**Muhammad Sufyan Zafar** – Student ID: 22504928  
**Buckinghamshire New University**

## Project Overview
Machine Learning-based forecasting of traffic congestion and quantification of Heavy Goods Vehicles (HGV) environmental impact using **555,880 records** from the UK Department for Transport (DfT) Annual Average Daily Flow (AADF) dataset (2000–2023).

**Key Findings:**
- HGVs represent only **4.11%** of traffic but contribute **28.1%** of road CO₂ emissions (7× disproportionate impact).
- XGBoost model achieved **R² = 0.5815** on corrected features (no data leakage).

## Live Dashboard
**[ View Interactive Dashboard](https://fyp-sufyan-zafar-traffic.netlify.app)**

## Repository Contents
- `notebooks/` → Exploratory Data Analysis & Model Training
- `src/` → Python scripts for preprocessing and modelling
- `data/` → Raw and processed datasets (if uploaded)
- `outputs/` → Charts and results
- Dashboard code (Gradio / Plotly)

## Technologies Used
- Python, Pandas, Scikit-learn, XGBoost
- Matplotlib, Seaborn, Kepler.gl
- Netlify (Dashboard deployment)

## How to Reproduce
```bash
git clone https://github.com/Sufyan8888/AI-Traffic-Congestion-HGV-Emissions-FYP.git
cd AI-Traffic-Congestion-HGV-Emissions-FYP
pip install -r requirements.txt
jupyter notebook
