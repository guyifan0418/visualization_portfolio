# visualization_portfolio
Yifan's data visualization portfolio.

# About me
Hello! I’m Yifan Gu, a Master’s candidate in Information Systems Management at Carnegie Mellon University with a background in Finance and Data Science from NYU Stern. My journey intersects technology, business, and social impact, and I’m particularly interested in how data can drive innovative solutions across industries. Over time, I’ve developed a strong foundation in programming with Python, Java, SQL, and R, alongside skills in financial forecasting, business valuation, and model interpretation. My professional experiences, ranging from nonprofit consulting to roles in operations and data science, have equipped me with diverse, practical insights. Now, I’m excited to showcase my data visualization work and analytical projects that reflect my commitment to unraveling complex patterns and translating them into actionable strategies.

# What I hope to learn
Through this portfolio, I aim to deepen my proficiency in data visualization and storytelling. I value the clarity that comes with well-designed visualizations and strive to present data in ways that highlight trends, patterns, and outliers effectively. I hope to build a stronger understanding of how visualizations can reveal societal and economic shifts over time, contributing to data-driven insights that support real-world decision-making. As I advance in my career, I am keen on exploring the ethical implications of data usage and learning more about balancing accuracy with interpretability. Ultimately, I seek to create visualizations that engage, inform, and inspire.

# Portfolio
Welcome to my portfolio of data visualizations! Here, you’ll find a collection of projects spanning various industries, each designed with the intention of distilling complex datasets into clear, compelling visuals. My approach to data visualization involves a blend of exploratory analysis and narrative design, as I aim to uncover initial insights and then dive deeper to discover subtleties within the data. This portfolio reflects my interest in exploring societal trends, economic well-being, and the nuanced stories that data can tell. Whether you’re interested in financial analysis, business intelligence, or social impact, I hope you find value and insight in these projects.
## Assignment: Visualizing Government Debt

<div class='tableauPlaceholder' id='viz1730754336832' style='position: relative'><noscript><a href='#'><img alt='&lt;General Government Debt&gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovDebt&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OECDGovDebt&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovDebt&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730754336832');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Description:
This box plot shows the annual distribution of government debt as a percentage of GDP across various countries from 1995 to 2019. Each box represents the interquartile range (IQR) of debt-to-GDP ratios for a given year, with the median indicated by a bold line within the box. Points outside the whiskers are outliers, showing countries with exceptionally high or low debt ratios in specific years. This visualization helps identify trends, such as the increasing variation in debt ratios over time and notable outliers in recent years.

<div class='tableauPlaceholder' id='viz1730758016112' style='position: relative'><noscript><a href='#'><img alt='&lt;Boxplot of Gov Debt&gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovDebt&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OECDGovDebt&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECDGovDebt&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730758016112');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Reflection on Visualizations: Government Debt Analysis
The **first visualization**, a bar chart, was ideal for comparing government debt levels across countries at a specific point in time. It is very intuitive and easy to understand because it uses a chart viewers are very familiar with (bar chart) and offers limited information. The **second visualization**, a heat map, was more dynamic, offering an overview of debt ratios by country and year. The color gradient made it easy to spot years and countries with exceptionally high or low debt-to-GDP ratios. However, the heat map was limited in showing the distribution within each year—it didn't capture the variability of debt levels across countries.

For the **third visualization**, I chose a box plot because it highlights the annual distribution of debt-to-GDP ratios. With this visualization, we an easily compare countries in different years. Unlike the previous visualizations, the box plot captures both central tendency and variation within each year. It shows outliers and helps viewers understand the range of debt ratios. This visualization tells a story about the spread and variability of debt across countries, revealing how the financial crisis and subsequent years saw widening disparities in debt levels. The box plot thus provides a layered perspective, showing not only the trend over time but also the variability within each year. In this visualization, I used a red palette, because red is often associated with negative interpretations, which suits the context of debt. I used a dark red color for outliers so it naturally draws attention. The median line within each box was also highlighted with a color contrast.

**Data Source**: The data used in this analysis was sourced from OECD. (https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2023)

## Assignment 3&4: Critique by Design
## Final project
