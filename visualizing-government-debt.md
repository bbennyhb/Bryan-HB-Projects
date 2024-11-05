[Home Page](https://bbennyhb.github.io/Bryan-HB-Projects/) | [Visualizing Government Debt](visualizing-government-debt) | [Columns](https://www.dailycal.org/users/profile/bryan%20hernandez%20benitez/) 

# Visualizing Government Debt Across Countries

The following visualizations track government debt.

## Part one: Working with web-based visualization tools and data

Original image from the OCED platform. 

![OCED Image](image.jpg) 

## Working with Tableau

Heatmap showing GDP to Debt Ratio across years.

<div class='tableauPlaceholder' id='viz1730767891278' style='position: relative'><noscript><a href='#'><img alt='GDP to Debt Ratio (1995 - 2019)Since 1999, Japan has had the highest average GDP to Debt ratio.Source: Organization for Economic Co-operation and Development, 2024 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;HeatmapGDPtoDebt&#47;HeatmapGDPtoDebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HeatmapGDPtoDebt&#47;HeatmapGDPtoDebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;He&#47;HeatmapGDPtoDebt&#47;HeatmapGDPtoDebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730767891278');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Part three: create your own visualization

Visualization 1 was taken directly from the Organization for Economic Co-Operation and Development (OCED). While this visualization provides a decent overview of how countries compare to one another, it doesn't provide viewers with direct percentages by country. In contrast, the heatmap (visualization 2) does a much better job of giving side-by-side country comparisons that allow us to compare direct ratios while maintaining an interactive aspect—as shown with the year-by-year changes. 

While these initial visualizations hold well in providing information, they lack in guiding decision-makers. In essence, there's no "so what?" aspect to visualizations 1 and 2. As such, the following visualization hones in on data retrieved from Canvas. While more countries and their respective GDP-to-Debt ratios were included in the dataset, I felt it would be more impactful to draw attention to a subset of that data, one that focuses on member nations of the European Union. By creating a map of these EU members, we're better able to understand how a key region of the world is doing. Furthermore, the visualization uses external research obtained from the World Bank (2010) to qualify a "good" versus "bad" ratio. 

As such, this visualization uses diverging colors (grey and red) in which countries at or under a good ratio threshold (77.1 percent) are shaded in grey, whereas countries above that threshold are marked in red. More information and analysis can be found in the visualization below.

<div class='tableauPlaceholder' id='viz1730767979487' style='position: relative'><noscript><a href='#'><img alt='Debt to GDP Ratio of member states of the European Union (2017)Using a threshold of 77.1 percent, if debt surpasses this percent, &quot;each additional percentage point ... costs the economy 0.174 percentage points in annual average growth. ... Below this thr ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;EU&#47;EUMemberStatesDebttoGDP&#47;EUMemberStates2017&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='EUMemberStatesDebttoGDP&#47;EUMemberStates2017' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;EU&#47;EUMemberStatesDebttoGDP&#47;EUMemberStates2017&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730767979487');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


_Sources: Organization for Economic Co-Operation and Development, World Bank (2010)_


