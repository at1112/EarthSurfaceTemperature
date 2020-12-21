## An Overview of Regional Effects of Climate Variability: Policy Recommendations 

### Executive Summary 

This report provides (1) a comprehensive overview of regional and temporal differences in earth surface temperature change, emissions, and crop production as a result of climate variability, and (2) a preliminary picture of how regional effects of these variables change over time. 

Policy recommendations focus on addressing food insecurity in low-latitude regions and leveraging the climate feedback mechanisms behind higher crop yield in high-latitude regions to offset reduced crop production in low-latitude regions (e.g. countries in Asia and Africa). It is proposed that high-latitude regions implement a combination of supply-side measures including grazing land management strategies, food diversification efforts, and more efficient transport measures  to reduce greenhouse gas contributions, and thereby offset the impact of lower crop yields in low-latitude regions that (1) experience higher average temperatures than the rest of the world, and (2) do not possess the political or economic infrastructure to alleviate the adverse effects of agricultural changes. 

### Data Sources

Kaggle provides publicly-accessible earth surface temperature data compiled by Berkeley Earth, with an Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. 

This dataset was used jointly with [Food & Agriculture data (FAOSTAT)](http://www.fao.org/faostat/en/#home) provided by the Food and Agriculture Organization (FAO) of the United Nations , and downloaded from Kaggle. FAO is a specialized agency leading international efforts for alleviating hunger and achieving worldwide food security. The specific crop production index pertaining to the gross production value of Agricultural production (relative to base period 1999-2001) is provided at the country-year level (unit is 1000 international dollars).   

Finally, the Greenhouse Gas (GHG) Inventory data was utilized to visualize emissions contributions at the country level. This dataset was downloaded from Kaggle, and the full dataset is published on [UNData](http://data.un.org/Explorer.aspx) The temporal scope of this data covers the period from 1990 to 2007. Anthropogenic emissions values are reported in kilotons CO2, with land use metrics subtracted and additional GHG removals of methane (CH4), nitrous oxide (N20), hydrofluorocarbons (HFCs), and perfluorocarbons (PFCs), among others. 


#### Changes in Average Temperature (degrees Celsius) by Country 

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/1.embed" height="525" width="100%"></iframe>

#### Crop Production Index: Regional Differences

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~at1112/7.embed" height="525" width="100%"></iframe>

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

 
### List/description of the significant technologies/platforms used
I used *Plotly*'s Python interactive graphing library to create the visualizations embedded above. *Plotly* is an open-source graphing library built on top of [plotly.js](https://plotly.com/javascript/). 

I created these visualizations in Jupyter notebooks after performing preliminary data cleaning and exploratory analysis with *NumPy* and *Pandas*. I employed Chart Studio's python package and HTML in order to embed these visualizations. This site was created using [GitHub Pages](https://pages.github.com/).

Technical Documentation can be found here:





