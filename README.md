## Modeling students on the UNC-CH campus for fall 2020 restart scenarios
### By Andrew Maxwell and Davis Brown

<img src="images/geographic_slice.png" alt="Campus model">

Adapting classrooms and course schedules to properly offer social distancing is crucial to bringing university students back to the campus. On May 21, UNC - Chapel Hill Chancellor Kevin Guskiewicz announced the University’s roadmap plan for the fall 2020 semester. Responding to the COVID-19 pandemic, this plan detailed sweeping changes made to UNC classrooms to promote safe environments for all students. Our aim with this analysis was to offer insight into how changing course schedules may impact the number of student-to-student interactions on campus. 

Maintaining social distance between individuals is essential to reducing the spread of the COVID-19 virus. [^1] [^2] We have used some of the changes suggested by the Chancellor Guskiewicz and other university systems to anticipate possible scenarios. We examine three different scenarios: 

1. Limit classes to only those with 50 students or less. There were 370 courses offered with over 50 students in Fall 2019. To limit student-to-student interactions and mitigate the exponential spread of COVID-19, we consider a scenario where these classes are held online.
2. Limit classes to only those with 100 students or less. We consider a scenario where the 178 courses offered with over 100 students are held online. 
3. Reorganize the overall class schedule to offer more weeknight classes. We sample 1/4 of the courses offered during the campus population peak hours between 11am - 3pm and move them to either a later time (between 5pm and 8pm) or to an earlier time (8 am) to reduce the density of students on campus. 

Our model provides insight on how each proposed change would impact the total number of students on campus. We consider the student density within the Chapel Hill campus. Below is a geospatial plot of students on campus throughout the week (press the triangle pointing right to play the animation through a week of courses). We offer the option of ‘layering’ restart scenarios: for example, you can view the student density on campus where classes are limited to 50 students or less, or where there are more weeknight courses offered, or where both classes are limited to 50 students AND more weeknight courses are offered. The total students in class on campus at a given time is in the plot header.


<body>
 <style>
  html, body { height: 100% }
</style>
 <div class='tableauPlaceholder' id='viz1590979367731' style='position: relative'><noscript><a href='#'>
  <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CoursesTableau_v2&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a>
  </noscript>
  <object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> 
   <param name='site_root' value='' />
   <param name='name' value='CoursesTableau_v2&#47;Dashboard1' />
   <param name='tabs' value='no' />
   <param name='toolbar' value='yes' />
   <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;CoursesTableau_v2&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    
 var divElement = document.getElementById('viz1590979367731');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
 else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} 
 else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
 </script>
 </body>

<p>&nbsp;</p>

We observe large clusters of students at peak hours. These clusters are mostly concentrated in the buildings between Cameron Ave and South Rd. As noted, this high population density creates more student-to-student interactions and fosters exponential spread of COVID-19. By limiting class size to 50 and extended class hours, we are able to reduce the on-campus population in this area from over 9400 students to less than 3600, limiting potential virus transmissions. Some other relevant COVID-19 related issues may arise from these dense clusters of students: 
* reroutes of student paths to avoid overcrowding, 
* cleaning of building entrances and facilities, and
* limiting students stopping-off in cafeterias, libraries, and recreational spaces.
Reducing students on campus may limit the risk of these issues but will not curb them completely. We are investigating classroom utilization across campus and how to optimize classroom space to reduce clustering. This analysis will be added to the bottom of this site when completed. 

In the next graphic, we note the consistent decrease of student population densities under the scenarios. Namely, within peak times of 11am - 3pm, we notice a decrease of student population on campus by over 5,000 students. With the most aggressive change to class schedules, we observe at least one instance on Monday - Thursday of a greater than 10,000 student decrease in campus population (e.g. Tuesday at 12pm). This may mitigate the exponential spread of COVID-19. The potential for student-to-student spread is lessened as class times are either spread out or the classes with the greatest potential to enable spread are moved online. We graph the total student population on the UNC-CH campus under different strategies or combinations of strategies below. The plot allows direct comparison of the total student population on campus with a chosen strategy. Each proposed change to the course schedule can be compared on an hour to hour basis for each day of the week. We highlight the standard course hours in blue and the extended course hours (later hours for weeknights) in yellow.


