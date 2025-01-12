# 🦠 COVID-19 Data Analysis Project

<div align="center">
  <img src="SARS-CoV-2_without_background.png" alt="COVID-19 Virus Structure" width="300"/>
</div>

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Data](https://img.shields.io/badge/Data-Kaggle-blue.svg)](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)


## 📊 Project Overview

This Jupyter Notebook provides comprehensive analysis of COVID-19 data, offering insights into global and regional trends, case counts, and correlations using various data science techniques.

### 🔍 Key Analysis Components

#### 📥 Data Acquisition and Preparation
- Downloads COVID-19 datasets from Kaggle
- Imports data into Pandas DataFrames
- Performs essential cleaning and handles missing values

#### 📈 Descriptive Statistics
- Calculates key metrics:
  - Mean and median of confirmed cases
  - Death rates
  - Recovery statistics

#### 🎨 Data Visualization

##### Core Visualizations
- 📈 **Line Plots**: Trend analysis of cases, deaths, and recoveries
- 📊 **Stacked Bar Charts**: Top 10 countries comparison
- 🗺️ **Interactive World Map**: Country-specific statistics
- 🌡️ **Correlation Heatmap**: Relationship analysis

##### Relationship Analysis
- 🔄 **Confirmed vs. Deaths**: Temporal correlation analysis
- ⚕️ **Confirmed vs. Recoveries**: Recovery rate insights

## 🛠️ Prerequisites

### Required Software
- Python 3.7+
- Jupyter Notebook

### 📚 Required Libraries
```bash
pip install pandas numpy seaborn matplotlib plotly matplotx geopandas kaggle folium
```

## ⚙️ Setup Instructions

1. **📂 Clone Repository**
   ```bash
   git clone https://github.com/AdityaAjithKumar/SIC_COVID-19_DATA_ANALYSIS
   ```

2. **📦 Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **🔑 Kaggle API Configuration**
   - Create `kaggle.json` with API credentials
   - Follow notebook instructions for setup

4. **▶️ Launch Notebook**
   ```bash
   jupyter notebook SamsungProject.ipynb
   ```

## 📊 Data Source
Dataset sourced from [Kaggle's Corona Virus Report](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

## 📓 Notebook Structure
The analysis follows a logical progression:
1. Data Import & Cleaning
2. Exploratory Analysis
3. Visualization
4. Insights Generation

## 🚀 Future Development

### Potential Enhancements
- 🤖 Machine Learning forecasting models
- 📊 Advanced visualization techniques
- 🌍 Regional demographic analysis
- 📱 Interactive dashboard development

## 📫 Contributing
Contributions welcome! Please read our contributing guidelines and submit pull requests.
