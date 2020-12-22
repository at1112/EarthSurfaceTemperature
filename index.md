## An Overview of Regional Effects of Climate Variability: Policy Recommendations 

### Executive Summary 

This report provides (1) a holistic overview of regional and temporal differences in earth surface temperature change, emissions, and crop production as a result of climate variability, and (2) a preliminary picture of how regional effects of these variables change over time. An examination of trends at both the country level and continental region level provide a foundation for studying how climate feedback mechanisms might produce differential crop yields in high-latitude and low-latitude regions. The "Green Revolution" beginning in the 1950s is plausibly responsible for higher crop production indices over the last 50-60 years; it is difficult to capture temperature effects on crop yields due to the effect of agricultural production initiatives occurring post-World War II. Further research is required to understand the implications of regional effects of temperature marked by higher granularity. 

Policy recommendations focus on addressing food insecurity in low-latitude regions and leveraging the climate feedback mechanisms behind higher crop yield in high-latitude regions to offset reduced crop production in low-latitude regions (e.g. countries in Asia and Africa). It is proposed that high-latitude regions implement a combination of supply-side measures including grazing land management strategies, food diversification efforts, and more efficient transport measures  to reduce greenhouse gas contributions, and thereby offset the impact of lower crop yields in low-latitude regions that (1) experience higher average temperatures than the rest of the world, and (2) do not possess the political or economic infrastructure to alleviate the adverse effects of agricultural changes. 

The visualization below depicts average temperature at the country level (recorded in degrees Celsius) for each year in the period 1950 - 2013. 


<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/1.embed" height="525" width="100%"></iframe>


The visualization below depicts average temperature means calculated at the level of continental region. It is apparent that Asia and Africa consistently experience higher temperatures, Oceania & the Americas experience moderate climates, and Europe experiences lower temperature on average, likely due to hemispheric regional climate effects. Surface Temperature data by region was aggregated over the period 1950 – 2013 since this was the mutual temporal scope of the merged data after correcting for missingness and omitting outliers. Additionally, I wanted to examine temperature trends at the continent level during the beginning of the Green Revolution.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/25.embed" height="525" width="100%"></iframe>

The following visualization indicates average crop production indices by continental region, over the period 1961-2007. These production indices pertain specifically to the gross production value of agricultural sectors (relative to base period 1991-2001), reported in units of $1,000 International dollars. It is evident that Asia experiences a dramatic surge in gross production value for countries' agricultural sectors, which can be attributed to the adoption of agricultural initiatives during the Green Revolution starting in the 1950s and 1960s. 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/31.embed" height="525" width="100%"></iframe>

#### The Big Emitters
 [bar graph]
 dfs

#### The Green Revolution: Crop Production Index versus Average Temperature (degrees Celsius)
This has points all over the place:

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/10.embed" height="525" width="100%"></iframe>


### Methodology

### Recommendations:

1.	Because it is hard to control for the regional variables discussed above in lower-latitude regions, we suggest production targets that account for regional effects of temperature on crop production. More specifically, this means placing more stringent regulations on countries in the Americas to curb greenhouse gas emissions. 
2.	We suggest the implementation of supply-side practices which reduce livestock emissions through grazing land management . Leveraging the positive effects of temperature increases on food systems in the Americas in order to offset the negative effects of temperature increases on crop production in lower-latitude regions such as Asia and Africa provide an opportunity to use a “food system” approach to offsetting food insecurity as a result of climate change. 
3.	We recommend land-based changes in countries in the Americas to mitigate the negative temperature effects in other regions. This can also be accomplished through diversifying food choice in higher-latitude regions as well, because production systems and individual diets play a large role in greenhouse gas contributions. 
4.	Implementing more efficient production and transport measures in the Americas can potentially offset the impact of lower crop yields in low-latitude regions that do not possess the infrastructure to alleviate the adverse effects of agricultural changes.


### Data Sources

Kaggle provides publicly-accessible earth surface temperature data on 243 countries compiled by Berkeley Earth, with an Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. After removing missing values, the temporal scope of this data spans the period 1750-2015. 

This dataset was used jointly with [Food & Agriculture data (FAOSTAT)](http://www.fao.org/faostat/en/#home) provided by the Food and Agriculture Organization (FAO) of the United Nations , and downloaded from Kaggle. FAO is a specialized agency leading international efforts for alleviating hunger and achieving worldwide food security. The specific crop production index pertaining to the gross production value of Agricultural production (relative to base period 1999-2001) is provided at the country-year level (unit is 1000 international dollars). After removing missing values, the temporal scope of this data spans the period 1961-2007. 

Finally, the Greenhouse Gas (GHG) Inventory data was utilized to visualize emissions contributions at the country level. This dataset was downloaded from Kaggle, and the full dataset is published on [UNData](http://data.un.org/Explorer.aspx) The temporal scope of this data covers the period from 1990 to 2007. Anthropogenic emissions values are reported in kilotons CO2, with land use metrics subtracted and additional GHG removals of methane (CH4), nitrous oxide (N20), hydrofluorocarbons (HFCs), and perfluorocarbons (PFCs), among others. 
 
### List/description of the significant technologies/platforms used
I used *Plotly*'s Python interactive graphing library to create the visualizations embedded above. *Plotly* is an open-source graphing library built on top of [plotly.js](https://plotly.com/javascript/). 

I created these visualizations in Jupyter notebooks after performing preliminary data cleaning and exploratory analysis with *NumPy* and *Pandas*. I employed Chart Studio's python package and HTML in order to embed these visualizations. This site was created using [GitHub Pages](https://pages.github.com/).

Technical Documentation can be found here:





