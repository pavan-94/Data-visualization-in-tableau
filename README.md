# Data-visualization-in-tableau
Data Set:
Global Historical Tsunami Database
Citation:   National Geophysical Data Center / World Data Service: NCEI/WDS Global Historical Tsunami Database. NOAA National Centers for Environmental Information. https://www.ngdc.noaa.gov/hazard/tsu_db.shtml

Data Description:
The Global historical Tsunami Database provides details of about 2,400 tsunamis from 2000 BC till date. The database consists of two files. The first file consists of details on the source of tsunami such as the year in which first ever tsunami was observed, where it originated, its location, different causes for tsunami, maximum wavelength recorded, total deaths and injuries and total damage estimate in dollars at the source location. The second file consist of details on runups. The large amount of water that a tsunami pushes onto the shore above the regular sea level is called Run-up, that is the maximum vertical height onshore above sea level reached by a tsunami. Run-up is the more damaging force than the huge tsunami waves as it surges inland and destroys all in its path. This file consists of details such as location names where the tsunami hit the run-up location via different measures eyewitnesses, reconnaissance surveys, tide gauges, and deep-ocean sensors. Maximum water height and inundation distance for specific runup location.   


The main motive of this visualization is to help scientist predict more accurately the occurrence of tsunami and identify the cities or countries which are more prone to this disaster and what impact it had on the cities which it hit. A descriptive analysis was performed on the dataset in order to identify the variables of interest and Tableau Public was used as a visualization tool to visualize the dataset and draw informative conclusions. After the analysis of the dataset below is the approach that was taken to know the impact of tsunami and how its impact can be reduced w.r.t people.
a.	Identify the year in which the tsunami occurred in different locations around the world.
b.	Identify the parameters that caused tsunami so that we can know what factors that caused most tsunamis.
c.	Know how intense the tsunami can be and damage it incurs w.r.t social and financial aspects.
d.	Record the total deaths due to tsunami from 2000 BC till date
In order to visualize above factors certain variables are selected and graphs and charts have been plotted to draw more insights. 

Data Explorations:
1.	YEAR IN WHICH TSUNAMI WAS RECOREDED (2000 BC – 2019 AD)
Variables used: 
Year: 
Valid values: -2000 to Present
Format +/-yyyy (-is B.C, +is A.D.)
Worksheet Link: 
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-1

2.	MAJOR FACTORS THAT CAUSE TSUNAMI:
Variable used:
Country Name
Tsunami Cause Code:
Valid values: 0 to 11
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-2

3.	TSUNAMI INTENSITY 
Dataset: Tsunami source event 
Variable used:
Soloviev 
Valid values: -5 to 10
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-3

4.	DAMAGE IN DOLLORS:
Dataset: Tsunami Run-up 
Variable used:
Damage Millions of Dollars
Damage Description
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-4

5.	TOTAL DEATHS DUE TO TSUNAMI IN SOURCE LOCATIONS:

Dataset: Tsunami source event
Variable used:
Total Number of Deaths from the Tsunami and Source Event
Description of Deaths from the Tsunami and the Source Event
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-5

INSIGHTS and DASHBOARD:
From the exploratory analysis below are the three insights identified:
•	First Tsunami occurred on Syrian Coasts in 2000 BC
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-6
This visualization gives us information on not only where the first tsunami occurred but also gives information on when and where the first tsunami originated for each country. 

•	Major cause of tsunami is earthquakes and there has been significant increase in earthquakes since mid-1850s.
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-7
Visualization clearly shows that earthquake is the major factor for most of the tsunami occurrences. Apart from this the visual also shows significant increase in the earthquakes since mid-1850s compared to pre 1850s, with 17 occurrences in 1852, 18 in 1928, 19 in 1938 and so on. The factors that least contribute to tsunami occurrence are Cause Code 5(Volcano, Earthquake, and Landslide occurring all together) which was observer only once in 2013 and Cause Code 10(Explosion) which was observed in 1917.

•	More intense the tsunami more devastating impact it has on the population.
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-8
visual is created by using these variables and sum of total deaths is taken as reference in order to determine the size and color of the boxes. It shows the more the intensity of tsunami more is the death count. With intensity 3.0, 188092 is the death count and 4 (~1001 or more deaths) is the death description. There are also certain cases where intensity is high, but death count is low, for intensity 5, the death count is 2500 and 3 (~101 to 1000 deaths) is the death description this may be due to lesser population of people on those locations where the intensity of tsunami was more.

•	In year 2011 Japan experienced the worst financial damage due to tsunami
Worksheet Link:
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/Sheet-9


DASHBOARD FOR INSIGHTS:
Below is the link to tableau dashboard
https://public.tableau.com/profile/pavan2622#!/vizhome/D18128936_PavanNagesh/insights





