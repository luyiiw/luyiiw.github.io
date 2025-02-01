---
title: "Citi Bike Re-Balancer"
date: 2023-11-17 00:00:01 +/-TTTT
categories: [Projects]
tags: [R, Machine Learning, Data Engineering]
image: assets/thumbnails/bikeshare_predictions.png
alt: "Bikeshare Predictions"
---

## Project Description
Bike share programs have been growing in dense and populous cities in the US, like New York City, New Jersey City, and Philadelphia. For bike share programs to maximize ridership, it is important to ensure that bikes are where the riders are at the right times. For this project, I explore how to predict where and when riders are in New York City. For this project, I used Citi Bike data. This project shows how I trained a predictive model using temporal, spatial, and other features. 

### Project Details
**Project Type**: Individual

**Contributers**: Lu Yii Wong

**Skills**: R, Machine Learning, Geospatial Analysis, Data Analysis, Data Wrangling, Communication

## Introduction
Citi Bike is a bikeshare program that allows users to rent bikes across all boroughs of New York City, Jersey City, and Hoboken. How it works is that Citi Bike users can unlock a bike at any Citi Bike station through the Citi Bike app, ride it anywhere in the city, and return the bike by parking it at an available docking station.

Bikeshare programs like this have revolutionized the way people can get around the city. A major challenge that these programs face is “re-balancing”, which is ensuring that there are bikes where the demand is. Programs like Citi Bike can only be successful if they anticipate where demand for bikes are to ensure that users can ride whenever and wherever they are.

## Use Case
To address this issue, I attempt to build a predictive model using demand for bikes in Manhattan to show how we can use time-space predictive modeling to address an operations issue. With this information, Citi Bike can anticipate the time and location of high bike demand across the borough and move bikes to these locations at the appropriate times.

For this project, I focused on Manhattan Citi Bike demand. Manhattan is currently the most heavily trafficked Citi bike locations. To improve the current distribution of bikes in the city, I feel that using an example with the robust data set will allow us to come up with the strongest predictive model that can later be applied to other boroughs and areas which Citi bike serves. Due to the size of the data sets, I chose to look at Citi bike data from June to July 2023. I chose these months as the summer months are typically the most busy. Moreover, using the most up to date data can help create a more relevant model, as it might better reflect current demand patterns.

## Methodology
This project developed a predictive machine learning model to optimize Citi Bike rebalancing operations in Manhattan. Using historical trip data, time-lag features, and weather information, the model forecasted bike demand at specific stations.  

1. **Data Collection**: Acquired Citi Bike trip data, including station-level time-space information, and integrated external weather datasets.  
2. **Feature Engineering**: Designed temporal and spatial predictors, such as time of day, day of the week, and proximity to nearby stations. Introduced time-lag features to capture demand trends.  
3. **Modeling**: Trained and tested multiple regression models, evaluating their performance on prediction accuracy. Achieved a 50% reduction in Mean Absolute Error (MAE) by optimizing feature selection and model tuning.  
4. **Results**: The final model highlighted demand patterns across Manhattan, providing actionable insights to enhance Citi Bike's operational efficiency.