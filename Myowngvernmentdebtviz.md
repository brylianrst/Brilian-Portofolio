| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) | [Part 1: Working with web-based visualization tools and data](https://brylianrst.github.io/Brilian-Portofolio/governmentdebtviz.html) | [Part 2: Working with Tableau](https://brylianrst.github.io/Brilian-Portofolio/Governmentdebthighlightviz.html) | [Part 3: Create your own visualization](https://brylianrst.github.io/Brilian-Portofolio/Myowngvernmentdebtviz.html)


<div class='tableauPlaceholder' id='viz1706578770862' style='position: relative'><noscript><a href='#'><img alt='Myowngovernmentdebtvizsource : https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htmBrief Explanation : The visualization portrays the government debt average values from each countries in the descending order, i try to make it like that so the audi ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;My&#47;Myowngovernmentdebtviz&#47;Governmentdebtviz2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Myowngovernmentdebtviz&#47;Governmentdebtviz2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;My&#47;Myowngovernmentdebtviz&#47;Governmentdebtviz2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1706578770862');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Explanation of my own government debt visualization

Source of data : https://data.oecd.org/gga/general-government-debt.htm

In my own revised government debt visualization, I've adopted a side-by-side bars approach, deviating from the previous task that utilized a highlight/heatmap visualization. 
I've also adjusted the variables, shifting from using "Year" (time) as columns, "Location" as rows, and two instances of "sum(value)" as marks, to now organizing the data with "Location" and "sum(value)" as columns,
and "Year" (time) as rows with marks. This restructuring aims to accentuate the depiction of government debt average values across countries, arranged in descending order. 
By presenting the data in this manner, it becomes visually evident that Japan holds the highest government debt average, while Estonia boasts the lowest. This new visualization not only facilitates a straightforward comparison of average values between countries but also enhances audience navigation by incorporating colored labels based on years, providing an intuitive means for viewers to explore specific timeframes.
