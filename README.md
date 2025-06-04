# 🤖 End-to-End Portfolio Construction

This project implements an end-to-end portfolio optimization system that integrates **predictive modeling** and **portfolio allocation** into a unified, data-driven pipeline. Unlike traditional workflows that separate forecasting from optimization, this framework learns return forecasts that are explicitly optimized for downstream investment performance.

It reflects a modern approach to quantitative investing, where **machine learning and optimization are tightly coupled** to improve portfolio outcomes under uncertainty.

---

## 🌟 Key Features

- **Unified objective**: Simultaneously learns to forecast and optimize for portfolio performance.
- **Flexible portfolio definitions**: Adapts to a wide range of investment mandates and risk objectives.
- **Robustness to model misspecification**: Incorporates returns ditributional misspecification using distributionally robust techniques.
- **Backtesting support**: Includes workflows to evaluate out-of-sample performance across real-world market conditions.
- **Superior risk-adjusted returns**: Demonstrates higher Sharpe ratios compared to standard predict-then-optimize approaches.

This repository builds upon and extends the models and code presented in  
📝 *"Distributionally Robust Portfolio Construction"*, [Journal of Financial Econometrics, 2023](https://www.tandfonline.com/doi/full/10.1080/14697688.2023.2236148).

---

## 📁 Repository Contents

`notebooks/`: Includes the Jupyter notebook demonstrating the end-to-end learning framework with extended model components.

---

## 🐍 Python Stack

### 🖥️ Language  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

### 📦 Data Acquisition  
![yfinance](https://img.shields.io/badge/yfinance-003B71?logo=yahoo&logoColor=white)

### 📊 Data Analysis & Handling  
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)

### 🔍 Optimization & Modeling  
![CVXPY](https://img.shields.io/badge/CVXPY-34495E?logo=python&logoColor=white)  
![cvxpylayers](https://img.shields.io/badge/CVXPYLayers-2C3E50?logo=python&logoColor=white)

### 🤖 Deep Learning  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

---

## 🎯 Purpose

This repository is intended solely to illustrate extended models and code associated with the aforementioned paper.  
It is meant for academic and educational purposes and is **not intended for production or commercial deployment**.

---

## 📄 License

This project is released under an **academic-use license**.  
You are free to use, modify, and share the code for **non-commercial research or educational purposes**, provided that attribution is given to:

- **Paper**: *"Distributionally Robust End-to-End Portfolio Construction"*
- **Original codebase**: [Iyengar-Lab/E2E-DRO](https://github.com/Iyengar-Lab/E2E-DRO)

No warranty is provided. Use at your own discretion and risk.

---

## 🙏 Acknowledgements

- **Original paper**: *"Distributionally Robust Portfolio Construction"*
- **Source code**: [Iyengar-Lab/E2E-DRO](https://github.com/Iyengar-Lab/E2E-DRO)
