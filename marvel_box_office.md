# Assignment 3&4: Critique by Design

## Original Visualization
[Link to Original Visualization](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)

## Critique and Analysis
In this project, I selected the "Which is the Best Performing Marvel Movie?" visualization for redesign. I chose this visualization because it covers a popular and engaging topic: the performance of Marvel movies. The original visualization was visually appealing and interactive, but it had some areas for improvement. Specifically, the use of multiple metrics and a complex color scheme made it difficult for viewers to quickly interpret the data. I aimed to redesign it to make the information clearer, enhance the user experience, and provide a better narrative flow.

## Redesign Process
### Critique Using Stephen Few’s Method
One standout feature of the visualization is its use of interactive elements and thematic branding. The inclusion of movie posters and recognizable Marvel icons makes the visualization engaging for fans and eye-catching for a more general audience as well. Tooltips and filters enhance the exploration experience, enabling users to delve into specific data points. The effective use of color makes it easy to distinguish high-performing films from those that underperformed.

However, the visualization’s comprehensiveness leads to complexity. Those unfamiliar with specific industry terms like “budget recovery percentage” or “weekend drop-off rate” might find it confusing. Additionally, the emphasis on aesthetics, such as the use of movie posters, sometimes makes it even harder to understand. I would simplifying the display of metrics by breaking it up into different charts. Instead of using a scatterplot, I might use more intuitive charts like bar chart. Furthermore, adding a brief legend or explanatory text for complex metrics would increase accessibility, especially for users who may not be familiar with the nuances of box office analysis.

The main audiences are Marvel fans, movie enthusiasts, and industry analysts. It is designed for casual viewers who are curious about how different Marvel movies performed in theaters and what critics thought of them. At the same time, it also targets people interested in movie industry trends, such as analysts or entertainment journalists, who want to see detailed metrics like budget recovery and audience scores.

Overall, this visualization is effective in reaching its intended audience because it is both engaging and informative. For Marvel fans and casual viewers, the use of familiar movie posters and colorful visuals makes the data fun to look at. The design helps them quickly find movies they recognize and see how well they performed. The interactive features, like hovering over data points for more information, keep the experience interesting and easy to follow. For data enthusiasts and industry analysts, the tool offers a deeper level of insight. It goes beyond simple box office numbers by including detailed metrics like the percentage of the budget recovered and the drop-off in ticket sales after the first weekend. These details allow users who are interested in the business side of movies to explore the data more thoroughly and understand what factors contributed to a movie’s success or failure.

### Wireframe and User Feedback
I began by sketching a wireframe for the redesign, focusing on three main metrics: Budget Recovery Percentage, Audience Score, and Critics’ Score. I created two visualizations:
- A bar chart showing the Budget Recovery Percentage for each movie.
- A scatter plot comparing Audience Scores and Critics’ Scores.

I shared the wireframe with two people for feedback:
1. Student, mid 20s: They appreciated the redesign, especially the focus on the Budget Recovery Rate as a key metric. They mentioned that highlighting the budget recovery percentage helps viewers quickly understand how successful each movie was in terms of profitability. The idea of using a bar chart for this metric made it easier for them to compare movies side by side. They suggested including an explanation on how to interpret budget recovery percentage.
2. Student, mid 20s: They appreciated the overall consistency and simplicity of the design. They liked that the visualization clearly displayed the key metrics (Budget Recovery, Audience Score, and Critics’ Score) without being cluttered. However, they suggested using a matching color scheme for both the bar chart and scatter plot to maintain visual consistency throughout the dashboard. They also recommended limiting the number of reference lines, as having too many could confuse viewers. Student 2 felt that using only one or two key reference lines would be more effective and less distracting.
 
### Final Design
Based on this feedback, I made the following changes:
- Color Palette: I chose a consistent color palette for both charts to help users easily see consistency.
- Labeling: I increased a textbox explaining what budget recovery percentage means, improving readability.
- Reference Lines: I added a reference line at 250% on the bar chart to indicate the break-even point, removing extra reference lines.

## Final Visualization
<div class='tableauPlaceholder' id='viz1731625531642' style='position: relative'><noscript><a href='#'><img alt='Marvel Movie Box Office and Audience Insights ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MarvelMovieBoxOfficeandAudienceInsights&#47;MarvelMovieBoxOfficeandAudienceInsights&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MarvelMovieBoxOfficeandAudienceInsights&#47;MarvelMovieBoxOfficeandAudienceInsights' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MarvelMovieBoxOfficeandAudienceInsights&#47;MarvelMovieBoxOfficeandAudienceInsights&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731625531642');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='827px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Summary
The redesigned visualization provides a clearer and more user-friendly experience by simplifying the layout and enhancing color consistency. It effectively communicates key metrics, such as budget recovery and audience scores, in a format that is accessible to a wider audience.
Data Source: Information is Beautiful. “Which is the Best Performing Marvel Movie?”
https://public.tableau.com/app/profile/yifan.gu6974/viz/MarvelMovieBoxOfficeandAudienceInsights/MarvelMovieBoxOfficeandAudienceInsights?publish=yes
