# ETL-Flight-Analytics-GCP

## Problem Statement:
The project aimed to predict flight velocity and delays using real-time and historical data from the Bureau of Transportation Statistics website.

## Objective:
Develop a predictive model to estimate flight velocity and accurately predict flight delays, leveraging both real-time and historical data.

## Data Sources:
Bureau of Transportation Statistics website for historical data, OpenSky for streaming data.

## ETL:
Utilized GCP to load the data into Cloud Storage before finally moving it into BigQuery.

## Analysis and Modeling:
Conducted analysis and modeling in BigQuery datawarehouse.
Utilized logistic regression to predict flight delays (91% accuracy) based on various factors.
Employed linear regression to predict flight velocity (86% accuracy) using relevant attributes.

## Visualization and Reporting:
Developed a Looker dashboard to present the results for each case.

## Business Impact:
Accurate prediction of flight delays and velocities is crucial for optimizing airline performance. It directly impacts factors like fuel consumption and emissions, ensuring flights operate within optimal parameters to enhance operational efficiency and passenger satisfaction.
