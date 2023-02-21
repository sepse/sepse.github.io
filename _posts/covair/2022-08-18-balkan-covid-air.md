---
layout: post
title: Balkan Air Pollution & COVID
subtitle: Is there a relationship?
gh-repo: sepse/COVAir-Balkans
gh-badge: [star, fork, follow]
tags: [balkan, covid, air pollution]
comments: true
---

![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/banner.jpg)

A data science research project, supported by [**FLOSSK - Free Libre Open-Source Software Kosova**](https://flossk.org/) through [**Techcamp**](https://techcamp.america.gov/about/). This project's objective is to promote the use of Data Science tools and Machine Learning algorithms, through which we will analyze datasets regarding air pollution and COVID in the Balkans and get a better understanding of these phenomena. The goal is to use these tools to gather new insight from large datasets, and potentially use them to fight misinformation with the power of algorithms.

## Introduction
This project initially started several years before as a citizen-science initiative to install DIY air pollution sensors in Kosovo through [Sensor Community](https://sensor.community), as a means of quantifying and understanding the phenomenon of air quality and the potential causes and patterns. As environmental concerns became more evident in the Balkans, there was a strong lack of concrete and open data about air pollution. The advantage of this global community-driven initiative is that the data gathered is standardized, as they all use the same type of sensor, and they can be placed in areas where local communities may have concerns, thereby raising awareness about the state of the environment.

## Objective
By having access to this vast network of sensors, in-depth raw data will be gathered from 6 major Balkan cities and be used as a example to perform data science studies to find potential relationships between phenomena in general. As there are numerous studies that find a relationship between air quality and respiratory diseases; by having large amounts of COVID data gathered institutionally and available makes studying this phenomenon much more viable using data science tools, that would otherwise be daunting. 
By performing exploratory analysis of data from these cities we can get different profiles of them in ways that will allow us get a better perspective about how they rank in comparison as well as how they handle issues such as pollution and pandemic response.

## Data
### Air Pollution Data
![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/pmgraphic.jpg)

PM stands for particulate matter (also called particle pollution): the term for a mixture of solid particles and liquid droplets found in the air. Some particles, such as dust, dirt, soot, or smoke, are large or dark enough to be seen with the naked eye. Others are so small they can only be detected using an electron microscope. Air particle pollution includes:

- **PM10** : inhalable particles, with diameters that are generally 10 micrometers and smaller; and
- **PM2.5** : fine inhalable particles, with diameters that are generally 2.5 micrometers and smaller. [Source](https://www.epa.gov/pm-pollution/particulate-matter-pm-basics)

Daily air pollution data (PM10 & PM2.5) has been gathered from 2019 to 2022, to coincide with the COVID pandemic [Source](https://archive.sensor.community/), from the following cities: 

* Prishtina 
* Skopje
* Tirana
* Belgrade
* Banja Luka
* Zagreb 

![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/airbalkans.jpg)

### COVID Data ##
COVID data has been gathered from: [Our World In Data](https://ourworldindata.org/coronavirus). It includes:

- **Cases**: How many new cases are being confirmed each day? How many cases have been confirmed since the pandemic started? How is the number of cases changing?
- **Deaths**: How many deaths from COVID-19 have been reported? Is the number of deaths rising or falling? How does the death rate compare to other countries?
- **Vaccinations**: How many vaccine doses are being administered each day? How many doses have been administered in total? What share of the population has been vaccinated?
- **Testing**: How much testing for coronavirus do countries conduct? How many tests did a country do to find one COVID-19 case?
Government responses: What measures did countries take in response to the pandemic?

All datasets can be accessed via this link [Complete Datasets](https://drive.google.com/drive/folders/1jQUcwHCfegaoPiOR3yDSgqbY3zlYsIAx?usp=sharing)

## Methodology 
All data processing, exploration and visualization will be conducted using Python notebooks hosted in [Google Colab](https://colab.research.google.com/). The material is available as a tool to further explore the topics and learn about air quality and COVID in particular, and data science in general. Notebooks will open in Colab, where you can see the research methodology performed on the dataset; notebooks also allow you to tweak them to further explore the data on you own.

**The notebooks:** [Balkan Air Pollution](https://github.com/sepse/COVAir-Balkans/blob/main/balkan_pollution.ipynb); and [Balkan Covid](https://raw.githubusercontent.com/sepse/COVAir-Balkans/blob/main/balkan_covid.ipynb)




## First Results
Not surprisingly, from initial data exploration of overall region we can see the clear seasonality and trend of pollution levels due to increased burning of wood and coal for heating during the winter. It is particularly interesting to see how different city profiles emerge by looking at baseline air pollution during non-winter months, namely as it addresses other factors that might contribute to air quality (vehicles, industrial activities). These results might not point to specific cause of pollution, however it provides us an advantage to better investigate the phenomenon and potentially identify potential culprits that might play a major role. For instance, one key takeaway that stands out is the improvement of air quality during the COVID lockdown periods, possibly due to decreased traffic. 

![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/balkanair.jpg)

![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/seasonality.jpg)

Meanwhile our exploration of COVID dataset also reveals somewhat similar country profiles as far as general trendlines are concerned, nevertheless some unique patterns do emerge and they become evident as we visually investigate.

![airbalkans](https://raw.githubusercontent.com/sepse/COVAir-Balkans/main/Graphics/covidbalkan.jpg)

This analysis provides a general understanding of how Balkan countries relate to one another, and it does raise some questions that might be worthy of further investigation from different domains. Namely, the strongest correlation exists between 'New Testing' and 'New Cases' variables, which could  explain the anomalies in the trendlines above.


For more in-depth analysis and visual representation, refer to the complete studies in the notebooks above.

*"This project is financed under the TechCamp Kosovo small grant program, funded by the Bureau of Educational & Cultural Affairs through the U.S. Embassy Pristina, Kosovo, in partnership with FLOSSK."*
