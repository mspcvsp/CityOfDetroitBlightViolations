# CityOfDetroitBlightViolations
Project Motivation:
------------------
Erwin de Leon and Joseph Schilling introduce their April 2017 Urban Institute research report [“Urban Blight and Public Health: Addressing the Impact of Substandard Housing, Abandoned Buildings, and Vacant Lots”](https://www.urban.org/research/publication/urban-blight-and-public-health) with the following statement: “We spend more than 2/3rds of our time where we live; thus, housing and neighborhood conditions affect our individual and family’s well-being”. They also discuss the impact of poor economic conditions that result in “increasing inventories of vacant homes and abandoned buildings”. For example, the authors of this report cite the Detroit Blight Removal Task Force’s 2014 “strategic plan to address more than 80,000 derelict structures and vacant lots”.  

Summary of the Analysis Results:
-------------------------------
The [AnalyzeBVNDataSet.ipynb Jupyter notebook] (https://github.com/mspcvsp/CityOfDetroitBlightViolations/blob/master/AnalyzeBVNDataSet.ipynb) illustrates my application of the Python programming language to answer three questions regarding the [City of Detroit MI Blight Violation Notices (BVN)](https://data.detroitmi.gov/Property-Parcels/Blight-Violations/ti6p-wcg4)public domain data set:  

1. Is the number of blight violations per month increasing, decreasing, or staying constant over time?
2. Is the total balance due per month increasing, decreasing, or staying constant over time?
3. For 2017, are “responsible by default” blight violation notices non-uniformly distributed as a function of latitude and longitude?  

My analysis of this data set suggests that the number of blight violations and the total balance due per month peaked during the 2008 recession. I also observed a decrease in these two metrics from 2009 to 2014 and an upward trend from 2014 to the present. The conclusion that I drew based on my cluster analysis of 2017 “responsible by default” violations is that they are non-uniformly distributed as a function of latitude and longitude. A potential extension of this analysis is to expand upon the predictive modeling described in the [“Understanding Blight Ticket Compliance in Detroit”](https://midas.umich.edu/wp-content/uploads/sites/3/2017/09/understanding-blight-ticket.pdf) journal article published at the 2017 Data Science for Social Good Conference in Chicago, IL.

Repository Files:
----------------  
- AnalyzeBVNDataSet.ipynb: Python software that analyzes the City of Detroit MI Blight Violation Notices public domain dataset  
- LICENSE: Repository license file

Libraries used:
--------------
- [NumPy](http://www.numpy.org/)   
- [Pandas](https://pandas.pydata.org/)  
- [os](https://docs.python.org/3/library/os.html)  
- [re](https://docs.python.org/3/library/re.html)  
- [urllib](https://docs.python.org/3/library/urllib.html)
- [matplotlib](https://matplotlib.org/)  
- [seaborn](https://seaborn.pydata.org/)  
- [scikit-learn](http://scikit-learn.org/stable/)  
- [datetime](https://docs.python.org/3.6/library/datetime.html)  
- [Folium](https://blog.dominodatalab.com/creating-interactive-crime-maps-with-folium/)  
- [GeoPy](https://geopy.readthedocs.io/en/stable/)  

[Blog article that summarizes this Python software](https://medium.com/@mspcvsp/city-of-detroit-blight-violation-notices-statistics-a0adb94e61dc)  
