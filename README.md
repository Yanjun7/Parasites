## Project 2: Giardiasis (Giardia Infection)
By Melinda Wiley, Patricia Escalante, Yanjun Zhou
<br>
The George Washington University Data Analytics and Data Visualization Boot Camp
04 January 2019
<br>
<p align="center">
<img width="461" alt="giardia1" src="https://user-images.githubusercontent.com/41865917/50729052-2e3e8700-1101-11e9-8c32-db152d1b875e.PNG">
<img width="228" alt="giardia2" src="https://user-images.githubusercontent.com/41865917/50729053-2e3e8700-1101-11e9-90ed-cccb0fa40fe3.PNG">
<img width="334" alt="giardia3" src="https://user-images.githubusercontent.com/41865917/50729054-2e3e8700-1101-11e9-807a-65a3d0cfb194.PNG">
<img width="245" alt="giardia4" src="https://user-images.githubusercontent.com/41865917/50729055-2e3e8700-1101-11e9-958d-a9dedf12bbab.PNG">

</p>

<br>
Project 2 Giardia Infection cases reported by the CDC between 2014 and 2018. This project utilizes HTML/CSS, JS, two datasets and user-driver interactions. Data munging and data visualization utilizing CDC provided dataset on Giardiasis (Giardia) from the National Notifiable Diseases Surveillance System (NNDSS). Along with data information on state population. We narrowed the field to this disease caused by parasites to focus on building out our site with a more manageable dataset. Giardia csv and US population by State csv will be read into a SQL database. We will scrape the index from https://www.cdc.gov/parasites/az/index.html#s to pull the list of parasites; working these aspects in jupyter notebook with BeautifulSoup. <br>

Initial layout will include US maps, chart, and possibly some links to the CDC site for more information. The visualizations will show infection cases over the years through mapping and a bar/bubble/line chart with some rad transitions. The 1 JS library not previously covered everpolate.browserified.min. <br>

Resources: https://www.cdc.gov/parasites/az/index.html#s, https://data.cdc.gov, https://www.cdc.gov/parasites/giardia/index.html; 
https://www.census.gov/topics/population.html <br>

Topic: Giardiasis (Giardia Infection)Dataset: National Notifiable Diseases Surveillance System (NNDSS)<br>
Git repo: https://github.com/Yanjun7/Parasites <br>
JS Library: everpolate.browserified.min<br>

Design: <br>
•	Home page: informational page<br>
•	Chart drop down links with D3 charting with transitions and interactions <br>
o	Line charts with transitions on raw data, per capita data, and regional data
	X=time; y=# of Infections<br>
o	Bubble chart over time (2014-2018) x=giardia infection cases, y= giardia infection cases/population



    

