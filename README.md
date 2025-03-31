#  Workplace-Project: Forecasting the returns of a portfolio of 2 shares, taking into account their dependency structure

## 🐍 Description
Welcome to **Workplace Project** where statistical modeling meets portfolio risk forecasting. This project combines advanced analytical techniques, such as **ARIMA**, **GARCH**, and **Copula** models, to estimate portfolio metrics — **mean terminal value**, **standard deviation**, and **Value-at-Risk (VaR)** —for a portfolio consisting of two financial assets. By integrating these methods, we create a robust framework for assessing risk and managing investment strategies.
We take into consideration the inherent patterns in each share data time series as well as the dependence structure between the two. 

Prior to that data cleanup has been performed in excel.

## 📚 Table of Contents
- _Data Used_
- _Core Methodologies_
- _Practical Applications_
- _Project Goals_
- _Files_  
- _Recreating the Environment_
- _Contributing_
- _Contact Details_

## 🗞️ Data Used
The project uses historical price data for Nvidia (NVDA) and Apple (AAPL) to model trends, volatility, and dependencies. The data for each are combined to build the portfolio of interest.

## 🧠 Core Methodologies
1. ARIMA (AutoRegressive Integrated Moving Average):
  - Captures linear trends, patterns, and seasonality in the individual share time series data.
  - Forecasts future values based on historical data, enabling a deeper understanding of long-term asset behavior.

2. GARCH (Generalized Autoregressive Conditional Heteroskedasticity):
  - Models volatility clustering, which is common in financial markets, focusing on time-varying variance.
  - Provides crucial insights into the risk and uncertainty surrounding each asset.

3. Copula Models:
  - A powerful statistical tool for modeling dependency structures between the two shares.
  - Simulates the joint behavior of assets to assess portfolio dynamics and correlations.

Together, these methods provide a comprehensive approach to portfolio forecasting by addressing trend prediction, volatility modeling, and dependency estimation — elements that individual models cannot fully capture on their own. This synergy allows for a more robust and adaptable framework for risk and return analysis.

## 🔍 Practical Applications
This project applies these statistical models to Apple Inc. and Nvidia Corporation share data, exploring:
- Portfolio Mean Value: Average projected portfolio terminal value based on simulations.
- Standard Deviation: Measure of risk or variability in portfolio terminal values across simulations.
- Value-at-Risk (VaR): Worst-case loss expected at a specified confidence level (e.g., 95%).

## 🚀 Project Goals
- To enable risk forecasting for a portfolio under normal market conditions.
- To provide tools for optimal portfolio allocation, balancing risk and return through weighted simulations.
- To simulate scenarios and dependencies for robust financial decision-making.
  

## 📜 Files
This project consists of 5 files other than this Readme:  
- A python notebook containing the analysis (_Workplace_Project_v1.ipynb_)
- The data exported from the notebook for checks (_data.xlsx_)
- An excel workbook where the checks have been performed (_data-checks.xlsx_)
- A requirements file to reproduce the environment locally (_requirements.txt_)
- A presentation providing an overview of the project, results and conclusion in pptx and pdf formats (_Workplace_project presentation.pptx_ & _Workplace_project presentation.pdf_)
- A link to a Trello board which is used to manage the project flow and timelines as well as a screenshot of the Board (_Trello Board Link.txt_ & _Trello Screenshot.PNG_)

## ⚙️ Recreating the Environment
Reproduce the evironment in Python using:  
- Create a Virtual Environment:  
python -m venv myenv  
- Activate the Virtual Environment:  
myenv\Scripts\activate  
- Install Dependencies:  
pip install -r requirements.txt  
- Verify Installation:   
pip list  

Reproduce the evironment in Ananconda using:
- Create a New Environment:  
  conda create --name <env_name> --file requirements.txt  
- Activate the Environment:  
  conda activate myenv  
- Verify Installation:  
  conda list

## 🤝 Contributing
Guidelines for contributing to the project.
- Fork the repository
- Create a new branch (git checkout -b feature-branch)
- Commit your changes (git commit -m 'Add some feature')
- Push to the branch (git push origin feature-branch)
- Open a pull request


## 🔗 Contact Details
- Email: yaj457@gmail.com
- GitHub: yaj457

