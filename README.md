# **UCB FinTech Bootcamp Module 6 Challenge**
# *San Francisco Real Estate Analysis*
## **Introduction**

### The Bootcamp Module 6 Challenge - San Francisco Real Estate Analysis  requires us to analyze the Real Estate market performance of the city of San Francisco, CA between 2010 and 2016. 
### Based on the three key performance metrics avaialble by neighborhood  - Number of Housing Units, Sales Price per Square foot and Gross Rent Prices - we are to complete three separate analysis and present them on graphical form using the different Python data visualization packages:  Housing Unit Trends across the city, Overall Sales Price per Square Foot and Gross Rent trends across the city and finally, Sales Price per Square Foot and Gross Rent trends by neighborhood.
---
## **Goals and Objectives**

### ***Part I.*** Create a bar chart graph showing the annual Housing Unit numbers across the city and comment on the observed trend for the analysis period and answer the questions included in the Jupyter Notebook.
### ***Part II.*** Create a line chart graph showing the yearly average Sales Price per Square foot, and Gross Rent, in a single visualization for the analysis period. Comment on the observed trends and compare them for the sales and the rental markets and answer the questions in the Jupyter Notebook.
### ***Part III.*** Create a line chart graph showing the yearly average Sales Price per Square foot, and Gross Rent, in a single visualization, with filter by neighborhood enabled, for the analysis period. Complement the analysis with an interactive neighborhood map that plots the physical location of the interest data points (e.g. higher/lower sales/rent prices). Comment on the trends observed across the sales and rent data sets for specific neighborhoods by answering the questions in the Jupyter Notebook.
---
## **Technologies and Tools**

### The following list includes the main technologies and tools using during the preparation and deployment of the solution:
### 1. *Python* - Programming language used to code the solution. Version 3.7.13 was used
### 2. *GitHub* - Reposotory for code deployment, version management and documentation of the presented solution
### 3. *Jupyter Labs* - IDE tool for coding, code testing/debugging and solution documentation. Version V3.4.4 was used
### 4. *Git Bash console* - Local console used to test the coded solution and sync wiht GitHub Version 2.40.1.windows.1 was utilized for this challenge
### 5. *Slack* - Collaboration tool to communicate and brainstorm with other FinTech Bootcamp participants
### 6. *Operative System* - This solution was prepared in a PC running Windows 11 v H22
### 7. *[OpenStreetMap](https://wiki.openstreetmap.org/wiki/Using_OpenStreetMap)* - OpenStreetMap (OSM) is a global collaborative (crowd-sourced) dataset and project that aims at creating a free editable map of the world containing a lot of information about our environment 1. It contains data for example about streets, buildings, different services, and landuse to mention a few. While no additional installation was required for the current challenge, we are using OSM to source the rendering of the San Francisco neighborhoods for the interactive map part of the challenge.
### 8. *[Bokeh](https://bokeh.org/)* - Bokeh is a Python library used to make interactive graphs and visualizations using HTML and JavaScript.
### 9. *[GeoViews](https://geoviews.org/)* -  GeoViews is a Python library that provides a high-level interface for working with geographical data and creating interactive visualizations.
---
## **Installation Guide**

### 1. *Bokeh* - To be able to use the Bokeh library you need to install the package in your Python environment as follows:
#### 1.1. Open the GitBash terminal
#### 1.2 Type the following command and press Enter:
```python 
pip install bokeh
```
### 2. *GeoViews* - You can install GeoViews and its dependencies - e.g. HoloViews, Bokeh, and Cartopy -  by running the following steps:
#### 2.1. Open the GitBash terminal
#### 2.2 Type the following command and press Enter:
```python 
pip install geoviews
```
---
## **Solution Structure**

### The **[6.sfo_real_estate](https://github.com/LUTOV001/6.sfo_real_estate)** repository in GitHub contains the solution components. The repository consists of the following folders, subfolders and contents as described below:
 
###    1. Images : Includes the .png image files to illustrate the instructions in the Solution Jupyter Notebook. 
###    2. Resources : Includes the files with Real Estate data used for the analysis:
####     | 2.1 housing_per_year.csv
####     | 2.2 neighborhood_coordinates.csv
####     | 2.3 sfo_neigborhoods_census_data.csv
###    3. gitignore : Instructions for which files/file types to exclude from GitHub sync
###    4. README.md - The present file containing the outline of the repository and the solution
###    5. *san_francisco_housing.ipynb* is the Jupyter Notebook with the code for the core challenge solution
---
## **User Instructions**

### 1. Launch the Jupyter Lab from the GitBash terminal using the following command line:
```python 
jupyter lab
```
### 2. From the Jupyter Lab terminal, navigate to respositiry folder (e.g. 6.sfo_real_estate) and open the *san_francisco_housing.ipynb* Notebook.
### 3. Reset the Kernel and
### 4. Run the steps in sequence and verify the results as per the comments in the Notebook, including outputs on the screen (e.g. plot images, data frame prints, etc.)
---
### **Credits**

#### Prepared by Luis Torres 
#### LUTOV001@gmail.com
#### April 2023
