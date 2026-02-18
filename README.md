## Tableau_Hands-on_Project
#### Minnesota Traffic Analysis 
Dashboard for Minnesota Department of Transportation to help their team monitor traffic patterns.

#### Goal is to learn more about: 
- Traffic volume throughout the year; ideally organized by year, month, week, day, and hour
- Traffic volume in different weather conditions
- Traffic volume on different holidays
  
*Knowing traffic patterns under these conditions will help the team make important infrastructure decisions. These decisions will ensure that any construction in the future won’t cause problems for drivers.* 

I explored how BI professional work with stakeholders in an actual business environment to respond to their needs through project lifecycle.

#### Data source:

Cleaned and organized data in a .csv file from Minnesota Department of Transportation

#### Team collaboration:
Throughout the project I received email correspondence from my supervisors and team members with helpful information, tips, and strategies for completing the project deliverables.

**First Email:** Supervisor-Chart design

He shared some insights that might help me make some decisions for the project
They have been specific about the three charts they’re most interested in including for this dashboard:
- Traffic volume throughout the year; ideally organized by year, month, week, day, and hour
- Traffic volume in different weather conditions
- Traffic volume on different holidays

He shared some few specific columns that would be a good stating pace for what data to include: *date_time, traffic_volume, weather_main, and holiday.*
He also shared that I may need to create custom columns and filters to the dataset in order to get the metrics I needed. 
I had the flexibility to work on the project in a way that will make me feel comfortable. The team shared with me some chart ideas although they knew I had my ideas too. 

**Second Email:** Team supervisor-Dashboard organization

He suggested I could add some tooltips or captions to give more details to the user when they hover over a mark in the current view.

He also shared with me some key guidance as I work through my design process:
- Considering the business question and stakeholder needs
- Organizing my process with design thinking
- Avoid misleading or deceptive charts
- Prioritize accessibility
- Apply design principles

#### Dashboard
Dashboard features four charts and two legends.

![Dashboard](images/Menasota_Dashboard.png)

- These charts include **Traffic volumes by month per year**, **Traffic volumes by hour of the day**, **Traffic volumes organized by weather patterns**, and a **circle chart for Holidays with highest traffic**. 
Together, these charts address my stakeholders’ main interests: *comparing the traffic volume at different points in time and at different timescales, and examining holiday and weather patterns throughout the year.* 

- The legend specifies a separate color for each of the three years and traffic volume by day/hour represented in the data.
   
- This visualization uses **only three years** of llatest data in order to prioritize simplicity. If these charts featured data from all of the years, there would be too many lines and bars in the chart. This would make it much harder to read, and therefore much less effective as a visualization.
     
- In this dashboard, the line chart is placed at the top, alongside the legend. Since the legend applies to each of the charts, it’s important to place it at the top of the visualization.
   
- Beneath the line chart, there is a bar chart representing **weather patterns** and a circle chart representing **national holidays** in the United States. These charts have lower priority than the line chart, so they are placed lower in the dashboard. I also added a reference line to my bar chart to aid reading.
  
- Next to the three charts is a heat map representing the traffic volumes by hours of the day. Because a large amount of data is being visualized at once, this chart is larger than the others so stakeholders can view the data more easily.
  
- The **line chart** and **heat map** represent two of the timescales in which the stakeholder is most interested: the monthly timescale and the weekly timescale. In these charts, my stakeholders can view which months and days of the week have the highest traffic volume.
  
- You can also find other trends: based on the line chart, it seems like the traffic volume for 2017 was generally higher than in 2016.

- On top right corner of the dashboard I added a downloading buttom that can help users download to share or print dashboard and in the top left is a filter buttom.

 **Note:**  *In order to make this dashboard user friendly and updated, it will periodically be iterated*
