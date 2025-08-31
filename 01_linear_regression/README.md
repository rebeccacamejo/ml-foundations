# 01 ‑ Linear Regression

This module introduces **linear regression**, one of the simplest yet most
powerful tools in a data scientist's arsenal.  I used the **diabetes**
dataset from scikit‑learn to predict a continuous outcome from a set of
features.  The notebook demonstrates how to prepare the data, fit a
`LinearRegression` model, evaluate it with metrics such as **Mean Squared
Error (MSE)** and **R²**, and visualise predicted vs. actual values.

In a business context, linear regression helps estimate outcomes like house
prices, insurance risk or customer spend.  By understanding the relationship
between features and the target variable, decision makers can forecast future
performance and allocate resources more efficiently.

## Industry applications

- **FinTech:** Forecast **credit line utilization** and **interest income** by regressing current spend, payment history, and macro‑economic factors. This helps lenders optimize risk exposure and capital allocation.  
- **SaaS:** Predict **monthly recurring revenue (MRR)** or **annual recurring revenue (ARR)** growth from pipeline and usage metrics. Accurate forecasts allow better budgeting and hiring decisions.  
- **Logistics:** Estimate **delivery time**, **fuel consumption**, or **shipment volumes** from route length, weather, and load size. Carriers can set customer expectations and plan capacity more efficiently.  
- **Construction/field services:** Predict **job duration** and **project cost** based on crew composition, materials, and past job features. This enables accurate quoting and reduces cost overruns.

## Future case study ideas

- **FinTech:** Model **delinquency risk** by regressing default likelihood against employment data, account age, and macro indicators. Show how a more accurate forecast reduces loss provisions.  
- **Logistics:** Predict **delivery ETA variance** from traffic patterns and driver productivity to refine customer notifications and reduce re‑delivery costs.  
- **Construction/field services:** Estimate **maintenance interval** for HVAC units or industrial equipment by regressing failure time on usage patterns and sensor readings to optimize preventive maintenance.
