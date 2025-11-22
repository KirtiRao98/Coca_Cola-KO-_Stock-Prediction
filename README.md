# Overview

This project is my end-to-end analysis of Coca-Cola (KO) stock.
I worked with real historical stock data (the files included here) to:

understand KO’s price movements

explore trends and patterns

engineer useful financial features

train simple machine-learning models

test basic trading strategies

Everything is written clearly so anyone learning data analysis or finance can follow along.

📂 What’s Inside

Main notebook:

coca-cola_stock.ipynb — the full walkthrough (EDA → indicators → ML → backtesting)

Data (uploaded):

Coca-Cola_stock_history.csv

Coca-Cola_stock_info.csv

Folders to organize the project (optional but recommended):

data/
  raw/          # original CSVs
  processed/    # cleaned data
notebooks/
src/


This keeps the project tidy and easy to extend.

🔍 What the Project Does
✔ Exploratory Data Analysis

Price trends

Volume changes

Daily returns

Volatility

Moving averages

✔ Feature Engineering

SMA / EMA

RSI

MACD

Volatility

Lag features

Daily returns

✔ Machine Learning

A simple model (Random Forest) to predict the next day’s closing price.

✔ Backtesting

Tests a couple of trading ideas like SMA crossovers to see if they would have worked in real life.

🚀 How to Use
1. Install dependencies
pip install -r requirements.txt

2. Open the notebook
jupyter notebook


Run:
notebooks/coca-cola_stock.ipynb

📘 Dataset

The data used is included in the repository.
Both CSVs contain the historical daily prices and additional stock info.

🎯 Purpose

I built this project to practice:

data cleaning

feature engineering

market analysis

ML model building

creating clear and reusable workflows

It’s a great starter project for anyone interested in stocks or data science.

📜 License

MIT — feel free to learn from it or build on top of it.
