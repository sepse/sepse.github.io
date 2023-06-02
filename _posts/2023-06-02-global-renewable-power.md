# Global Renewable Energy :earth_africa: :recycle: :sunny:
A data science research project, analyzing global renewable energy production in general, and taking a closer look at Balkans in particular.

## Objective
The objective of this data science research project is to analyze global renewable energy production from different sources such as solar, wind, geothermal, and hydroelectric power. By using big data analytics techniques, we aim to gain insights into the current trends and patterns associated with each source. This analysis is crucial because the development of clean energy resources is essential for addressing climate change and promoting sustainability worldwide. Understanding how these technologies perform at large scales helps policymakers make informed decisions related to energy infrastructure investments, which ultimately impacts both economic growth and environmental preservation. With this research, we hope to contribute towards building a more resilient future through better use of natural resources.


## What is Renewable Energy?

Renewable energy comes from sources or processes that are constantly replenished. These sources of energy include solar energy, wind energy, geothermal energy, and hydroelectric power.

Renewable sources are often associated with green energy and clean energy, but there are some subtle differences between these three energy types. Where renewable sources are those that are recyclable, clean energy are those that do not release pollutants like carbon dioxide, and green energy is that which comes from natural sources. While there is often cross-over between these energy types, not all types of renewable energy are actually fully clean or green. For example, some hydroelectric sources can actually damage natural habitats and cause deforestation.

Types: 
- Solar Power
- Wind Power
- Hydroelectric Power
- Biomass Energy
- Geothermal
- Tidal Power

Renewable energy offers a range of benefits including offering a freely available source of energy generation. As the sector grows there has also been a surge in job creation to develop and install the renewable energy solutions of tomorrow. Renewable sources also offer greater energy access in developing nations and can reduce energy bills too.

Of course, one of the largest benefits of renewable energy is that much of it also counts as green and clean energy. This has created a growth in renewable energy, with wind and solar being particularly prevalent.

However, these green benefits are not the sole preserve of renewable energy sources. Nuclear power is also a zero-carbon energy source, since it generates or emits very low levels of CO2. Some favour nuclear energy over resources such as solar and wind, since nuclear power is a stable source that is not reliant on weather conditions. Which brings us onto some of the disadvantages of renewable energy.
[Source](https://www.twi-global.com/technical-knowledge/faqs/renewable-energy)


## Data
The Global Power Plant Database is a comprehensive, open source database of power plants around the world. It centralizes power plant data to make it easier to navigate, compare and draw insights for one’s own analysis. The database covers approximately 35,000 power plants from 167 countries and includes thermal plants (e.g. coal, gas, oil, nuclear, biomass, waste, geothermal) and renewables (e.g. hydro, wind, solar). Each power plant is geolocated and entries contain information on plant capacity, generation, ownership, and fuel type.


Dataset can be accessed via this link [Complete Datasets](https://datasets.wri.org/dataset/globalpowerplantdatabase)


## Methodology
All data processing, exploration and visualization will be conducted using Python notebooks hosted in Google Colab (a free service available to all Google users). The material is available as a tool to further explore the topics and learn about noise pollution in particular, and data science in general. Notebooks will open in Colab, where you can see the research methodology performed on the dataset; notebooks also allow you to tweak them to further explore the data on you own.

The data science methodology involves the following:

- Data loading: Load the dataset into the Python notebook using a library like Pandas. The dataset should contain power plant data such as: Name of powerplant, geolocation, country, capacity in MegaWatts, primary fuel, GWH production for the year 2020.
- Data cleaning: Check for missing or duplicate values in the dataset and remove or impute them as necessary. Also, check for outliers in the data and remove them if they are not meaningful.
- Exploratory data analysis (EDA): Explore the dataset using visualization techniques to understand the patterns and relationships in the data. Plotting histograms, line plots, and scatterplots can help you identify patterns, correlations, and distributions in the data. Use visualizations to understand the distribution of renewable powerplants in the world, and explore the relative capacitites of regional production.
- Visualization: Use visualizations to present the results of the exploration, create interactive maps showing areas of interest, or provide visualizations that help users understand the global landscape of energy production.

**The notebooks:** [Global Power Plants](https://github.com/sepse/Global-Renewable-Energy/blob/f99d4460377f2eb809fcfeb76261e7047e808428/Global_Power.ipynb)

## First Results

Global capacity in generating renewable energy, represented as a heatmap, in MW.
![newplot](https://github.com/sepse/Global-Renewable-Energy/blob/0961e0898026870a373dd7a6c80469e69a6e0ba3/Graphics/newplot.png)

As the above map indicates, China, US, Brasil, Canada and India have a lot of renewable energy capacity. The majority of which is generated by using Hydro, Wind and Solar, as depicted in the barchart below.

![primary](https://github.com/sepse/Global-Renewable-Energy/blob/0961e0898026870a373dd7a6c80469e69a6e0ba3/Graphics/primaryfuel.png)

### Balkan snapshot

In the Balkans, Albania stands out as the leading producer of renewable energy, followed by Montenegro, Bosnia and Croatia. The primary source of renewable energy generation in these countries is hydroelectric power. These countries, boast significant number of rivers and water resources, making it ideal for hydroelectric projects. Their abundant waterways have allowed the countries to harness their hydro potential effectively, making them top producers of renewable energy in the region. This emphasis on hydro power demonstrates the regions' potential to utilizing sustainable energy sources and promoting environmental sustainability.

![capacity](https://github.com/sepse/Global-Renewable-Energy/blob/7b5fb7d85d53d650c745fb3c15b1407cce7c9167/Graphics/balkanenergy.png)

 ### Mapped Balkan renewable power plants
By leveraging the location data available in the dataset, we can perform spatial analysis to visualize the distribution of renewable energy power plants across the Balkan countries. This analysis will help identify geographical patterns, clusters, and areas with untapped potential for renewable energy development.

![mapped](https://github.com/sepse/Global-Renewable-Energy/blob/7b5fb7d85d53d650c745fb3c15b1407cce7c9167/Graphics/balkanmap.png)

Trough this research we have achieved the following: 

- Assessed Global Renewable Energy Capacity: The dataset will provide information on the capacity of renewable energy power plants in the world in general, and the Balkan countries in particular. By analyzing this data, the project can determine the total installed capacity of solar, wind, geothermal, and hydroelectric power sources, both individually and combined. This assessment will help understand the overall renewable energy landscape in the region.

- Identified Dominant Renewable Energy Sources: Through data exploration and visualization techniques, the project can identify the predominant renewable energy sources within the Balkan countries. By determining the proportion of each energy source in the total capacity, it will be possible to highlight the region's strengths and weaknesses in terms of renewable energy production.

- Environmental Impact: Renewable energy sources offer a cleaner alternative to fossil fuels, significantly reducing greenhouse gas emissions and mitigating climate change. Assessing renewable energy production in the Balkan region can help quantify the environmental impact and determine its contribution to global efforts in achieving sustainable development goals.

- Energy Security and Independence: By exploring the renewable energy capacity, the project can identify potential opportunities for Balkan countries to decrease their reliance on imported fossil fuels. This analysis can contribute to enhancing energy security, reducing dependence on external energy sources, and promoting regional energy independence.

***For more detailed view on this research, please open the Notebooks, where more granular information is available in the visual and statistical form.***

**The Notebooks:** [Global Power Plants](https://github.com/sepse/Global-Renewable-Energy/blob/f99d4460377f2eb809fcfeb76261e7047e808428/Global_Power.ipynb)
