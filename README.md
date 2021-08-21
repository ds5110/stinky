# stinky

## Northeastern University student projects

### Smell reports

Summer 2021 term - links to Jupyter notebooks. (Links at the top of these notebooks will open them automatically in Colab).

1. Files for updating data (these notebooks clean and merge raw data, as needed)
* [stinky_dataset.ipynb](https://github.com/ds5110/stinky/blob/master/stinky_dataset.ipynb) -- Use to update df_stinky, table that combines data from SmellMyCity and SeeClickFix
* [oil_vessel_dataset.ipynb](https://github.com/caro28/ds5110_project/blob/main/oil_vessel_dataset.ipynb) -- Use to update df_vessels, table that contains merged, annual data tracking oil vessel passages through Portland (TEMP link through Caroline's fork until fix pull request issue)

2. Files with students' analyses
* [text_analysis_caroline.ipynb](https://github.com/ds5110/stinky/blob/master/text_analysis_caroline.ipynb) -- Example of using tidied data saved as csv files in data folder

### Environmental sensors

* All raw pod measurements are uploaded to the "stinky/weather_data_raw" directory in this repo. Those files are in the form of .csv. To update this repo simply replace the pod file. Thre replacement file needs to keep the original file naming scheme.

1.) Files for personal download (this notebook will autmatically download the weather group's data set - just run to download. These files do not need to moved to the repo - they can used for personal analyses)
* [weather_datasets.ipynb](https://github.com/ds5110/stinky/blob/master/weather_datasets.ipynb)

### Data files - description of data folders and individual file names
* The data folder contains all the csv files 
1. 

## Project Idea: This Stinks

Problem: Residents of Portland and South Portland in Maine have been reporting disruptive smells in the air 
on certain days of the year. 
South Portland has over 25,500 residents, and is the host of oil, gasoline, and asphalt tanks. 
These tanks do not have emissions controls and the emissions, in the form of odors, 
are reported in both South Portland and Portland. 
Many of the emissions are odorless and toxic, and may or may not correlate with odor complaints. 
It's been unclear what the source of the smells might be and difficult to understand the extent of the 
issue on both sides of the Fore River, which separates Portland and South Portland.

The City of South Portland relies on [Smell My City](https://smellmycity.org/) for odor complaints, 
while Portland relies on [See Click Fix](https://seeclickfix.com/portland_2).
The Department of Environmental Protection has 
[9 VOC Canister Monitors](https://www.maine.gov/dep/air/monitoring/spo-sampling-results.html)
(volatile organic compounds) in Portland and South Portland. 
The tanks are considered [minor sources of air emissions](https://www.maine.gov/dep/air/permits/minor.html),
and regulated accordingly.

### Project goals.

* Coordinate the various data sources
  * Smell My City odor complaints (South Portland)
  * See Click Fix odor complaints (Portland)
  * DEP VOC sampling data
  * Civilian grab canister results
  * Tom Mikulka monitoring data (for comparison only)
  * Weather patterns
  * Tank fills and transfers (dependent on access to data)
  * Individual tank inventory and temperature status
* Clean the data and make it easily accessible for the general public
* Create some simple visualizations
* Add additional data from ME DEP (e.g., wind speed, direction, temperature, etc)
Initial mapping will use compiled data, but the intent is to harvest data in real time to account 
for established correlations, additional sampling, and continued monitoring. 
Per [LD163](http://www.mainelegislature.org/legis/bills/getPDF.asp?paper=HP0119&item=2&snum=130), 
additional sampling will include: 
* Fenceline monitoring (continuous)
* Self reported emissions testing on heated tanks (2x yearly)

### Project partners

* The Greater Portland Council of Governments (GPCOG)
* The Sierra Club
* Roux Institute

## data

* Excel spreadsheet -- for City of Portland, Maine
  * [SeeClickFix](https://seeclickfix.com/portland_2) app for Portland residents
  * residents add odor reports with the app
  * these reports are collected by the city and sent (to us) monthly in an excel file
* https://smellmycity.org/data
  * This site has directions for accessing South Portland odor complaints
  * Enter ZIP codes of interest (South Portland have several ZIP codes) 
  * This produces a spreadsheet for download
* https://rainwise.net/weather/SMRO3
  * This site has DEP weather reports. 
  * The top drop-down menu has reports of interest to the project. 
  * There are many stations, only a portion of them are online
  * SMRO 3-7 (the units that are online) -- note the location at the bottom of the page. 
  * These were installed sometime in 2020 (that's when ME DEP started monitoring South Portland in particular)
  * To download spreadsheets, hit the button at the top of the bar that is a downward arrow.
* Oil terminals -- all of this data is in paper form
  * When barges come into the Portland terminal to deliver or pick up oil, they have to give DEP notice
  * There are written notifications from boats to ME DEP -- these are faxed paper copies
  * We hope to be be getting this data...

## key people

* Maria Guerra (Environmental Health Fellow, [Resilience Corps](https://www.gpcog.org/472/Resilience-Corps) at GPCOG)
* Andrew Butcher (Director of Innovation & Resilience, [GPCOG](https://www.gpcog.org))
* Luke Truman (Sierra Club's Maine Chapter)
  * Luke has experience in data mapping, and working on projects with college students.
  * He has been invested in this problem of Portland/South Portland air quality for some time.
