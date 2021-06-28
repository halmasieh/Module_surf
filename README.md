# Surfs Up

## Project Overview
In this analysis, we have used SQLite, a version of SQL which is smaller and faster and does not have users. SQLite is the most widely used database engine
in the world which is used in smart phones, computers and many applications that we have probably used before like [Itunes](https://www.apple.com/itunes/) and 
[Photoshop](https://www.adobe.com/adobe/photoshop). One of the reasons 
that SQLite is so popular is because it can be stored locally and instead of database server, local databases support quick testing and easy prototyping.
In order to use all the benefits of SQLite, we use a query tool called SQLAlchemy. It is extremely helpful for quering SQLite and integrates the statistics 
analysis with dataframe analysis.    

This project is done as follows: 
   - Explain the structures, interactions, and types of data of a provided dataset.
   - Use SQLAlchemy to connect to and query a SQLite database.
   - Determine the Summary Statistics for months of June and December in Oahu in order to determine if the surf and ice cream shop business is sustainable year-round using
     Python, Pandas functions and SQLAlchemy


## Resources
- Data Sources: hawaii.sqlite
- Software: [Jupyter Notebook](https://www.anaconda.com/products/individual), SQLite, [Matplotlib](https://matplotlib.org/)
- Module: SQLAlchemy

## Results
We plot the results of the analysis so that a visual presentation can help all the stackholders to make a decision about the surf shop location and convince them to inverst in 
starting the surf shop. 

1- Looking at the histogram plot from the June temperature observations. 



![here](https://github.com/halmasieh/Surfs-Up/blob/main/Images/hist_June.PNG)



This will allow us to quickly count how many temperature observations we have. Therefore, 
We can infer that a vast majority of the observations were over 74 degrees. 

2- Looking at the histogram plot from the December temperature observations. 




![here](https://github.com/halmasieh/surfs_up/blob/main/Images/hist_Dec.PNG)



We can infer that a vast majority of the observations were over 65 degrees. 



3- The results obtained from the following two tables related to the summary statistics of June and December temperature show that 

- Low (minimum) temperature is 64 and 56 degrees, respectively.
- High (maximum) temperature is 85 and 83 degrees, respectively.
- The average temperature is approximately 74.9 and 71 degrees, respectively.




![here](https://github.com/halmasieh/surfs_up/blob/main/Images/June_Dec_table.PNG)




By comparing the above summary statistics, It is quite clear that since starting a surf shop is directly related to the temperature.
In other words, the profits and losses of this business are directly related to weather conditions. Therefore investing in the months with higher temperature
like June will definitely bring a better financial return than the months with lower temperature like December.







## Summary

In fact "Silver Tsunami" is a metaphor used to describe the expected increase in the senior population. Today 15% of Americans are 65 or older and the aging population
can bring positive change to healthcare and senior living. Avtually, there are three main areas of our economy and society that will be most affected by 
- Health Care Resources
- Economic Struggles
- Workforce Influence

Focus on the latter, lest all this sound hopeless and awful, many seniors will stay healthy long enough to work past the age they may have had in mind for retirement. 
We performed this analysis on personels over sixty five years old with different job titles and the results are shown in the following table as:




![here](https://github.com/halmasieh/surfs_up/blob/main/Images/hist_Dec.PNG)



Most people over 65 years who retire soon are Engineers and Senior Staffs, repectively, therefore, the need to employ these two roles is a priority.
The rest of roles will need to be filled are Staff, Senior Engineer, Technique Leader, Assisstant Engineer and Manager, respectively.

The table below shows the trainees in the mentorship eligiblity program according to the different job titles:



![here](https://github.com/halmasieh/surfs_up/blob/main/Images/hist_Dec.PNG)




Comparing the above two tables, it is quite clear that the number of qualified trainees in the mentorship program who can replace with 
the silver tsunami retirees is not enough and Pewlett-Hackard needs to train more people to be able to hold various roles in this large company.
The code for the tables is available [here](https://github.com/halmasieh/Pewlett-Hackard-Analysis/blob/main/silver_tsunami.sql). 
