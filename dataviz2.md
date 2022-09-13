# Government Debt Data from the original source, OEDC
The first chart that I would like to show is the bar chart
<iframe src="https://data.oecd.org/chart/6OaZ" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6OaZ" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

<br/>
However, let's see if we decide to present in the line chart, any different?
<iframe src="https://data.oecd.org/chart/6OaQ" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6OaQ" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019 – 2021</a></iframe>

# Government Debt Data Chart 1
With this chart, I use Florish.studio to visualize the Debt-to-GDP ratio for each country from the year 1995 - 2021. 
From the graph, we can see that most of the country have just a slightly increased in the ratio.
However, some of the countries i.e. Greece, Japan, their ratio have gone up significantly througout the year, with approximately ratio of 260 in 2021. 
These countries should be on a look-out radar.

<div class="flourish-embed flourish-chart" data-src="visualisation/11140405"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Government Debt Data chart 2
With this chart but with the same data from the previous chart, I have decide to still keep using the line chart as I think it is the most suitable to use in order to show the trend of the ratio throughout the time period. After seeing the original data, I think that audience might not interest to see all the eyars and countries so I decide to show only the top 10 countries and the average of all countries, from year 2007-2021. The reason that I show from 2007 because it is the year before the financial crisis (2008/2009). 

<br/>
I choose to use the row filter function so we can see each country separately by clicking at the country's name. I use the dots for an easier mapping between year and ratio, and show to value for each dot. As for the y-axis, I have tried to move them to the left but after playing around, I still cannot find a way to undo this. I have also adjust the min-max of the y-axis to align with each countries as I don't think that they have to start the same as we show the graph for each country separately. 

<br/>
I also add the title, and some description about what the ratio means and how the audience can interpret it as some people might not have knowledge about what the debt and gdp represent and it will help with the understanding.

<br/>
Personally, I would like to have all countries show in the same grpah so it is easier to compare. I plan to have the top 3 and the average OECD to be shown in different colors in order to represent each catagory (country) and have the rest of the countries to be in grey. However, I cannot find a way to do it. So this might be the most closest that you could get. Fr

<div class="flourish-embed flourish-chart" data-src="visualisation/11140784"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Government Debt Data chart 3 from Tableau
What if we do it with Tableau Desktop? This one we see the heatmap where below 100 would be blue and above would be orange. The intensity of the colors would be on both end.
<br/>
<div class='tableauPlaceholder' id='viz1663030648274' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP ratio ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-RatioOECD&#47;OECD&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Debt-to-RatioOECD&#47;OECD' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-RatioOECD&#47;OECD&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663030648274');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);  
