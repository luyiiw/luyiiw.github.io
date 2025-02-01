---
title: "Health Equity Index"
date: 2024-12-15 00:00:01 +/-TTTT
categories: [Projects]
tags: [Python, Geospatial Analysis, Environmental Modeling]
image: assets/thumbnails/HEI_health_outcomes.png
alt: "Cancer and Asthma Rates in Philadelphia"
---

## Project Description 
This project introduces the Health Equity Index (HEI), a robust data-driven framework designed to evaluate health inequities at the census tract level and inform targeted public health interventions. Through the integration of diverse datasets covering environmental risks (tree canopy, heat vulnerability, lead exposure, asthma prevalence) and socioeconomic indicators (income, education, and racial composition), the HEI offers a holistic approach to identifying at-risk neighborhoods. The project leverages geospatial analysis, exploratory data visualization, correlation heatmaps, and clustering techniques to uncover actionable insights into the spatial and statistical relationships between social, economic, and health-related variables.

### Project Details 
**Project Type**: Group

**Contributers**: Lu Yii Wong, Yujin Song

**Skills**: Python, Geospatial Analysis, Unsupervised Machine Learning, Envrionmental Modeling, Data Analysis, Communication

## Introduction 
Health equity is a pressing concern in urban settings, where environmental and socioeconomic disparities significantly impact community well-being. In Philadelphia, these disparities are particularly pronounced, with marginalized communities facing heightened exposure to environmental hazards and limited access to resources that promote healthy living. This report introduces the Health Equity Index (HEI), a tool designed to evaluate health outcomes and identify vulnerable areas at the census tract level. By integrating environmental data such as tree canopy coverage, heat vulnerability, asthma and cancer prevalence, and child blood lead levels with socioeconomic indicators like income, education, and racial composition, the HEI provides a holistic framework to analyze health inequities in Philadelphia.

This project has three primary objectives:
- Highlight socioeconomic and demographic indicators that underscore areas at risk of health inequities.
- Identify neighborhoods requiring prioritization for targeted public health interventions.
- Explore the relationships between socioeconomic factors and environmental health outcomes.

The findings aim to support Philadelphia’s environmental justice goals, as outlined in local initiatives like the Philly Tree Plan, by providing actionable insights backed by data-driven evidence to inform equity-driven public health and environmental strategies. By bridging data analysis with urban policy, this research seeks to promote healthier, more equitable communities across the city.

## Methodology
- **Data Collection**: We sourced data from OpenDataPhilly, the U.S. Census Bureau, and the CDC PLACES initiative. Key datasets included tree canopy data, child blood levels, asthma and cancer rates, and socio-economic data from the 5-year American Community Survey.
- **Exploratory Analysis**: Preliminary data visualizations, including heat maps and choropleth maps, were created to identify spatial patterns and trends. 
- **Statistical Analysis**: We employed scatterplots and Peason correlation coefficients to assess relationships between socioeconomic variables and health outcomes.
- **Clustering Analysis**: K-mean clustering grouped census tracts based on socioeconomic indicators.

## Health Equity Index Construction
Using weighted scores for environmental, health, and socioeconomic indicators, we developed the HEI to rank census tracts by their relative vulnerability. The weights were informed by correlation strengths and policy priorities, aligning with Philadelphia’s environmental justice goals.