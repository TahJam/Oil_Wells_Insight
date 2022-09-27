# CaseStudy2 - FracFocus

## Introduction
In this case study, I am given a dataset from [FracFocus](https://fracfocus.org/data-download) and am tasked to run a statistical analysis of my choosing to make sense of the raw data. As the dataset is very large, I first clean the data and get rid of the attributes that did not contribute to my analysis.
I wanted to focus on the water and nonwater susbtances used in the base of the hydraulic system of each well that was used in the fracking jobs. To do this, I grouped together the wells by the counties they were located in and then I grouped together the counties into the individual states they are located in. The reason I focused on water was because, while it plays a crucial role in fracking and drilling, it is also a key resource for local communities. It is important that the Operators of the wells use the fresh water resource responsibly and make sure that the water supply is not negatively impacted by their use. <br>

## Tools Used
To conduct my analysis, I used Jupyter Notebook to write clean and concise `Python` code to read the data, cleaned it apporopriately and then ran my analysis on the cleaned data. I used `Pandas DataFrame` to read and store the data and `matplotlib` to create insightful graphs about the volume of water and nonwater substances used by the different wells around the United States. 

## Findings and Graphs
**State that used the least amount of water:** Idaho <br>
  * The state of Idaho had only one county that drilled and only used 727 gallons of water. <br>

**State that used the most amount of water:** Texas <br> 
  * The state of Texas has wells in 188 different counties and used almost 650 billion gallons of water. Out of the counties in Texas, Midland used the most water; close to 73 billion gallons of water. <br>

### Graphs of Counties in Each State
<p align="center">
 <img src="Images/Alabama.png" alt="Alt text" title="Alabama Water Consumption" style="background-color:33AFFF"><br>
 Alabama Water Consumption
</p>

<p align="center">
<img src="Images/Alaska.png" alt="Alaska Water Consumption" title="Alaska Water Consumption" style="background-color:white">
 <br>Alaska's Water Consumption
</p>

<p align="center">
<img src="Images/Arkansas.png" alt="Water Consumption" title="Arkansas Water Consumption" style="background-color:white">
 <br>Arkansas's Water Consumption
</p>

<p align="center">
<img src="Images/Cali.png" alt="Water Consumption" title="California's Water Consumption" style="background-color:white">
 <br>California's Water Consumption
</p>

<p align="center">
<img src="Images/Colorado.png" alt="Water Consumption" title="Colorado's Water Consumption" style="background-color:white">
 <br>Colorado's Water Consumption
</p>

<p align="center">
<img src="Images/Idaho.png" alt="Water Consumption" title="Idaho's Water Consumption" style="background-color:white">
 <br>Idaho's Water Consumption
</p>

<p align="center">
<img src="Images/Illinois.png" alt="Water Consumption" title="Illinois's Water Consumption" style="background-color:white">
 <br>Illinois's Water Consumption
</p>

<p align="center">
<img src="Images/Indiana.png" alt="Water Consumption" title="Indiana's Water Consumption" style="background-color:white">
 <br>Indiana's Water Consumption
</p>

<p align="center">
<img src="Images/Kansas.png" alt="Water Consumption" title="Kansas's Water Consumption" style="background-color:white">
 <br>Kansas's Water Consumption
</p>

<p align="center">
<img src="Images/Kent.png" alt="Water Consumption" title="Kentucky's Water Consumption" style="background-color:white">
 <br>Kentucky's Water Consumption
</p>

<p align="center">
<img src="Images/Lois.png" alt="Water Consumption" title="Louisiana's Water Consumption" style="background-color:white">
 <br>Louisiana's Water Consumption
</p>

<p align="center">
<img src="Images/Michi.png" alt="Water Consumption" title="Michigan's Water Consumption" style="background-color:white">
 <br>Michigan's Water Consumption
</p>

<p align="center">
<img src="Images/Missi.png" alt="Water Consumption" title="Mississippi's Water Consumption" style="background-color:white">
 <br>Mississippi's Water Consumption
</p>

<p align="center">
<img src="Images/Mont.png" alt="Water Consumption" title="Montana's Water Consumption" style="background-color:white">
 <br>Montana's Water Consumption
</p>


<p align="center">
<img src="Images/NC.png" alt="Water Consumption" title="North Carolina's Water Consumption" style="background-color:white">
 <br>North Carolina's Water Consumption
</p>

<p align="center">
<img src="Images/ND.png" alt="Water Consumption" title="North Dakota's Water Consumption" style="background-color:white">
 <br>North Dakota's Water Consumption
</p>

<p align="center">
<img src="Images/NY.png" alt="Water Consumption" title="New York's Water Consumption" style="background-color:white">
 <br>New York's Water Consumption
</p>

<p align="center">
<img src="Images/Nebr.png" alt="Water Consumption" title="Nebraska's Water Consumption" style="background-color:white">
 <br>Nebraska's Water Consumption
</p>

<p align="center">
<img src="Images/Nevada.png" alt="Water Consumption" title="Nevada's Water Consumption" style="background-color:white">
 <br>Nevada's Water Consumption
</p>

<p align="center">
<img src="Images/NewMex.png" alt="Water Consumption" title="New Mexico's Water Consumption" style="background-color:white">
 <br>New Mexico's Water Consumption
</p>

<p align="center">
<img src="Images/Ohio.png" alt="Water Consumption" title="Ohio's Water Consumption" style="background-color:white">
 <br>Ohio's Water Consumption
</p>

<p align="center">
<img src="Images/Okla.png" alt="Water Consumption" title="Oklahoma's Water Consumption" style="background-color:white">
 <br>Oklahoma's Water Consumption
</p>

<p align="center">
<img src="Images/Penn.png" alt="Water Consumption" title="Pennsylvania's Water Consumption" style="background-color:white">
 <br>Pennsylvania's Water Consumption
</p>

<p align="center">
<img src="Images/Texas.png" alt="Water Consumption" title="Texas's Water Consumption" style="background-color:white">
 <br>Texas's Water Consumption
</p>

<p align="center">
<img src="Images/Utah.png" alt="Water Consumption" title="Utah's Water Consumption" style="background-color:white">
 <br>Utah's Water Consumption
</p>

<p align="center">
<img src="Images/Virg.png" alt="Water Consumption" title="Virginia's Water Consumption" style="background-color:white">
 <br>Virgina's Water Consumption
</p>

<p align="center">
<img src="Images/WestVirg.png" alt="Water Consumption" title="West Virginia's Water Consumption" style="background-color:white">
 <br>West Virgina's Water Consumption
</p>

<p align="center">
<img src="Images/Wyom.png" alt="Water Consumption" title="Wyoming's Water Consumption" style="background-color:white">
 <br>Wyoming's Water Consumption
</p>


### Graph of the States Usage of Water

<p align="center">
<img src="Images/stateWater.png" alt="Water Consumption" title="Water Consumption by State" style="background-color:white">
 <br>Water Consumption by State
</p>

## Conclusion
There are many interesting conclusions that can be drawn from this data that can help businesses make insightful descisions or allocate resources to the wells that need it most. In my analysis, I wanted to focus on the amount of water and nonwater materials used in well jobs. Water is, arguably, our most precious resource but not most abundant, and so, we must use it wisely. With this data, one can determine how severely the location's fracking activity is having on the local water supply. Another use case for this data is to be used as a factor in determining whether to increase drilling in a specific location. An operator may choose to not continue fracking if a lot of water needs to be used at the specific location.
<br>
## Other Areas to Analyze
There are many other areas I had wished to analyze, however, with the constraint of time and resources, I have limited my analysis on just the usage of water. If there was another area I could have focused my analysis on, it would be about the materials used in the wells for different purposes. For example, many wells used Crystalline Silica Quartz as a proppant, others used Coconut Diethanolamide as a non-emulsifying acid. After grouping all the materials by their location, businesses can use this knowledge to determine what materials are needed where. 

