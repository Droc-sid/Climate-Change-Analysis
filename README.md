# Climate-Change-Analysis
Quantiative Time Series Analysis And Stochastic Modeling of Climate Change Effects in Selected Kenyan Counties.


# Overview 
<p>
This capstone project explores the effects of climate change across four counties in Kenya.
</p>

<ol>
 <li>Nairobi</li> 
<li>Kajiado</li>
<li>Machakos</li>
<li>Makueni</li>
</ol>

<p>
Using the Quantitative methods Time Series Forecasting and Machine Learning Models.
</p>

<p> 
The aim is to forecast future climate conditions and intergrate coursework from multiple academic units.
</p>


## Objectives

<ul>
  <li>Analyze historical and current climate data</li>
  <li>Model climate variables using stochastic process and time series forecasting</li>
  <li>Build a machine learning model to prediict climate indicators with over 85% accurracy</li> 
  <li>Apply Operations Research to optimize resource allocation</li> 
  <li>Use a NoSQL database (MongDB) for data management</li>
  <li>Intergrate basic information systems audit techniques for data integrity and traceability</li>
</ul>

## Units Covered

<ul>
  <li>Research Methodology</li>
  <li>Test of hypothesis</li>
  <li>Machine learning</li>
  <li>Stochastic process</li>
  <li>Time series</li>
  <li>Operation Research</li>
  <li>NoSQL Database</li>
  <li>Information Systems Forensics and Audit</li>
</ul>

## Data sources

<p>
Kenya: Rainfall Indicators at Subnational Level

This dataset contains dekadal rainfall indicators computed from Climate Hazards Group InfraRed Precipitation satellite imagery with insitu Station data (CHIRPS) version 2, aggregated by subnational administrative units.

Included indicators are (for each dekad):
<ul>
   <li> 10 day rainfall [mm] (rfh)</li>
   <li> rainfall 1-month rolling aggregation [mm] (r1h)</li>
   <li> rainfall 3-month rolling aggregation [mm] (r3h)</li>
   <li> rainfall long term average [mm] (rfh_avg)</li>
   <li> rainfall 1-month rolling aggregation long term average [mm] (r1h_avg)</li>
   <li> rainfall 3-month rolling aggregation long term average [mm] (r3h_avg)</li>
   <li> rainfall anomaly [%] (rfq)</li>
   <li> rainfall 1-month anomaly [%] (r1q)</li>
   <li> rainfall 3-month anomaly [%] (r3q)</li>
 </ul>
 
The administrative units used for aggregation are based on WFP data and contain a Pcode reference attributed to each unit. The number of input pixels used to create the aggregates, is provided in the n_pixelscolumn.</p>

https://data.humdata.org/dataset/ken-rainfall-subnational


## Technologies

 <ul>
  <li>Python, Jupyter</li>
  <li>Libraries: pandas, numpy, sklearn, statsmodels, scipy, seaborn, matplotlib, pymongo</li>
  <li>MongoDB for NoSQL storage</li>
  <li>Linear programming (scipy.optimize)</li>
  <li>Hashlib and logging for audit</li>
 </ul>

## Results

<ul>
 <li>Forecasting achieved **R² > 0.85** using Random Forest Regressor.</li>
 <li>Simulated random walk models and time series analysis indicate increasing variability in climate patterns.</li>
 <li>Hypothesis tests confirmed significant differences in key climate variables across counties.</li>
 <li>Budget optimization model provides a cost-efficient resource distribution plan.</li>
</ul>

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Droc-sid/climate-change-kenya.git
   cd climate-change-kenya

## Technologies

 <ul>
  <li>Python, Jupyter</li>
  <li>Libraries: pandas, numpy, sklearn, statsmodels, scipy, seaborn, matplotlib, pymongo</li>
  <li>MongoDB for NoSQL storage</li>
  <li>Linear programming (scipy.optimize)</li>
  <li>Hashlib and logging for audit</li>
 </ul>

## Results

<ul>
 <li>Forecasting achieved **R² > 0.85** using Random Forest Regressor.</li>
 <li>Simulated random walk models and time series analysis indicate increasing variability in climate patterns.</li>
 <li>Hypothesis tests confirmed significant differences in key climate variables across counties.</li>
 <li>Budget optimization model provides a cost-efficient resource distribution plan.</li>
</ul>

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Droc-sid/climate-change-kenya.git
   cd climate-change-kenya


