# CaseStudy2 - FracFocus

## Introduction
This Case Study involves running Statistical Analysis on a Dataset provided by FracFocus, a industry leading provider of chemical disclosures in national hydraulic fracturing. 
- Due to large size of dataset and to address performance issue, the data is first cleansed and the attributes normalized
  - Attributes were normalized using the min-max normalization
  - Target data was binned so that understanding the distribution was made easier
- Focus on water and non-water substance’s used in the base of the hydraulic system of each well used in the fracking jobs
- Wells were grouped by the demographic data grouped by State and County
- Water has vital role in fracking and drilling, as also is a key resource for local communities. It is important that the Well Operators assume the social responsibility of the balanced use of fresh water
## Prerequisite
Many components of this project are best viewed in light mode therefore it is required that viewers have their system setting in light mode (dark mode is not recommended).
## Tools Used
`Jupyter Notebook` was used to:
- Write clean and concise `Python` code to read the data
- Run analysis on the cleaned data
 
`Pandas DataFrame` was used to:
 - Read and store the data 

`matplotlib` was used to: <br>
 - Create insightful graphs about the analyzed data 

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
Several insights can be drawn from this analysis
  - Resources needed to be allocated at the Well level
  - Appropriate usage of planet’s most critical commodity i.e. Water
  - Impact of fracking activity at precise geo location level
  - Areas of expansion of drilling activity by location
  - Discontinuation of fracking activity of non-performing Well
## Other Areas to Analyze
Due to the constraint of time and resources, this analysis has been limited to just the usage of water. <br>
Other areas to analyze: 
- Grouping materials used in the wells by location 
  - Many wells used Crystalline Silica Quartz as a proppant, others used Coconut Diethanolamide as a non-emulsifying acid. 
  - After grouping, businesses can determine what materials are needed where and therefore allocate their own supplies to the places of high demand. 

