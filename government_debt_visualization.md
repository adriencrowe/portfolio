# <strong>Visualizing Government Debt<strong>
  
- [Government Debt Master Dataset](government_debt_master.xlsx)

##### This project is meant to capture the effects on storytelling of redesigning a data visualization. In the status quo visual below, we are provided with a single year bar chart of debt-GDP ratios for a number of countries. While this visualization does make it fairly clear which countries have larger debt and which have smaller debt, there is much to be desired. Specifically, the viewer is given no context as to how each countries' debt got to the level it is today.
##### In the second visualization, the debt ratios have been broken out by country and depicted over a period of time as sparkline graphs. In this way, the viewer can better understand overall trends in debt overtime, as well as which countries have deviated from the norm or average overtime. With that said, this visualization does not focus the viewers attention very well and it may be difficult to pick up on these trends.
##### The third visualization attempts to highlight a couple of over-arching regions to better understand the aggregated effect of two events, the 2008 financial crisis and the Covid-19 Pandemic, on debt levels. To tell this story, countries have been aggregated by region using a country map which has been provided above. Then debt ratios were averaged across these regions, and the Americas and Europe were highlighted to focus in on two of the largest economies around the globe.

##### Read on for more details on each visualization!
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  
### Status Quo:
  
  <iframe src="https://data.oecd.org/chart/6S0A" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6S0A" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

### Visualizing Debt Over Time:
  - In this redesign, I have taken the data presented by OECD, and redesigned it to depict the change in the GDP-Debt ratio over time by country. This allows the viewer to see at the country level how trends in debt have been changing over time since the 90s. Seeing these trends provides more context into how each country got the the level of debt it is at today. It also provides context into specific periods of time throughout recent history during which debt was elevated across the globe (I.e. the 2008 financial crisis) which may feel highly localized or at least nationalized for many people when in reality these events have global impacts in the 21st century.
  
  
  <div class="flourish-embed flourish-chart" data-src="visualisation/11691730"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

### Creating A New Story From The Data:
  - In this final design, I have grouped countries by region (Americas, Europe, Asia, Africa, and Oceania), and aggregated GDP-Debt ratios of countries with available data within these over-arching regions. The story here is directly related to the Covid-19 Pandemic, and it's effect on global markets. While all markets were effected by this pandemic, I largely wanted to focus on the Americas and Europe, as these were two of the hardest hit regions around the globe. Additionally, they account for much of the global GDP. Additionally, I wanted to track how countries in these two regions have managed to come back from the crisis which occurred in 2020. Therefore, I have designed this visualization to highlight the GDP-Debt ratio for the Americas as well as Europe, but still included the other regions for comparison. Notably, Asia has struggled more with post pandemic recovery than European countires on average; with an increasing debt ratio comparably. Some of this increase could be explained by Japan's burgeoning debt, though other countries have certainly felt the impacts of Covid-19 in Asia.
    - It's worth noting that for both the Americas and Europe, the Covid-19 Pandemic has had a larger impact on government debt levels than during the 2008 financial crisis. At that time, the ratio increased by 14% and 16% respectivelly from 2007 to 2009 for the Americas and Europe. During the Covid-19 Pandemic, government debt increased by 24% and 18% respectively for the Americas and Europe. It is also worth noting that government debt started at a more elevated level during the most recent uptick. In 2019, government debt was at 83% and 76% of GDP for the Americas and Europe while in 2007 government debt was at 58% and 50% respectivelly. Both the relative increase and the high starting levels indicate poor economic trends leading up to and following the Covid-19 Pandemic.
  
  <div class="flourish-embed flourish-chart" data-src="visualisation/11692050"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
