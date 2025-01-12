# Introduction

The goal of this analysis is to show an example of how python, pandas dataframes, and matplotlib can be used to collect, analyze, and visualize data that captures historical stock performance. To evaluate the stock performance, we use the popular Alpha and Beta metrics. 

# How To Run

This project consists of two notebooks: 
- dataset.ipynb: downloads historical stock data, computes Alpha and Beta values, and stores the calculated information in stock_dataset.csv 
- analysis.ipynb: reads the previously calculated data from stock_dataset.csv and performs an analysis and builds the graphs which are stored in the figures directory. 

To run this, you need a FRED API key. To get this key, follow the instructions on this page: https://fred.stlouisfed.org/docs/api/api_key.html. After getting the key, input it into the FRED_API_KEY environment variable. 
