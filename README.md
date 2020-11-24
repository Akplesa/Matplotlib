# Pymaceuticals

## Purpose 
Pymaceuticals Inc., is a mock burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
Their most recent animal study is comprised of 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. My goal is to generate all of the tables and figures needed for the technical report of the study. 

## Process 
* checking the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.


* Using the cleaned data for the remaining steps.


* Generating a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


* Generating a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.


* Selecting a mouse that was treated with Capomulin and generating a line plot of tumor volume vs. time point for that mouse.


* Generating a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


* Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


* Looking across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

## Analysis
1. Most of the mice were used for Capomulin and for Ramicane Treatment
2. Tumor volume shows to decrease over time for the Capomulin treatment.
3. The linear regreassion model shows a positive coorelation between Mouse weight and Tumor volume.



