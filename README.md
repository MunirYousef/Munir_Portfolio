# Data Science Portfolio

# [Project 1: Breast Cancer Prediction: Project Overview](https://github.com/MunirYousef/Breast_Cancer_Predictor/blob/gh-pages/Breast_Cancer_Predictor.ipynb)
The information presented in this file contains data representing the correlation between characteristics or features of cells in Malignant and Benign masses. Some of the features include "uniformity of cell shape" and "clump thickness". 
After plotting the data in pairplots and heatmaps to visualize our values, the data was then split into a training and testing group using sklearn and preprocessing methods. 
The data was then fit into various ML algorithms/classifiers to test the models accuracy. The results of each test were displayed in a confusion matrix and visualizers. 
######## These operations were performed using Python in Jupyter Notebook with the only requirement being the imported libraries and the breast cancer data set which is also available on kaggle.

Project tools used:
-	Numpy
-	Pandas
-	matplotlib.pyplot
-	seaborn

![](/images/download.png)


![](/images/heat_map_1.png)

# [Project 2: Global Temperature Prediction: Project Overview](https://github.com/MunirYousef/Global_Temp/blob/master/Global_Temp_TS.ipynb)
This project was created to predict the trend of rising global temperatures using an ARIMA (AutoRegression, Integration, Moving Average) time series model. 
The steps follow a simple procedure of importing the necessesary tools for analysis and visualization. 
The dataset was pulled from https://datahub.io/core/global-temp and preprocessed to only include the temperatures recorded in March, every year from 1895 to 2016.

![](/images/moving_average_log_scale.png)

![](/images/rolling_mean_standard_dev.png)

![](/images/prediction_analysis.png)

# [Project 3: Using ArcGIS To Perfrom An Investigation Of Mining Communities In The United States In Relation To Average Household Income And Education Level: Project Overview](https://github.com/MunirYousef/ArcGIS/blob/master/yousef-%20ArcGIS%20Final%20Part3.docx)

Introduction
There are mining towns scattered across the United States. In most cases, mining camps came first, and communities built up around them. These communities have a number of different aspects that can be analyzed along demographic lines to better understand how earning potential in households are impacted by the presence of mining operations. This too can take many forms including educational achievement, etc.  While all of these are important to analyze together, this study focused average household income in mining communities by County.  

To better understand the communities that mining camps are situated in, demographic data on the attainment of average income by county was analyzed.  Since this may be both a national and localized phenomenon, the analysis included both a national perspective and a local one.  Westchester County in New York State was used for local analysis.  The study attempted to Analyze:
1.	What is the distribution of average income in mining towns in the continental United States and locally in Westchester County.
2.	What is the distribution of counties with average income (both locally and nationally)
3.	What mining towns are in the designated demographic (Average income with Bachelor’s degrees attained less than the Mean).

**Methodology**
The development environment for this study was ESRI ArcGIS Arcmap.
This study used data from Social Explorer’s Education data set. Social Explorer has a wide variety of demographic data sets including:
1.	Education
2.	Employment
3.	Family
4.	Housing
5.	Income
6.	Poverty
7.	Real Estate

![](/images/map2.jpg)

![](/images/map1.jpg)

To get a base map of counties, the study used US Census Bureau Tigerline 2018 data. Social Explorer Education Attainment data was joined with County data to perform geographic analysis.  
To select counties with a specific demographic character (e.g. Average Income < mean), the joined layer was used.  Finally, to specifically select those mining communities within the selected demographic layer selection by location was used.
Results
In the discussion below, both the Continental US and Westchester County were analyzed (and shown). Local analysis may require more investigation since the number of mining communities were limited.
The base maps and initial demographic showed dense concentrations of mining towns in urban centers in the east coast. The mining towns are sparse on the western half of the country.



