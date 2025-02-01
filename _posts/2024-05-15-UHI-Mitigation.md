---
title: "Urban Heat Island Mitigation"
date: 2024-05-15 00:00:01 +/-TTTT
categories: [Projects]
tags: [R, ArcGIS, Geospatial Analysis, Remote Sensing, Environmental Modeling]
image: assets/thumbnails/UHI_Philly_Temp.png
alt: "Mean Temperatures in Philadelphia 2011"
---

## Project Description 
This project investigates the relationship between physical environmental factors and the Urban Heat Island (UHI) effect in Philadelphia to recommend targeted cooling strategies. UHIs occur when urban areas replace natural land cover with heat-retaining surfaces like pavement and buildings, leading to higher temperatures that exacerbate energy use, air pollution, and heat-related illnesses. Vulnerable populations, particularly low-income communities, are disproportionately affected due to limited adaptive capacity.

The study focuses on Philadelphia, a city with stark heat disparities across neighborhoods. Using census tract-level analysis, the team evaluates how urban density, tree canopy coverage, and land use patterns contribute to UHI intensity. By addressing the gap in quantitative research linking UHI drivers to heat vulnerability, this work aims to inform equitable, data-driven interventions to mitigate extreme heat in the city’s most impacted areas.

### Project Details 
**Project Type**: Group

**Contributers**: Lu Yii Wong, Yujin Song

**Skills**: R, ArcGIS, Geospatial Analysis, Remote Sensing, Envrionmental Modeling, Data Analysis, Communication, Collaboration

## Introduction
Urban Heat Islands (UHI) occur when cities replace natural land cover with dense concentrations of pavement, buildings, and other surfaces that absorb and retain heat. This effect [increases energy costs, air pollution, heat-related illnesses, and mortality](https://www.epa.gov/green-infrastructure/reduce-urban-heat-island-effect#:~:text=%22Urban%20heat%20islands%22%20occur%20when,heat%2Drelated%20illness%20and%20mortality). The UHI effect results in [higher temperatures in dense urban areas](https://www.littlerock.gov/city-administration/city-departments/public-works/sustainability/urban-heat-islands/) compared to surrounding suburban and rural areas. Temperatures can differ significantly by 15 to 20°F in urban areas than in suburban and rural areas. The disparities in temperature have great implications for living conditions in UHIs. In the summer, higher temperatures will increase the chance of heat-related illnesses such as heat exhaustion and heat strokes, which can be fatal. This is a concern, especially for vulnerable and sensitive populations, such as isolated older adults.

## Use Case
In Philadelphia, heat vulnerability is a concern. Like other urban areas, Philadelphia has been combating the impacts of hotter cities in the summer. In 2022, Philadelphia recorded its 2nd hottest summer ever, with an [average temperature above 90°F in August](https://whyy.org/articles/philadelphia-2022-one-of-warmest-years-on-record-climate-change/#:~:text=August%202022%20broke%20records%20in,high%20of%20over%2090%20degrees). According to a Department of Health spokesperson, [eight heat-related deaths were recorded for the summer of 2022](https://www.inquirer.com/weather/philadelphia-weather-record-heat-climate-summer-2022-20220901.html). Although high temperatures are a concern across the city, the impacts of higher temperatures are not evenly distributed across the city. A 2022 Philadelphia Heat Watch study showed that temperatures across the city were not uniform. For instance, high-density developed areas in the downtown core recorded higher temperatures than areas with high-density tree canopies like Fairmount Park.

As the impacts of climate change intensify, summers will become longer and hotter. Cities must act now to mitigate future effects of heat. This project investigates how the physical environment impacts urban temperature, with the goal of recommending interventions to keep urban areas cool during hotter months. 

## Methodology 
1. **Data Collection**: Utilized Landsat imagery to estimate land surface temperature, National Land Cover Database (NLCD) tree canopy and land cover data to identify permeable surfaces, and US Census data to incorporate socio-economic variables.  
2. **Data Processing**: Processed Landsat thermal bands to calculate surface temperatures using zonal statistics, highlighting temperature disparities across Philadelphia. Applied Ordinary Least Squares (OLS) regression to analyze the socio-economic factors contributing to heat vulnerability.  

## Key Findings 
1. A greater share of tree canopy cover corresponds to significantly decreased surface temperatures. 
2. A greater share of permeable surfaces corresponds to a significant decrease in surface temperatures. 
3. The models showed that the average land surface temperature is statistically associated with the share of vulnerable populations in 2011 and 2021. A higher share of vulnerable populations corresponds to increased surface temperatures, all else equal.

### Policy Recommendations
* Expand Existing Tree Planting Programs in Philadelphia
* Preserve Existing Wetlands and Natural Spaces
* Advocate for Additional Cooling Resources in Heat-Vulnerable Areas