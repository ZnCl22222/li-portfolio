### Back to Home Page: [Home Page](/README.md)

# Original Visualization
Gender wage gap for the most common occupations for women in the United States in 2021, by median weekly earnings
https://www.statista.com/statistics/244096/us-gender-wage-gap-for-the-20-most-common-occupations-for-women/

I chose this visualization because I am personally interested in gender issues, especially in quantifiable gender inequality in the context of the labor economy. I am also currently conducting a research project on the reasons for the decline in the labor force of immigrant women before and after the epidemic through IPUMPS census and survey data. I was trying to find a visualization related to gender issues on the statista and came across this title, Gender Wage Gap. However, when I clicked on the visualization I found that it only listed the wage of men and women, with no way to get the information I was looking for such as the occupations with the largest gender differences. I thought there was a lot of room for revision in this visualization, so I chose this one. Source data include median weekly earning of the two gender group in most common occupations.

# Critique the Data Visualization
From the Stephen Few's methodology, we were able to re-evaluate this visualization in two major aspects and seven minor aspects.
- Informative
  - Usefulness
  - Completeness
  - Perceptibility
  - Truthfulness
  - Intuitiveness
- Emotive
  - Aesthetics
  - Engagement

According to our criticize, the intuitiveness, truthfulness, and completeness of the original visualization are already well done, and we need to improve mainly in other areas:
- Usefulness: In order to increase the usefulness of the data, we decided to get the data on women's income as percentage of men's income from the original data, which can be more intuitive for the audience to recognize the difference between women's and men's income.
- Perceptibility: In order to make it easier for the audience to compare the magnitude of gender differences between occupations, we chose to rank the data in order of the magnitude of gender differences, from largest to smallest.
- Aesthetics: I will use contrasting colors to label males and females, as well as using gray to reflect the difference between male and female wages.
- Engagement: I will display a summary line of text or number somewhere in the visualization to achieve the interaction with the user and enhance the user experience. The user only needs to select a certain occupation to get information about the difference in salary between men and women and the specific salary of that occupation.

# Sketch out a solution
![IMG_4453](https://user-images.githubusercontent.com/100179117/202339988-f6dca6a2-1ba9-4b80-8fab-5e691cfe42e9.jpg)

Here are the changes I made：
- Derive new variable from the original data and visualize the new variable
- Sort by magnitude of gender gap
- Change colors
- Add a summary session to better inform audience

# Test the solution
I shared my sketch with three classmates and received the following comments:
- Solid lines can be added in the blanks to represent the part that has been achieved, in contrast to the gap represented by the gray part.
- The title is a bit too long, can be changed to a shorter one.
- Rethink about the form of the pop-up box, or perhaps just change it to a one-sentence summary.

# Learn from feedback
- Change to a short and clear title
- Add a summary line at the beginning so that the audience can figure out what I'm trying to convey with minimal effort
- Adding a solid line is a good suggestion as well, but I have not done so for now due to the difficulty in implementing it in tableau

I chose a very different way of presenting the same data than the original. Before re-visualizing, I changed the data to be presented, turning the median wage for men and women into women's wage as a percentage of men's. I then used red dots for women, blue dots for men, and gray areas for the gender wage gap. I then sorted the occupations from largest to smallest based on the size of the difference. Finally I added an interactive element where viewers could select any occupation and get a one-line summary to maximize user engagement.

# Final data visualization
<div class='tableauPlaceholder' id='viz1668653247386' style='position: relative'><noscript><a href='#'><img alt='仪表板 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;Genderwagegap_16686532358570&#47;1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Genderwagegap_16686532358570&#47;1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ge&#47;Genderwagegap_16686532358570&#47;1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1668653247386');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1301px';vizElement.style.height='779px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1301px';vizElement.style.height='779px';} 
  else { vizElement.style.width='100%';vizElement.style.height='1327px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
