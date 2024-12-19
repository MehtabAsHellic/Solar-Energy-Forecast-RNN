# Solar Energy Surplus Forecasting Project

## Overview
This project focuses on forecasting solar energy surplus using advanced RNN-based machine learning techniques. It provides 36-hour-ahead predictions for surplus energy to help optimize energy distribution in pilot programs like the one in Colchester. The forecast aims to identify surplus periods, enabling energy providers to offer surplus energy for free, improving energy efficiency and promoting sustainable usage.

---

## Project Features
- **Data Exploration**: Includes exploratory data analysis and visualization.
- **Time Series Forecasting**: Implements an RNN model tailored for energy forecasting tasks.
- **Insights and Evaluation**: Generates detailed visualizations and key performance indicators to evaluate the model's accuracy.
- **Deployable Models**: Includes saved forecasting models for easy reuse.

---

## Folder Structure
- **data/**:
  - `raw/`: Contains the original dataset files.
  - `processed/`: Cleaned and pre-processed data files (e.g., `processed_data.csv`).
- **notebooks/**:
  - `1_data_exploration_preprocessing.ipynb`: Notebook for EDA and preprocessing.
  - `2_modeling_analysis.ipynb`: Notebook for building, training, and analyzing the model.
- **results/**:
  - **figures/**:
    - Graphs showcasing:
      - `actual_vs_predicted.png`
      - `correlation_heatmap.png`
      - `time_series_plots.png`
      - `training_history.png`
  - **models/**: Includes the serialized model files, such as `solar_energy_forecast_model.h5`.
- **venv/**: Python virtual environment.
- `README.md`: Overview of the project.
- `requirements.txt`: Required Python libraries and versions.

---

## Installation and Usage Instructions

## 1. Create a Virtual Environment
On Windows:

   python -m venv venv

On macOS:

   python3 -m venv venv

**Activate the Virtual Environment**
On Windows:

   venv\Scripts\activate
On macOS:

   source venv/bin/activate

You will see (venv) before your terminal prompt if the environment is activated.

## 2. Install Required Libraries

Run the following command in your terminal:
   pip install -r requirements.txt

Manually Installing Each Dependency
If you prefer to install dependencies manually:

   pip install numpy
   pip install pandas
   pip install matplotlib
   pip install seaborn
   pip install tensorflow
   pip install scikit-learn
   pip install jupyter

