# Financial Planning Tools

This prototype application financial planning tool was created to help credit union members evaluate their financial health in both their cryptocurrency holdings and their stock/bonds. It allows the user to assess their monthly budgets and forecast a reasonably effective retirement plan based on their current holdings using the Monte Carlo simulation. 

---

## Required Modules/Libraries

Requests (v.2.24.0) - helps you pull and access data from API

JSON (v.0.13.1) - takes the data from API and puts it into a readable format

Alpaca SDK (v.0.50.0) - let's us interact with the Alpaca API (ensure that it is version 0.50.0 -- newer versions no longer use get_barset)

Python Dotenv (v.0.14.0) - let's us read key-value paris from an environment file (.env) and add them as envrionment variables

---

## Datasets

Alpaca API - to pull cryptocurrency data, as well as stock/bond data this application makes an Alpaca API call via the Alpaca SDK to get historical pricing data

Alpaca API account needed with API Key and Secret Key stored as an environment variable in OS

---

## Financial Analysis Tools

1) Emergencies - Members will have the ability to visualize their current savings and determine if they have enough reserves for an emergency fund based on their holdings.

2) Retirement - Members will have the ability to forecast their performance in their retirement portfolio in 30 years and provides a snapshot of where they would be in 10 years if they decided to incrase their stocks/bonds vs cryptocurrencies using the Monte Carlo Simulation.

---