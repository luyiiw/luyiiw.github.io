---
title: "Home Repair Enrollment Predictor"
date: 2023-11-15 00:00:01 +/-TTTT
categories: [Projects]
tags: [R, Machine Learning, Cost-Benefit Analysis, Predictive Modeling]
image: assets/thumbnails/housing_subsidy.png 
alt: "Housing Subsidy Model Cross-validation" 
---

## Project Description
I built this enrollment predictor using a hypothetical scenario. A hypothetical Department of Housing and Community Development agency was faced with low enrollment rates in its Home Repair Tax Credit Program, mainly due to outreach being conducted at random. This project involved building a classification model to predict which homeowners were most likely to enroll in the program, enabling HCD to run a more targeted outreach campaign that reduces costs while increasing program efficiency.

### Project Details
**Project Type**: Individual

**Contributers**: Lu Yii Wong

**Skills**: R, Machine Learning, Cost-Benefit Analysis, Data Visualization, GLM Modeling, Cross-Validation

## Introduction
Maintaining affordable and quality housing is critical for ensuring neighborhood stability and improving residents’ quality of life. In this hypothetical city, many homeowners, particularly those from low- to moderate-income households, struggle to finance essential home repairs, leaving their homes vulnerable to structural decline and reduced property value. To address this challenge, the Department of Housing and Community Development (HCD) launched the Home Repair Tax Credit Program to assist eligible homeowners in covering repair costs and preserving the city’s aging housing stock.

Despite its potential to create positive community impacts, the program faces a key obstacle: low enrollment rates. Currently, HCD’s outreach strategy involves contacting homeowners at random, which results in high marketing costs and limited efficiency. This project seeks to optimize outreach efforts by developing a predictive model to identify homeowners most likely to participate in the program. The model provides a targeted approach that reduces marketing expenditure while increasing program participation by applying data analytics and machine learning techniques.

The project has three main goals:
1. Develop a predictive model to classify homeowners based on their likelihood of enrolling in the tax credit program.
2. Evaluate the model’s performance using statistical metrics such as accuracy, sensitivity, and specificity.
3. Conduct a cost-benefit analysis to assess how targeted outreach could improve program efficiency and outcomes.

The insights from this model will help HCD make data-driven decisions, enabling a more cost-effective and impactful program. Although hypothetical, this project demonstrates how predictive analytics can be applied to real-world urban programs, offering a framework that other municipalities could adopt to improve service delivery and resource allocation.

## Methodology

- **Data Cleaning & Exploration**: Remortted and aggregated campaign data, ensuring key features like previous contact history, education level, and campaign frequency were ready for analysis.
- **Data Visualization**: Used visualizations to explore correlations between homeowner characteristics and enrollment likelihood. 
- **Model Development**: Built and tested several generalized linear models (GLM) using McFassen’s pseudo R-squared to assess performance. The first model, which retained the most features, produced the best McFadden score of 2.1.
- **Model Evaluation**: Evaluated the model using accuracy, sensitivity, specificity, ROC curves, and k-fld cross-validation. Despite a high specificity (98%) and overall accuracy of 90%, the model had low sensitivity (24%), revealing a challenge in identifying true positives due to imbalanced data. 

## Use Case 
The model offers HCD a data-driven approach to prioritize outreach to eligible homeowners most likely to enroll in the program. By using this model, HCD can reduce unnecessary marketing expenditures while increasing the likelihood of homeowner participation, ultimately maximizing the program’s impact. 

Although this project is hypothetical, it demonstrates the real-world applicability of predictive modeling in public policy and program management. For example, similar approaches are used to forecast healthcare needs, identify potential food insecurity zones, and predict disaster impact. 
