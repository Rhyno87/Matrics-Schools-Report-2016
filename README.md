# Matrics-Schools-Report-2016
## **Purpose of the project**
I looked at the Matric Schools Report for 2016, which included years 2014, 2015 and lastly 2016.
I looked at how the results of pass rates and progressed rates of 2014 looked compared to 2016, as 2014 was the first year that the CAPS
cirriculem was introduced to matrics.

##**Data Analysed**
The data analysed was in a csv file format(https://github.com/Rhyno87/Matrics-Schools-Report-2016/blob/master/Matrics%20Reports%202016.csv).
The data set consisted of 1000 rows and 15 columns.  Columns that I found interesting was the quintile column, as that put the schools into 
certain areas tied to their socia-econimic area.  And I focused quite abit on that aswell.

##**How Data was Analysed**
I used a jupyter notenook to write the code(https://github.com/Rhyno87/Matrics-Schools-Report-2016/blob/master/Matrics%20Schools%20Report%202016.ipynb)
as stated earlier, the dataset consists of 1000 rows(information on schools) and 15 rows(how information was devided up).
Some of the columns are centre_no, quintile, wrote_2014, perc_2015 and passed_2016.  Like I said this is only some of the columns.
I looked at how the data was distributed using .describe(), also calculating the number of missing data points for each column using isnull().sum().
Additionally I calculated the percentage of the missing data.  For visiulization purposes I pulled a matrix to see where the missing data points lay.

##**Main Findings**
I compiled all my findings in an EDA report(https://github.com/Rhyno87/Matrics-Schools-Report-2016/blob.master/EDA.docx).
As part of my data cleaning I determined that I hade eight colums with missing data points, but still had enough data to work with and pull visualizations.
I grouped the columns by quintile and looked at the amount of schools there was per quintile and pulled a count plot to better visualize the data.
As said earlier I looked specificly at year 2014 and 2016.
I pulled to boxplots for 2014 and 2016 indicating the pass rate per quintile per year.
I also pulled heat maps for both year to indicate the amount of students that wrote and passed per year.
Lastly I pulled to distplots to show the distribution of passed students per year and how there was an increase in the later year as the confidence on the
material increased.
