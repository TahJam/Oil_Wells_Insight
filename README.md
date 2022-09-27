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
Alabama's Water Consumption
<img src="Images/Alabama.png" alt="Alt text" title="Alabama Water Consumption" style="background-color:white">

Alaska's Water Consumption

<img src="Images/Alaska.png" alt="Alaska Water Consumption" title="Alaska Water Consumption" style="background-color:white">



### Graph of the States Usage of Water
![Alt text](Images/stateWater.png "State Water Consumption")

