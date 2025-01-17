# Visual Design Critique

### - Original Graphic
  - The chosen graphic for this project represents the total number of acres burned and total number of fires by year for the past 10 years within the United States. This graphic is part of a [larger visualization project](https://www.usatoday.com/in-depth/news/2020/09/10/wildfires-california-washington-oregon-drought-heat-climate-change-graphics/5764156002/) from USA Today which attempts to put the wildly large wildfires from recent years into a context that's more easy to understand. 
  - They do so by comparing the total number of acres burned by wildfires in one year to the size of New York City. This aspect of the visualization works well, but the graphic which I've chosen to redesign feels like an oversight in comparison. While the aesthetics of the graphic are not too bad, it does little to provide useful information on the topic of concern. The visualization is limited to the past 10 years of data, so it does not depict the historical trend and increasing size of fires overtime.
  - In addition, the years are ordered chronoligically making it more difficult to pick out the worst, or best years for wildfires. The line chart depicting the number of fires per year also provides little useful context. There doesn't appear to be any correlation between the number of acres burned and the number of fires per year so this added information just clutters the visualization.
  - For these reasons, I've chosen to redesign this visualization to include historical context for the data. In the context this data is presented, which is informing normal people about the outlandish size of recent wildfires, providing the historical context better informs people about how bad the situation is today. This would hopefully move people to demand or create change as much as possible.

<div class="infogram-embed" data-id="_/jBKgoCtjCakSFM6oPI58" data-type="interactive" data-title="Fires vs acres burned 2020" data-processed="1" id="ig-138f25c5-c0f7-21e4-c909-b344459df66f" style="min-height: 1px;"><iframe src="https://e.infogram.com/_/jBKgoCtjCakSFM6oPI58?parent_url=https%3A%2F%2Fwww.gannett-cdn.com%2Fexperiments%2Fusatoday%2Ftools%2Fstatic-graphic-embeds%2Findex.html%3Finfogram%3D%253Cdiv%2520class%253D%2522infogram-embed%2522%2520data-id%253D%2522_%252FjBKgoCtjCakSFM6oPI58%2522%2520data-type%253D%2522interactive%2522%2520data-title%253D%2522Fires%2520vs%2520acres%2520burned%25202020%2522%253E%253C%252Fdiv%253E&amp;src=embed" scrolling="no" frameborder="0" allowfullscreen="" title="Fires vs acres burned 2020" style="border: none; width: 626px; height: 363px;"></iframe></div>

### - Wireframing The Redesign
  - I want to depict the growth of these fires overtime. One option is to create a dot chart with the number of acres burned on one axis and years on the other. There are a number of ways to depict the increase here. First, the chart itself would show the change. In addition, I can use color or size to depict the increase over time. Finally, I could highlight a certain subset of years to show that many of the worst years have happened most recently. 
  - The following wireframe project depicts my conceptual ideas for this idea. Overall, I want to highlight the up and to the right trend in the datapoints which clearly depicts a growing problem over time. I've also used size in both charts to depict the size of the fires growing over time. Though utilizing size in dot charts can be problematic as it's hard to decipher scale, I think that in this case it is simply reinforcing the trend that's clearly depicted by the graphic itself. I also included a trend line in one graphic to further drive home the point that wildfires are increasing in size over time. While trend lines are a more complex concept, I think in this visualization it's fairly clear what the line is representing. 

![Wireframe of Data Redesign Concept](https://user-images.githubusercontent.com/97984051/201532717-0601ba85-efed-4592-a314-511f9f78229a.png)

### - Feedback on Redesign Concept
  - I interviewed two women age 25 and age 23. below is their responses synthesized based on common responses.

**Can you tell me what you think this visualization is depicting?**

-	Upward trend over time in acres burned
-	Positive trend
-	Largest fires in the past 40 years have occurred in the last half of the time frame

**What about the visualization leaves you with questions or confuses you?**

-	Legend on second visualization is confusing, “top ten years by acres burned” only red no gray
-	How many colors for “number of fires burned” scale
-	Are there any outliers in the data, UB, LB testing
-	Source of the data

**Can you describe how you think color and scale are being used in this visualization?**

-	Larger and redder indicate greater size/frequency
-	Yellow and grey/smaller indicate lower size/frequency
-	Doesn’t make since to have number of fires depicted in the graph

**Who do you think would care most about the content of this visualization?**

-	Environmental activist groups
-	Increasing size and prevalence of wildfires, population would care more
-	Policy makers
-	Liberal political leaning
-	White people, racial minorities have bigger things to worry about

**Is there anything you wish were included in this visualization that isn’t depicted?**

-	Source of the data
-	Clearer indication in legend
-	Clear indication of geographic bounds of this issue

**Which of the two visualizations do you like more, why?**

-	The one on the right
-	Puts the issue in perspective in a more interesting way, brings up more questions
-	Listing the years on the chart makes it more interesting
-	Graph on left doesn’t tell me anything that I didn’t logically know anyway


### - Final Redesign
  - I incorporated the feedback I received on my wireframed redesign concepts and created the final visualization in Tablaeu. The main changes I've made are simplifying the legend and color usage in the chart. I also added an indicator to the legend for the years which are out of the top ten years in order to more clearly depict the difference between grey and colored dots. I have also decided to remove the scaling on the dots by acres and keep them uniform in size instead. I think this helps to simplify the visualization which makes it easier for the average individual to understand. Because the context for this visualization includes an average individuals living in states effected by wildfires, I wanted to ensure the data was clear and simple.
<div class='tableauPlaceholder' id='viz1668547443563' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fires_data_visualization&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='fires_data_visualization&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fires_data_visualization&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1668547443563');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if (
  divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else {
  vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
