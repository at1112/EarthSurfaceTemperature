# Regional Effects of Climate Variability: Temperature-Agriculture Relationships
## Anjali Taneja 
#### PPOL-563

### Executive Summary 

It is hypothesized that small, incremental increases in earth surface temperature contribute to decreased agricultural productivity and resultant adverse outcomes embedded in interconnected environmental and social processes. Therefore, it is necessary to obtain a more complete picture of climate variables longitudinally, as well as the relationships between these variables and social process variables related to factors such as crop production indices. This report examines the relationship between crop production index and changes in surface temperature, since crop production is a potential mediating factor between climate change and processes such as migration, civil conflict, and economic productivity. 

This report provides (1) a holistic overview of regional and temporal differences in earth surface temperature change and crop production and (2) a preliminary picture of how regional effects of these variables change over time. An examination of trends at both the country level and continental region level provide a foundation for studying how climate feedback mechanisms might produce differential crop yields in high-latitude and low-latitude regions. The "Green Revolution" beginning in the 1950s is plausibly responsible for higher crop production indices over the last 50-60 years; it is difficult to capture temperature effects on crop yields due to the effect of agricultural production initiatives occurring post-World War II. Further research is required to understand the more granular implications of regional effects of temperature on agricultural production indices at the country level. 

The findings that follow serve as a foundation for examining how to address food insecurity in regions marked by higher temperature and lower crop production indices, and leveraging the climate feedback mechanisms behind higher crop yield in northern hemispheric regions to offset reduced crop production in countries exhibiting high temperatures and low crop production indices (e.g. Africa). It is proposed that regions marked by higher gross crop production and mild and moderate climate factors (e.g. Europe, Americas) implement a combination of supply-side measures including grazing land management strategies, food diversification efforts, and more efficient transport measures to reduce greenhouse gas contributions ([IPCC](https://www.ipcc.ch/srccl/chapter/chapter-5/)), and thereby offset the impact of lower crop yields in regions such as Africa that (1) experience higher average temperatures than the rest of the world, and (2) do not possess the political or economic infrastructure to alleviate the adverse effects of temperature-related agricultural changes.  

### Data Sources & Methodology

Kaggle provides publicly-accessible earth surface temperature data on 243 countries compiled by Berkeley Earth, with an Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. After removing missing values, the temporal scope of this data spans the period 1750-2015. This data was filtered and cleaned using *pandas* and the final data included observations from 1950-2013, in order to more closely examine trends in surface temperature and agricultural productivity as a result of the [Green Revolution](https://www.thoughtco.com/green-revolution-overview-1434948). Earth surface temperature compiled by major city was used to map countries to continents using a combination of data wrangling methods, including some implemented on [Kaggle](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data/notebooks) simply to map continents to each country-level observation. 

This dataset was used jointly with [Food & Agriculture data (FAOSTAT)](http://www.fao.org/faostat/en/#home) provided by the Food and Agriculture Organization (FAO) of the United Nations , and downloaded from Kaggle. FAO is a specialized agency leading international efforts for alleviating hunger and achieving worldwide food security. The specific crop production index pertaining to the gross production value of Agricultural production (relative to base period 1999-2001) is provided at the country-year level (unit is 1000 international dollars). After removing missing values, the temporal scope of this data spans the period 1961-2007. This dataset was filtered in order to include only observations for gross production value of agriculture (see [data](https://github.com/at1112/EarthSurfaceTemperature/blob/gh-pages/Technical%20Documentation.zip), element_code == '152'). The cleaned earth surface temperature and FAO datasets were merged at the country-year level in order to produce the following visualizations. 

### Findings

The visualization below depicts average temperature at the country level (recorded in degrees Celsius) for each year in the period 1950 - 2013. This visualization displays subtle increases in temperature over this time period; rising earth surface temperature occurs with small, incremental changes that have particularly drastic effects including rising sea levels which deem coastal areas uninhabitable, and adversely affect crop production in some regions. 


<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/1.embed" height="525" width="100%"></iframe>


The visualization below depicts average temperature means calculated at the level of continental region. It is apparent that Asia and Africa consistently experience higher temperatures, Oceania & the Americas experience moderate climates, and Europe experiences lower temperature on average, likely due to hemispheric regional climate effects. Surface Temperature data by region was aggregated over the period 1950 – 2013 since this was the mutual temporal scope of the merged data after correcting for missingness and omitting outliers. Additionally, I wanted to examine temperature trends at the continent level during the beginning of the Green Revolution. I used [ColorBrewer](https://colorbrewer2.org/#type=diverging&scheme=RdYlBu&n=5) to select a 5-class RdYlBu palette that is color-blind friendly. 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/25.embed" height="525" width="100%"></iframe>

The following visualization indicates average crop production indices by continental region, over the period 1961-2007. These production indices pertain specifically to the gross production value of agricultural sectors (relative to base period 1991-2001), reported in units of $1,000 International dollars. It is evident that Asia experiences a dramatic surge in gross production value for countries' agricultural sectors, which can be attributed to the adoption of agricultural initiatives during the Green Revolution starting in the 1950s and 1960s. This visualization portrays how crop production is differentially affected by region and how it changes over time. I used [ColorBrewer](https://colorbrewer2.org/#type=diverging&scheme=RdYlBu&n=5) to select a 5-class RdYlBu palette that is color-blind friendly.  

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/31.embed" height="525" width="100%"></iframe>

The plot below displays country-level crop production indices (1,000 I$) over the years 1961 - 2007 with continental region indicators. Rising earth surface temperatures are characterized by subtle incremental changes that are difficult to capture. However, using the plot below, one might be able to follow how specific countries' agricultural productivity indicies change over time. This plot is limited to crop production index values below 60,000,000 (1,000 I$). Countries which experience crop production indicies above this threshold move outside of the bounds of this particular visualization so that we can better visualize countries with crop production indices in this range. We can use this visualization jointly with the one above in order to understand which countries might be contributing to sharp increases in crop production index at the continental region level (e.g. China, Brazil, etc). 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/33.embed" height="525" width="100%"></iframe>

Here is the same data scaled out in order to better visualize sharp, exponential increases in a few "outlier" countries (e.g. China): 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/39.embed" height="525" width="100%"></iframe>



### Recommendations:

1.	Countries which exhibit higher crop production indices in the face of high temperatures, or countries in regions which seem to have climate-resistant crops (e.g. those in the Americas, though it is bold to make this claim based only upon temperature and crop production data) can implement production targets that account for regional effects of temperature on crop production. More specifically, this means placing more stringent regulations on countries in the Americas to curb greenhouse gas emissions. 
2.	Implementing supply-side practices ([IPCC](https://www.ipcc.ch/srccl)) which reduce livestock emissions through grazing land management is advisable. Leveraging the positive effects of temperature increases on food systems in the Americas and even Asia in order to offset the negative effects of temperature increases on crop production in countries within Africa provide an opportunity to use a “food system” approach to offsetting food insecurity as a result of climate change. 
3.	We recommend land-based changes in countries in the Americas to mitigate the negative temperature effects in other regions. This can also be accomplished through diversifying food choice in regions marked by moderate climates as well (e.g. Americas, Oceania) as well, because production systems and individual diets play a large role in greenhouse gas contributions. 
4.	Implementing more efficient production and transport measures in the Americas and Europe can potentially offset the impact of lower crop yields in regions that do not possess the infrastructure to alleviate the adverse effects of agricultural changes.


 
### Tools

I used *Plotly*'s Python interactive graphing library to create the visualizations embedded above. *Plotly* is an open-source graphing library built on top of [plotly.js](https://plotly.com/javascript/). 

I created these visualizations in Jupyter notebooks after performing preliminary data cleaning and exploratory analysis with *NumPy* and *Pandas*. I employed Chart Studio's python package and HTML in order to embed these visualizations. This site was created using [GitHub Pages](https://pages.github.com/).

### Technical Documentation can be found here:

[Technical Documentation.zip](https://github.com/at1112/EarthSurfaceTemperature/blob/gh-pages/Technical%20Documentation.zip)





