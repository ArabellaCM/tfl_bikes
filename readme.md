# Ironhack Final Project - What effect did Covid have on TFL's Cycle Hire Scheme?

This repository contains the final project for the Ironhack Data Analysis course in Berlin Jan-Mar 2021<br/>


# Code and Resources Used
- Python Version: 3.7 <br/>
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, statsmodel, geocoder, beautiful soup, requests <br/>
- APIs: TFL, Google Elevation, Bing<br/>


# Data gathering and export
The data was gathered from these sources:<br/>
- London Datastore<br/>
- TFL Open Data<br/>
- 2011 UK Census<br/>
- TFL API<br/>
- Google Elevation API<br/>
- checkmypostcode.co.uk<br/>


# Linear Regression<br/>
A linear regression model was run to predict the total number of journeys to and from a docking station based on a large number of demographic and geographical features for each docking station <br/>
The results for 2019 were an R-squared score of 25% implying some correlation with the features however for 2020 the R-squared score was only 5% which implies that these features didn't reflect the popularity of the docking stations for 2020.<br/>
Linear Regression, KNN and Random Forest models were all applied with similar results from each. <br/>

# Grouping
The individual journeys were grouped based on the area they started and ended in. The areas were defined as "residential", "non-residential" and "mixed". This showed a big shift in the type of journeys at the start of the lockdown. <br/>

 
# Time Series Analysis
A simple time series analysis was run on the daily number of journeys since 2015. This showed clear seasonal patterns with higher usage during the summer and lower during the winter. It also showed a high number of residuals for 2020 implying that it does not fit the pattern <br/>

# May 2019 and 2020
More detailed data exports were created for May 2019 and May 2020 for further exploration in Tableau<br/>


# Visualization and Presentation
All visualisations can be seen in this Tableau presentation:
https://public.tableau.com/profile/arabella.cooper.maddocks#!/vizhome/TFLCycleHireduringCovid/Story1
