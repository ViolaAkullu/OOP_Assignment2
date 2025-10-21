# Python Assignment: Data Analysis Using Functional Programming Techniques

This assignment demonstrates the application of Python functional programming concepts to analyze data across multiple domains. The tasks include electricity billing, market basket pricing, temperature tracking, school fee payments, agricultural yield estimation, and website status aggregation. Throughout this assignment, we utilized Python features such as `map()`, `filter()`, `zip()`, `zip_longest()`, lambda functions, list/dictionary comprehensions, *args, **kwargs, and generators.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Electricity Billing Optimization](#electricity-billing-optimization)  
3. [Market Basket Price Aggregator](#market-basket-price-aggregator)  
4. [District Temperature Tracker](#district-temperature-tracker)  
5. [School Fees Payment Analyzer](#school-fees-payment-analyzer)  
6. [Agricultural Yield Estimator](#agricultural-yield-estimator)  
7. [Web Data Aggregation](#web-data-aggregation)  

---

## Project Overview

This assignment focuses on analyzing structured data using Python’s functional programming capabilities. Each section represents a distinct question or task. The primary objective was to explore Python techniques such as:

- **`map()`** to transform data (e.g., computing bills, converting units, temperature conversions).  
- **`filter()`** to select data based on conditions (e.g., high consumption customers, hot months, students who cleared fees).  
- **`zip()` and `zip_longest()`** to pair related datasets (e.g., names and values, daily prices for multiple fruits).  
- **Lambda functions** for concise, on-the-fly operations (e.g., summing payments, averaging prices).  
- **List and dictionary comprehensions** for readable and efficient data construction.  
- **Generator expressions** to lazily evaluate sequences of interest (e.g., costly fruits, hot months, active websites).  
- **`*args` and `**kwargs`** for flexible function inputs, including computing averages and simulating revenue.  

The assignment demonstrates both data transformation and aggregation techniques, as well as formatting outputs for human readability.

---

## Assignment Questions Overview

### 1. Electricity Billing Optimization
Compute household electricity bills based on units consumed and connection type (Domestic or Commercial). Identify high-consumption customers and calculate average bills using `*args`.

### 2. Market Basket Price Aggregator
Combine daily fruit prices using `zip_longest()` to handle missing values, compute average prices, and identify fruits costing above the average using generator expressions.

### 3. District Temperature Tracker
Track monthly temperatures per district, pair months with readings using `zip()`, identify hot months with `filter()`, convert Celsius to Fahrenheit using `map()`, and use generators to yield months above a temperature threshold.

### 4. School Fees Payment Analyzer
Sum valid installment payments using lambda functions, compute total payments per student with `map()`, identify students who cleared full fees using `filter()`, and summarize payments using `**kwargs`.

### 5. Agricultural Yield Estimator
Convert yields from kilograms to tons with a list comprehension, identify high-yield districts using a generator, compute average yield with `*args`, simulate revenue per district with `**kwargs`, and format output for readability.

### 6. Web Data Aggregation
Fetch website status codes using `requests.get()`, filter reachable sites, store results in a dictionary comprehension, and generate active site messages using a generator expression.

---
