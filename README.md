# Monte Carlo Simulation for Pricing Options

This repository contains the codes for pricing European and American Options using Monte Carlo Simulations.

The 'utilities.py' file defines a function for simulating stock prices using Geometric Brownian Motion. It also defines the Least Square Monte Carlo method.

The *Jupyter Notebook* 'European-option.ipynb' uses the Black-Scholes solution to valuate an option (specifying parameters for 'call' or 'put') and simulates the stock path using the Geometric Brownian Motion from 'utilities.py'

The *Jupyter Notebook* 'American-option.ipynb' simulates the stock price using GBM and calculates the option premium using LSMC method.
