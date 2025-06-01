# End-to-End Portfolio Construction
	
End-to-end portfolio optimization systems leverage a fully data-driven pipeline to improve investment decision-making. These systems learn to forecast expected returns in a way that directly supports portfolio allocation, integrating predictive modeling and optimization into a unified process. Rather than treating forecasting and optimization separately, the model learns what matters most for downstream performance.

Key features of the approach include:

- Flexibility in defining portfolio objectives, allowing alignment with different investment mandates.

- Data-driven calibration of risk preferences to better reflect market conditions.

- Can be tailored to the uncertainty in the distribution of mean returns, thus providing robustness against model missepcification.

- Built-in backtesting workflows that assess how portfolio decisions perform under real-world market dynamics.

- Substantial performance gains over traditional approaches, including significantly higher Sharpe ratios compared to standard predict-then-optimize methods.

This framework exemplifies modern quantitative investing—where machine learning and optimization are tightly coupled to drive better portfolio outcomes.

This repository contains a Jupyter notebook that illustrates my extension of the models and code for the paper "Distributionally Robust Portfolio Construction", [Journal of Financial Econometrics, 2023](https://www.tandfonline.com/doi/full/10.1080/14697688.2023.2236148).

### 🛠 Tools & Technologies

#### 🖥️ Language  
![Julia](https://img.shields.io/badge/Julia-9558B2?logo=julia&logoColor=white)

#### ⚙️ Optimization Solvers  
![JuMP](https://img.shields.io/badge/JuMP-00BFFF?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyBmaWxsPSIjMDAwMDAwIiBoZWlnaHQ9IjEwMCIgd2lkdGg9IjEwMCIgdmlld0JveD0iMCAwIDEwMCAxMDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPC9zdmc%2B&label=JuMP)  
![HiGHS](https://img.shields.io/badge/HiGHS-0066CC?logo=gnu&logoColor=white)  
![Gurobi](https://img.shields.io/badge/Gurobi-EE1C25?logo=gurobi&logoColor=white)

#### 🎲 Simulation Techniques  
![Monte Carlo](https://img.shields.io/badge/Monte%20Carlo%20Simulations-FFD700?style=flat)

## Purpose

**This repository is intended solely for the illustration of extended models and code associated with the above-mentioned paper.**  
It is not intended for production or commercial use.

## License

The contents of this repository are made available for illustrative and academic purposes only.  
Unless otherwise stated, you may use, modify, and share the code and materials herein for non-commercial, educational, or research purposes, provided that proper attribution is given to the original paper and codebase:

- Paper: "Distributionally Robust Portfolio Construction"
- Original codebase: [Iyengar-Lab/E2E-DRO](https://github.com/Iyengar-Lab/E2E-DRO)

No warranty is provided, and use of the materials is at your own risk.

## Acknowledgements

- Original paper: "Distributionally Robust Portfolio Construction"
- Original codebase: [Iyengar-Lab/E2E-DRO](https://github.com/Iyengar-Lab/E2E-DRO)
