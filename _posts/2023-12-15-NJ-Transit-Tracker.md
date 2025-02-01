---
title: "NJ Transit Tracker"
date: 2023-12-15 00:00:01 +/-TTTT
categories: [Projects]
tags: [R, Machine Learning, Data Engineering]
image: assets/thumbnails/transittracker_wireframe.png
alt: "Transit Tracker Wireframe"
---

## Project Description
Train delays can be incredibly frustrating for riders. Since the pandemic, mass-transit ridership has been slow to bounce back to pre-pandemic levels. I wanted to create a mass transit tracking model that could predict train delays, so that train operators can anticipate potential delays and address issues before severe delays are accrued. I designed this project, using NJ Transit as the client. This project shows how I used spatial-autocorrelation, temporal-features, and physical features to predict train delays.  

### Project Details
**Project Type**: Group

**Contributers**: Lu Yii Wong, Xiaofan Liu

**Skills**: R, Feature Engineering, Machine Learning, Data Analysis, Communication, Wire framing, Collaboration


## Introduction

Our team is interested in mass-transit delay forecasts. As frequent train commuters, we have personally been impacted by train delays along the Northeast-Corridor between Philadelphia and New York City. Our team is invested in understanding how potential transit delays can be identified before travelers are impacted.

The New York-New Jersey-Pennsylvania Metropolitan Statistical Area (NY-NJ-PA MSA) is an important economic hub in the United States of America. Currently, approximately 20 million residents live within the MSA, with an [employed population of 9.81 million](https://datausa.io/profile/geo/new-york-newark-jersey-city-ny-nj-pa). Moreover, according to the 5-year American Community Survey (ACS) for 2019, about [30 percent of residents commute to work via public transit](https://datausa.io/profile/geo/new-york-newark-jersey-city-ny-nj-pa). The large working population and moderately high proportion indicates potential for public transit networks to expand their operations.

[NJ Transit](https://www.njtransit.com/our-agency/about-us) is the nation’s third largest provider for bus, rail, and light rail transit, linking major points in New Jersey, New York and Philadelphia. Our team believes that NJ Transit is well-positioned within the northeast region as a major transit provider. We want to build a tool for the agency to use in order to improve their delay forecast. We believe that this tool will help NJ Transit trains run more efficiently and ultimately boost their overall ridership rates and rider satisfaction rates. We have identified NJ Transit as a potential client as the agency has a business goal to attract more commuters.

## Use Case
The use case for our project is to “Improve NJ Transit Rail Station service by forecasting on-time performance, enabling proactive measures for expected delays”. The tool NJ Transit Tracker will help forecast minute-to-minute delay by station. NJ Transit Tracker will help prioritize potential service delays by severity and importance. This tool aims to optimize the data organization process, so that the agency can direct resources to stations where delay will create the most disturbance.

Currently, [NJ Transit operates 12 rail lines statewide, and services 162 train stations](https://www.njtransit.com/our-agency/about-us), connecting travelers to vital destinations around New Jersey City and New York City. NJ Transit has monitored customer satisfaction through publicly accessible surveys. NJ Transit produced borderline satisfaction results, with [an overall score of 5.1/10](https://www.njtransit.com/surveyresults). NJ Transit had an [overall satisfaction rate of 5.7/10 and 5.2/10](https://www.njtransit.com/surveyresults) for on-time performance at boarding and arrival stations, respectively. The customer satisfaction rates show that there is significant space for improvement for the NJ Transit system.

With a tool like the NJ Tracker, workers can effectively take preemptive action to address potential issues to reduce train delay. When the application is fully implemented, we envision that the Transit Tracker will facilitate actions as displayed in the flow chart.

![nj-transit-flow-chart](assets/thumbnails/nj_transit_flowchart.png)
_NJ Transit System Flow Chart_

This flow chart is a high-level overview of the system, identifying how users and stakeholders can benefit from this product. The primary user of the product is NJ Transit, who will make use of the delay forecast system to help optimize their train services. If more delays can be prevented through the workflow, NJ Transit would reduce overall delay, improve customer satisfaction, and increase ridership in the long-run.

## Methodology 
1. **Data Collection**: Scrapping NJ US Census Data, [NJ Transit Rail Stations data](https://njogis-newjersey.opendata.arcgis.com/datasets/4809dada94c542e0beff00600ee930f6_0/explore), transit [performance data from Kaggle](https://www.kaggle.com/datasets/pranavbadami/nj-transit-amtrak-nec-performance), and weather data from Newark Station. 
2. **Data Processing**: Cleaning and aggregating feeds to create a dataset of actual vs. scheduled arrival times for each stop. 
3. **Reliability Metrics**: Calculating key performance indicators such as on-time performance and average delays across NJ Transit Stations. Analyzed temporal and spatial correlation for on-time train performance. 
4. **Spatial Analysis**: Trained a model to produce accurate and generalizable predictions for train delays, using linear regression and incorporating spatial and temporal lag features. Visualized performance geographically, identifying patterns of delays across routes, and highlighting problematic stops.

## Additional Resources 
Interested in learning more about this project? Watch to our team's [4-minute pitch for our product here](https://www.youtube.com/watch?v=Hv5ObwCQN8k&ab_channel=xiaofanliu).

{% include embed/youtube.html id='Hv5ObwCQN8k' %}

