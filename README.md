# Overview dsend_project_1:
- [Repository content](#Repository_content)
- [Software requirements](#Software_requirements)
- [Motivation](#Motivation)
- [Summary of results](#Summary_of_results)
- [Acknowledgements & licensing](#Acknowledgements)

## Repository content:<a name="Repository_content"></a>
This repository includes the .ipynb file for the first project of the Udacity Data Scientist for Enterprise Nanodegree.
The .shp and gzipped .csv files with the geographic & Airbnb data were partially too large to be uploaded to this repository. I thus have not uploaded any data. Nonetheless, the data can be found here:

- Airbnb data on Munich: http://insideairbnb.com/get-the-data.html; All files from 25 November 2019 [accessed 01 February 2020]
- OpenStreetMap on Upper Bavaria: http://download.geofabrik.de/europe/germany/bayern/; filename: "oberbayern-latest-free.shp.zip" [accessed 06 February 2020]

## Software requirements:<a name="Software_requirements"></a>
Python version 3.x & the followings packages:
- geopandas==0.6.3
- matplotlib==3.1.1
- numpy==1.17.4
- pandas==0.25.3
- seaborn==0.9.0
- shapely==1.7.0
- sklearn==0.22
- For geopandas you will need (next to shapely) to install further libraries on a Windows machine:
  - Fiona==1.8.13
  - GDAL==3.0.4
  - pyproj==2.4.2.post1
  - rtree==0.9.3

To run this .ipynb file, I used Jupyter Notebook.

## Motivation:<a name="Motivation"></a>
Munich is well known for its high cost of living in Germany & for the Oktoberfest internationally. It is an attractive destination for tourists from all around the world. In other words, the increased price level & the amount of visitors should be taken into consideration when you plan a trip to go there. I was curious whether this is actually reflected in the prices at Airbnb. My questions thus addressed pricing, timing, location, & availability of listings on Airbnb in Munich. 

## Summary of results:<a name="Summary_of_results"></a>
For the context of my results, please refer to this blog post: https://medium.com/@lezneklihp/airbnb-take-me-to-munich-97915e40f579

- **When was the most expensive time to book an Airbnb listing in Munich in 2019?**
Prices for listings were the highest during Oktoberfest.

- **Where were the most expensive listings located?**
Central areas were the most expensive.

- **When were the most listings available?**
The number of available listings was the highest in the first quarter of the year.

- **Are there any aspects of a listing which allow to conclude whether a listing is available?**
Conclusions on the availability of a listing based on certain aspects of a listing are random.

## Acknowledgements & licensing:<a name="Acknowledgements"></a>
- Thanks to Airbnb & OpenStreetMap for publishing data.
- Thanks to Geoff Boeing for his straightforward explanation of how to install the geopandas package & its dependencies.

- Airbnb data are licensed under Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication"
- OpenStreetMap data as of 2020-02-06T21:59:01Z are licensed under the Open Database 1.0 License; https://www.openstreetmap.org/copyright
