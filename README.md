# 🏠 US Housing Dashboard

An interactive Streamlit application to explore residential property data in the Seattle area.

## 📌 Overview

This tool allows users to:

- Navigate and understand a dataset of 4,000+ housing records
- Visualize property features across cities
- Interactively filter listings based on price, size, bedrooms, and more

Built using **Streamlit**, the app features a clean, storytelling-style introduction and a dedicated dashboard interface.

---

## 🗂️ Features

- Storytelling landing page with introduction and objectives
- Dynamic dashboard:
  - Filter properties by key attributes
  - Visualize average prices by city on a map
  - Explore distributions and correlations
- Modular and scalable codebase
- Ready for deployment (locally or on the cloud)

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.8+
- Install dependencies:

```bash
pip install -r requirements.txt
```
▶️ Run the App
```bash
streamlit run app.py
```
The dashboard will be accessible at http://localhost:8501

📁 Project Structure
```bash
us-housing-dashboard/
├── Home.py                  # Landing page (storytelling + objectives)
├── pages/
│   └── Dashboard.py      # Main dashboard
├── data/
│   └── housing.csv         # Raw dataset
├── models/                 # (optional) Trained models or scripts
├── utils/                  # Helper functions and pipelines
├── requirements.txt
└── README.md
```
📊 Data Description

The dataset includes the following features:

    Price (target): Sale price in USD

    Bedrooms / Bathrooms

    Sqft Living / Lot

    Floors, Waterfront, View, Condition

    Construction & Renovation Dates

    City, Statezip

📌 Notes

    The app currently does not include prediction models.

    All insights are based on exploratory data analysis and interactive visualizations.
