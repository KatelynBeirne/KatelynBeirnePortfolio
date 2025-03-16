# Katelyn Beirne's Data Scientist Portfolio

<div align="center">
    <table>
     <tr>
        <td><b>About Me</b></td>
        <td><b>Looking For...</b></td>
     </tr>
     <tr>
       <td>![A professional photo of myself](pngs/m3.PNG)
           I'm graduating from WPI in May, 2025! 
           Outside of work I enjoy reading, hiking, and raising pet shrimp. </td>
        <td>A full time position in the field of Data Science. I'm passionate about GIS, data visualizations, and learning more about different python libraries. </td>
     </tr>
    </table>
    </div>
    
---
## Education &  Skills
**Worcester Polytechnic Institute**, Anticipated 2025 graduation
Bachelor of Science in Data Science, Minor in Computer Science, GPA 3.72

**Programming Languages:** Python, Java, R, SQL, C, C++, 
**Applications:** ArcGIS, Oracle, Github, Flourish, Microsoft Office (Excel, Word, PowerPoint), Adobe Photoshop, VirtualBox, RStudio, Tableau, MATLAB
Data Science Skills: Data visualization, D3 library, spatial optimization, machine learning, predictive modeling, data management, data mining, statistical analysis

## Work Experience
### Research Position - Global Lab Assistant
- Cleaned, visualized, and analyzed waste data from New England's nuclear power stations for the Citizens Awareness Network.
- Created an ArcGIS story map and interactive data visualizations in Flourish.
- Mentored two data science students, resulting in improved, polished products of data visualizations. 

#### Data & Process

I collected data from an online documenting system for a nuclear power station in Massachusetts. First, I developed a script to parse the data from the online pdfs into an excel sheet. Unfortunately, several of the pdfs had data that was rendered incorrectly, so data collection was done manually. 

After organizing and collecting data, I worked with an industry expert to brainstorm creative, but accessible data visualizations. I researched different data visualization methods, and decided on Flourish to create interactive and colorful visualizations.

#### My final work
An interactive timeline map, showing which towns recieved the most nuclear waste shipments over time.
<div class="flourish-embed flourish-map" data-src="visualisation/18677633"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/18677633/thumbnail" width="100%" alt="map visualization" /></noscript></div>

A colorful Sankey diagram, to illustrate flow of shipments from the power station to different towns. 
<div class="flourish-embed flourish-sankey" data-src="visualisation/18510722"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/18510722/thumbnail" width="100%" alt="sankey visualization" /></noscript></div>

A simple, but effective interactive bar chart, allowing viewers to dial down into specific totals by clicking on the key.
<div class="flourish-embed flourish-chart" data-src="visualisation/18527381"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/18527381/thumbnail" width="100%" alt="chart visualization" /></noscript></div>

After responding to feedback and finalizing the visualizations, I created an ArcGIS Storymap in order to display some necessary background and the visualizations for my organization to show on their website. It can be viewed [here](url=https://arcg.is/08vPLu0).

## Projects

### Optimizing Locations for Climate Resilience Interventions
- Determined ideal placements for cool routes using heat map analysis and pedestrian traffic patterns, directly impacting citizens by offering shaded pathways during peak summer heat.
- Researched, analyzed and cleaned datasets, resulting in an interactive map exceeding current state-of-the-art methods.
- Focused on spatial optimization and adapting to climate change with ArcGIS.

#### Here is an example of some of the data I worked with: 

![Raster Data](pngs/temperature.PNG)
![Shade Data](pngs/shade.PNG)

My team's raster data of Worcester's temperature obtained from the Global Lab; and shade data, obtained from ShadeMap. My personal work on this project involved processing this data so it could be used as costs for pathing in ArcGIS. Temperature data was turned into integer format from float, then combined with Shade Data via the raster calculator tool. From there, our new cost raster was turned into a polygon layer so as to access the attribute table. 

#### Process

There was a lot of useful trial and error throughout this project. The best example of my learning process throughout is how we picked the tool we would use. There were several options in ArcGIS, and I decided which tool would be best to use; the route analysis tool with polygon costs. An issue we ran into early on was that the pathing data was too information heavy to correctly run a route analysis. A solution I proposed involved creating our own network dataset of Worcester sidewalks, instead of using ArcGIS' default network. After proposing to my team, we worked through the issue together and were able to create our final prototype. 

#### Our final prototype

After working with our front and backend developer, our team finalized our prototype for cool routes in Worcester. We are looking forward to adding a way to add potential locations for street tree planting. 
![Final Website](pngs/FinalProduct.PNG)

### Data in D3: Exploring Housing After Graduation

Working in a team of 4, I helped choose data for analysis, synthesize a question/purpose, and create data visualizations in order to see where we could live after graduation. Our final product was 4 data visualizations on a website, in addition a 2 minute recording I narrated talking through our design. 
Throughout our work we kept a detailed process book. This included drafts of data visualizations and how we worked through any challenges as a team. Here is some of my progress, as well as a [link](https://katelynbeirne.github.io/D3ProjectForPortfolio/) to the Github pages for our data visulizations. 

![Visualization Prototypes](pngs/VisualizationSketches.PNG)
![Housing Graph](pngs/Housing.PNG)




### Horse Genetics Excel Project
 - A personal project to create a creative excel sheet. [WIP]
