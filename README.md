# Geog458 final essay

### introduction<br/>
   the project I will be analyzing on is [Washington state emergency operations Center Dashboard](https://waseocgis.maps.arcgis.com/apps/MapSeries/index.html?appid=84b17c2a2af8487f97a244b6126834c2). I came across this project when I am looking for data for my final project and it is large and complicated. I think it would be meaningful and interesting to analyze this project. 
   The goal of this project is to provide WA residents or whoever stays in WA state with helpful information about emergencies or daily information like weather or condition of a road. As mentioned earlier, it is a complicated portal and it serves a lot of functions. It has several large sections: 
   - wildfire -include wind and wildfire information and alerts
   - WebEOC Shelters -shows the location of statewild shelters
   - Air Quality -reports air quality of each area of the world
   - WSDOT Traffic alerts map -reports road accessibility(closed or not)
   - WA Department of Health COVID Tracker -shows covid cases in the state
   - John Hopkins COVID-19 -cite to the JHU covid-19 dashboard
   - Earthquake -shows earthquakes of last week, nationwide
   - Flood -reports possible floods
   - Limited English Proficiency -shows the areas in WA with limited english proficiency
   - Weather outlooks -shows the weather of all counties in WA
   - One Stop Shop Traffic -retrieve CCTV data of the road and show detailed information of each segment of road

The map elements that the project employs are scalar bar (only in on stop shop traffic section), legend, and title.
Based on the section it has, this project is suitable for all the people in the world as part of its section provide data of the world, especially on the air quality and covid trackers. For the author of the project, it would be the government of Washington state since it is a government project. However, each subsection has different authors and they belong to different organizations as the dashboard employs their work and combines them to create this dashboard. For example, the covid dashboard that the website employed is made by John Hopskin University.
For this dashboard project, they update their most of data everyday and through different approaches. However, in the english proficiency section, their data is collected at 10.30.2019, Lewis Lujian is the author.

data source:
- wildfire: WA State Parks GIS
- WebEOC Shelters:  Bureau of Land Management
- Air Quality: Department of Ecology via EPA web services
- WSDOT Traffic alerts map: WA State department of transportation
- WA Department of Health COVID Tracker: washington department of health
- John Hopkins COVID-19: John Hopkins University, [their data source list](https://github.com/CSSEGISandData/COVID-19/blob/master/README.md)
- Earthquake: USGS(major data source)
- Flood: National Weather Services(major data source)
- Limited English Proficiency: Limited English Proficiency Coordinator Mitigation & Recovery Section, author: Lewis Lujan
- Weather outlooks: USGS
- One Stop Shop Traffic: Departments of Transportation(major data source)
For the data source, most sections use data from different data source besides the sections that clearly list out their data, it's usually the department of transportation, WA State Parks GIS, Esri, HERE, Garmin, FAO, NOAA, USGS, Bureau of Land Management, EPA, NPS, and Esri. I listed the major data source they collect data from. 


----------
### systematic architecture:




---------

### critique on its overall UI/UX and Web Mapping design.

for the UI, UX and web mapping design, I think they did a good job on trying to make the website simple and fast to use. Since they have quite a few section with large dataset, it has a comparatively user friendly loading time, for individual page too. The website is divided into tabs and each tab contains different maps, which is simple and easy to understand. However, when I first entered the website, I didn't notice the tab on top of the website for a while simply because the content on the first map was already overwhelming. So I think they can add an introduction page (maybe a sidebar panel) where users will first enter, this page can inform the users the basic purpose of the project and the usage of the website. 
Another thing to mention is that even though all sections show information clearly and well, it is quite obvious they have different styles, especially the background color of the sections, some of them are white and others are white or light color. The audience may first notice the change of color instead of the data, so the variations of the background color can be seen as a distracting factor for users. It would be an improvement if the project team could match the background color for all sections. 
What's more, some sections in the project includes data that covers all around the world while others only cover Washington State. So adding a swtich for the audience to switch data between only Washington State and the globe will be a good improvement since it speeds up the loading process. 
Beyound that, the project can also offer audience the link of the section on the page of each section, for example, the John Hopkins Covid dashboard. It gives users options to only focus on the section they are interested in instead of going on this all-in-one project.