<body>
 <style>
  html, body { height: 100% }
</style>
<div class='tableauPlaceholder' id='viz1591210149499' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimePeakReduction&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TimePeakReduction&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ti&#47;TimePeakReduction&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1591210149499');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>

<p>&nbsp;</p>

The next graphic displays the scenarios in a similar manner but replaces time with buildings. This graphic is a snapshot of the peak campus population, on Tuesday at 12pm. In the scenarios limiting classes to under 50 students, certain buildings with large lecture halls experience major decreases in population such as Genome Sciences, Phillips Hall, and Chapman Hall. On the other hand, Dey Hall and Peabody Hall remain relatively unchanged, suggesting they have many classes with under 50 individuals. By moving large lecture classes online, these large classrooms could be used to adequately social distance students for in-person lectures. 

<body>
 <style>
  html, body { height: 100% }
</style>
 <div class='tableauPlaceholder' id='viz1591210710345' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bu&#47;BuildingPeakReductions&#47;Dash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BuildingPeakReductions&#47;Dash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bu&#47;BuildingPeakReductions&#47;Dash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1591210710345');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>

<p>&nbsp;</p>

Finally, we consider how many open and filled (‘used’) seats each building on campus has during the course week. We call the building’s open seats and used seats the ‘utilization’ of the building. Utilization describes student density in a building at the per seat level. This gives us more information about the potential for student-to-student interaction than student density per building alone, as we can now graphically consider how tightly packed students are in the classroom. We can also make better decisions about where to allocate students on campus. 


For example, in the utilization graphic below, the Genome Sciences Building has 846 used seats and 29 open seats on a Tuesday at 12:00 pm. When we implement a layered strategy of extended night hours during the weeknight and also limiting classes to less than 50 students, we notice that Genome now has only 149 used seats and 726 open seats. This suggests that our intervention is effective at the per seat level. Importantly, it also suggests a further strategy: we can move other classes (from, e.g. Phillips Hall, which has 356 used seats) on campus to some of the empty seats in Genome, and still have reasonably low student-to-student interactions given the utilization rate of the building. 


<body>
 <style>
  html, body { height: 100% }
</style>
<div class='tableauPlaceholder' id='viz1591364337921' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ut&#47;Utilization_v2&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Utilization_v2&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ut&#47;Utilization_v2&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1591364337921');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>

## Takeaways 
We use changes to the UNC-CH course schedule to decrease the possibility of student-to-student COVID-19 spread in the classroom. We consider three strategies to mitigate in-class interactions: by limiting class sizes to <50 or <100 students, and extending course hours till 8 pm, as well as layered combinations of these strategies. We find a decrease of campus student population density with all strategies. The most significant decrease of student density on campus occurs with the layer extending class hours with the strategy of moving classes with over 50 students online. 

Further work will consider network analysis of student-to-student spread in UNC-CH classrooms, and how these strategies may mitigate this spread. 


## Methods
We use UNC Chapel Hill course enrollment data from fall 2019 provided by the [Office of the University Registrar](https://registrar.unc.edu/files/2019/03/2199-SSB-3-4-19.pdf). 

For the two strategies that limit course sizes over 50 or 100 students, we remove these courses from the course schedule and assume they are held online. For the extension of course hours to add weeknight classes, we sample between peak student density hours of 11:00am to 3:00pm. Conditional on the course being less than 1.5 hours, we randomly sample 1/4 of these courses. If the sampled course starts at 11:00 am, we move the course to 8:00 am. For other sampled courses, we add 5 hours to its time, so a course that originally started at 2:00 pm and ended at 2:50 pm will now start at 7:00 pm and end at 7:50 pm. 

We use Tableau and pandas for the data analysis and visualization. 



[^1]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7118670/
[^2]: https://wwwnc.cdc.gov/eid/article/26/8/20-1093_article


