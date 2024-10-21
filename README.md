Smart Investment Advice - Part 1
This repository contains the initial part of the Smart Investment Advice project, which focuses on predicting future trends in the USD exchange rate and gold prices using time series analysis and machine learning models. The goal of this project is to provide insights into investment strategies based on historical financial data.

Data
The data used in this project includes:

Historical USD exchange rates.
Historical gold prices.
Both datasets cover the period from 2005 to 2024 and contain daily closing prices. These datasets are publicly available and have been preprocessed for the purpose of this project.

Data Structure
USD Exchange Rate Dataset:
Columns: Date, USD, EUR, GBP.
Gold Price Dataset:
Columns: Date, Gold Price (in grams).
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Kodu kopyala
git clone https://github.com/MehmetAliKOYLU/Smart-Investment-Advice-part1.git
cd Smart-Investment-Advice-part1
Install the required Python libraries using pip:

bash
Kodu kopyala
pip install -r requirements.txt
Ensure that you have Python 3.7+ installed.

Usage
Once the repository is set up, you can run the notebooks or scripts to train models and generate predictions.

Steps:
Data Exploration: Load and explore the financial data.
Model Training: Use different machine learning algorithms such as ARIMA, SARIMA, Random Forest, and LSTM to predict future trends in the exchange rate and gold price.
Visualization: Generate graphs and visualizations to understand the trends and predictions.
To execute a specific notebook, navigate to the notebooks folder and run it using Jupyter Notebook or JupyterLab:

bash
Kodu kopyala
jupyter notebook notebooks/SmartInvestment.ipynb
Example:
To plot the historical USD exchange rates:

python
Kodu kopyala
import pandas as pd
import matplotlib.pyplot as plt

# Load data
df = pd.read_csv('data/doviz_kuru.csv')

# Plot USD over time
plt.plot(df['Tarih'], df['USD'])
plt.title('USD Exchange Rate Over Time')
plt.xlabel('Date')
plt.ylabel('USD')
plt.show()
Models
In this project, we explore several machine learning and time series forecasting models:


Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.

### Contributors
- Yucel KANDAS- [Yucel KANDAS](https://github.com/Yucel00)
