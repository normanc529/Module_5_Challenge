# Module_5_Challenge

This file is for Financial planning with APIs and Simulations
It does not accurately represent what will happen if you invest X amount for Y time
but can serve as a guideline or estimate for how to invest money based on MonteCarlo Simulations


libraries and dependencies used are:

import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi

from MCForecastTools import MCSimulation
    this tool is created specifically to run the Monte Carlo Simulation for portfolio price data

%matplotlib inline

Part 1: 

Evaluating current portfolio investments of User
    takes into account all types of investments such as crypto, stocks, bonds
        stocks and bonds are based on the alpaca API SDK
    
Evaluating the Funds and visualization of crypto to stock/bond ratio of investment

Part 2: 

Creating a Planner with Simulations

makes an API call to the Alpaca SDK to get 'X' amount of data for a split weighing on stocks to bonds
    Compares the differences between different weights 
    Compares the differences between different amounts of time used for investments
    
Ploting the simulations to visualize likelihood of returns on investments