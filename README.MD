### Overview 

## Airbnb 1 (more data cleaning)
1) Source - [Kaggle](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata/data) published by Arian Azmoudeh
2) Developed a custering algorithm to get rid of missing location data on neighborhoods and neighborhoods groups 
3) Interactive maps (Plotly express) and data vizualizations 
4) Analyzed with Natural Language Toolkit (NLTK) the top adjectives used in the listings 
5) Created additional indicators from the listing text decriptions (e.g. "no smoking" / "no pets") 
6) Modeled an neural neutwork to predict the price of the lisitngs with TenserFlow 


## Airbnb 2 (official data with more variables)
1) Source - [Airnb](https://insideairbnb.com/get-the-data/) March 2024 New York City
2) Built indicators out of the listed amenities (e.g. "Bathtub" , 'Dedicated workspace', 'Room-darkening shades' ) resulting in 0.3 incremental R^2 using all other variables (like room type, number of beds and others). Also spread out in a similar way the property types to get more accurate representations of the listings. 
3) Vizualized data with graphs and made an interactive html map (Folium)
4) Compared the performance of OLS Regression, Decision Trees, Neural Network and XGB Regression 