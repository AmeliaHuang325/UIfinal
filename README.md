# UIfinal

# Social vulnerability and Airbnb Price
> Do Location and Local Context Affect Airbnb Price?


This project aims to explore and examine whether the location and local neighboring context of Airbnb properties affect their prices. Social Vulnerability Index (SVI) is used as the value to reflect neighborhood conditions. Depending on the definition and implication of SVI score, ACS (American Community Survey) is the primary dataset being used besides Airbnb data. The Airbnb data is scraped and produced by Tom Slee (http://tomslee.net/). We choose the Airbnb data from July 2017 in New York City. Principal Component Analysis (PCA) and Factor analysis (FA) are the mathematical procedures we applied to determine the most relevant variables. Besides the analysis of the relationship between the social environment and Airbnb price, we built a platform where either users or Airbnb hosts can find out the information of each Airbnb property while getting a sense of the neighboring environment at the same time. This interactive website enhances data communication and enables people to make use of the data to help with their future trips and vacations. 


## Python packages

python packages:

```sh
pip install geopandas
pip install pysal
pip install shapefile
pip install sklearn
pip install json
pip install factor_analyzer
pip install plotly
pip install matplotlib.pyplot
pip install shapely
pip install foliums
pip install vincent
pip install unicodedata
```

## Usage example

More neighborhood factors could be taken into account in the future with the purpose of acquiring a more comprehensive sense about how price tendency may relate to the social environment at the local level.  


## Meta

Shuyang Huang - sh3685 - sh3685@columbia.edu
Lu Hao - lh2857 - lh2857@columbia.edu


## Data Reference and Citations
Data:

United States Census Bureau / American FactFinder. 2012 - 2016 American Community Survey 5-year estimates. Released on December 7, 2017. Retrieved from https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml?refresh=t
New York City Department of City Planning. New York City Census Tracts for 2010 US Census. Released on November 19, 2018. Retrieve from https://www1.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page
Airbnb data: https://github.com/tomslee/airbnb-data-collection  

Code reference:

https://gist.github.com/frankrowe/6071443
https://towardsdatascience.com/pca-using-python-scikit-learn-e653f8989e60
https://plot.ly/ipython-notebooks/principal-component-analysis/
https://pypi.org/project/factor-analyzer/
https://plot.ly/python/line-and-scatter/
https://towardsdatascience.com/lets-make-a-map-using-geopandas-pandas-and-matplotlib-to-make-a-chloropleth-map-dddc31c1983d
https://plot.ly/python/box-plots/
https://github.com/pauljeon/airbnb-data-analysis/blob/master/analysis.ipynb  
http://jonathansoma.com/lede/foundations-2017/classes/geopandas/mapping-with-geopandas/ 
http://geopandas.org/gallery/plotting_with_geoplot.html 



