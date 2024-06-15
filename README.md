# ana-515-week-iv

Comprehensive Analysis of U.S. 30-year Climate Normals (1991-2020)

Overview
This project provides a comprehensive analysis of the 30-year climate normals data for key weather stations in the United States. The dataset, provided by the National Centers for Environmental Information (NCEI), includes monthly climate normals for temperature and precipitation for the period from 1991 to 2020. The analysis includes data acquisition, cleaning, aggregation, summary statistics, and a variety of visualizations to explore and understand the data.

Dataset
The climate normals data were sourced from the NCEI website. The dataset includes monthly climate normals for temperature and precipitation, along with metadata for key weather stations.

Data Source: NCEI Climate Normals
Inventory File: Inventory 30-year Climate Normals
Readme File: Readme By-Variable By-Station Normals Files
Requirements
The analysis is performed using R and requires the following packages:

tidyverse
bslib
ggplot2
dplyr
readr
knitr
rmarkdown
rnaturalearth
rnaturalearthdata
sf
furrr
httr
xml2
lubridate
progress
transformr

Instructions
Setup
Install R and RStudio: Ensure that you have R and RStudio installed on your computer.

Install Required Packages: The necessary packages will be automatically checked and installed when you run the R Markdown document.

Running the Analysis
Download the R Markdown Document: Save the provided R Markdown (.Rmd) file to your local machine.

Open the R Markdown Document in RStudio: Launch RStudio and open the .Rmd file.

Run the Document: Click on the "Knit" button in RStudio to render the document. This will execute all the code chunks, download the necessary data, perform the analysis, and generate a comprehensive report in PDF format.

Code Description
The R Markdown document is structured as follows:

Introduction: Provides an overview of the analysis and the dataset.
Data Acquisition: Describes the process of downloading the data from the NCEI website and loading it into R.
Key Stations: Identifies key weather stations based on their Global Surface Network (GSN) and Historical Climatology Network (HCN) status.
Data Cleaning and Aggregation: Cleans the data and calculates monthly averages for temperature and precipitation.
Characteristics of the Data: Provides a summary of the data, including the number of rows and columns, and a description of each column.
Summary Statistics: Presents summary statistics for the temperature and precipitation data.
Visualizations: Includes a variety of plots to explore the data, such as line plots, boxplots, heatmaps, and geographical maps.

Visualizations
The following visualizations are included in the analysis:

Monthly Average Temperature by Station
Monthly Average Precipitation by Station
Boxplot of Monthly Average Temperature
Boxplot of Monthly Average Precipitation
Heatmap of Monthly Average Temperature
Heatmap of Monthly Average Precipitation
Visualization of Data on Map (Temperature and Precipitation)
Temperature Distribution
Precipitation Distribution

References
National Centers for Environmental Information (NCEI). "Climate Normals." Accessed June 15, 2024. NCEI Climate Normals
National Centers for Environmental Information (NCEI). "Inventory 30-year Climate Normals." Accessed June 15, 2024. Inventory 30-year Climate Normals
National Centers for Environmental Information (NCEI). "Readme By-Variable By-Station Normals Files." Accessed June 15, 2024. Readme By-Variable By-Station Normals Files
