# Stroke Prediction Analysis - Jupyter Notebook Guide

This project contains a Jupyter notebook for analyzing healthcare data and building machine learning models to predict stroke risk based on various health indicators.

## 📁 Project Structure

```
├── predicao_avc.ipynb          # Main Jupyter notebook for stroke prediction analysis
├── healthcare-dataset-stroke-data.csv  # Healthcare dataset with stroke information
├── README.md                   # This guide
└── .venv/                      # Virtual environment directory
```

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Jupyter Notebook or JupyterLab

### Installation Steps

1. **Clone or download this repository**
   ```bash
   git clone <repository-url>
   cd 6iadt-tech-challenge-01-grupo-8
   ```

2. **Create and activate a virtual environment (recommended)**
   ```bash
   # Create virtual environment
   python -m venv .venv
   
   # Activate virtual environment
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install required dependencies**
   ```bash
   pip install scikit-learn matplotlib seaborn pandas imblearn plotly shap
   ```