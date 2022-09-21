# Critique by Design
## Step One
![Initial Visualization](https://www.statisticshowto.com/wp-content/uploads/2014/01/wii-floundering.png)

After a lot of searching I found the following image which described the active user percentage of each of th primary consoles in 2009 by month over a 6-month period. This visualization looked perfect for critique for a variety reasons, and the data was luckily accessible in a PDF of a Nielsen Report.

## Step Two

This visualization seemed perfect to me because it fell flat in many departments including truthfulness, engagement and usefulness. A lot of the failure in these departments is due to the misrepresentation of the data. See, even though the data provided active user percentage, it did not calculate consoles owned at the time. Therefore, the Nintendo Wii appears very underperforming, but it is on par with the other new consoles.

In addition to data misrepresentation, the axes could both use work. The x-axis used 2009 in every month tick unnecessarily and the y-axis starts at 5%. Finally, the color scheme for each console line had no correlation and just appeared to try and contrast from each other as much as possible. These problems could be fixed.

## Step Three
The next step would be to sketch out potential redesigns now that I have recognized the flaws. I decided to sketch two options:

1. A line graph with adjusted color scheme and axes
2. A bar graph with adjusted color scheme, axes, as well as an adjusted y-value set that factors consoles owned as well as usage percentage

<img width="468" alt="image" src="https://user-images.githubusercontent.com/112968634/191404000-f442d737-9bd5-4d28-86c6-a49ed0befd0f.png">

These sketches allowed me to play with both old and new y-values and see what story is told by each. It appeared to me that the bar graph told a better story. More specifically, it told me that “PS2 is being played way more than PS3 (Sony’s next generation console). This is uncharacteristic of the average relationship between old and next generation consoles (Nintendo and Microsoft’s consoles follow this relationship)”

## Step Four

After sketching two rough ideas for how to redesign, I wanted to put them to the test.

I prepared and asked the following questions to two individuals. A female student in her mid-20s and a male adult in his mid-60s

I captured most of their feedback below:

![image](https://user-images.githubusercontent.com/112968634/191387887-5420f6d6-e13a-4e28-87f7-1970c96b6db3.png)

After assessing their feedback, it seems like they both had more unique grievances. For instance, the adult was more concerned about the colors being used for a purpose while the student wanted more clarity on the axes. However, it seems that there was a general consensus that the bar chart was much more clear and actually told a story.

## Step Five

Therefore, I decided to go ahead with the bar chart. I added additional edits that were suggested such as:

* Clearer y-axis
* Clearer title
* Color scheme that highlighted Old vs. New consoles

I then ended up with this draft on Tableau (press full screen for a more clear picture):

### Final Draft Before Class
<div class='tableauPlaceholder' id='viz1663717999841' style='position: relative'><noscript><a href='#'><img alt='Average consoles used in 2009 by Company and Generation ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft34&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Draft34&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Dr&#47;Draft34&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663717999841');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I brought these sketches to my group mates in class and they were very pleased with the route I chose to take. There is always room for improvement, so they helped me with the following:

* Giving a clearer title that explained my goal for my audience
* Flipping the graph to show horizontal axis title more clearly
* Simplifying tick marks on the x axis

After all this I ended with the final product:

### Final Visualization
<div class='tableauPlaceholder' id='viz1663717503843' style='position: relative'><noscript><a href='#'><img alt='How many are playing Older consoles vs. Newer? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_16637153629070&#47;Final&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34_16637153629070&#47;Final' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_16637153629070&#47;Final&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663717503843');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I am very pleased with this visualization. I believe it tells a story, and greatly improved upon the original design.
