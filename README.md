# 🌦 Real World Data Visualization — Colombian Climate Analysis

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg?style=for-the-badge&logo=python)]
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)]
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)]
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-green?style=for-the-badge)]
[![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)]

---

## 📌 Project Overview

This project performs an in-depth **climate data analysis of Colombia (1824–2013)** using real-world historical temperature data from the Berkeley Earth dataset.

The goal is to identify:

- Long-term warming trends  
- Seasonal temperature behavior  
- Structural distribution shifts over time  

The analysis combines statistical processing, visualization techniques, and interpretative storytelling to extract meaningful climate insights.

---

## 🏗 Analysis Workflow

Raw Dataset  
↓  
Data Cleaning  
↓  
Filtering (Colombia)  
↓  
Feature Engineering (Year, Month, Decade)  
↓  
Statistical Aggregation  
↓  
Visualization  
↓  
Climate Interpretation  

---

## 🧠 Core Components

### 1️⃣ Data Preparation

- Load CSV dataset
- Filter Colombia records
- Convert dates to datetime
- Extract year, month, and decade
- Remove missing temperature values

### 2️⃣ Trend Analysis

- Compute yearly average temperature
- Apply linear regression
- Estimate warming rate

### 3️⃣ Visualizations

The project includes three main visual studies:

#### 📈 Long-Term Trend
Yearly average temperature evolution with regression trendline.

#### 🔥 Monthly Heatmap
Seasonal patterns combined with long-term warming behavior.

#### 📊 Decadal Distribution
Boxplot comparison showing structural temperature shifts across decades.

#### 🌍 Colombia vs Global Temperature Comparison
To contextualize national climate behavior, we compared Colombia’s historical temperature trend with the global average temperature from the same dataset.
---

## 🚀 Getting Started

### 📦 Prerequisites

- Python 3.11
- pip

---

## ⚙️ Installation

```bash
git clone https://github.com/JeissonS02/real-data-visualization.git
cd real-data-visualization
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

---

## ▶️ Running the Analysis

Open the Jupyter notebook:

```bash
jupyter notebook notebooks/colombian_weather_analysis.ipynb
```

Run all cells to reproduce the analysis.

---

## 📁 Project Structure

```
├── data/
│   └── GlobalLandTemperaturesByCountry.csv
├── notebooks/
│   └── colombian_weather_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## 📈 Key Findings

- Clear upward temperature trend after 1970  
- Accelerated warming post-1990  
- Structural distribution shift across decades  
- Consistent warming across most months of the year  

The findings align with global climate change patterns and demonstrate sustained warming effects in Colombia over nearly two centuries.

---

## 📚 Dataset Source

Berkeley Earth — Global Land Temperatures Dataset  
(Available on Kaggle)

---

## 👨‍💻 Author

[![GitHub](https://img.shields.io/badge/GitHub-JeissonS02-181717?style=for-the-badge&logo=github)](https://github.com/JeissonS02)
[![GitHub](https://img.shields.io/badge/GitHub-SebastianAlbarracinSilva-181717?style=for-the-badge&logo=github)](https://github.com/SebastianAlbarracinSilva)