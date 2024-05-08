# SML312_Final-Project
This was done as part of my final project for SML312-Research Projects in Data Science. 
The project is centered around predicting forest fires in trail routes of the Table Mountain, South Africa.
This is particularly important because previous researches didn't focus on trail routes, and I think this is 
fundamental because most of the forest fires happen in the mountaneous regions of South Africa. 

I obtained my dataset from three different sources: AllTrails, NOAA website, and NASA Firms website. I performed 
geospatial clustering to combine the three datasets by creating polygons and classifyign features on the basis
of their closest distance to a particular polygon. I then used 3 models: Logistic Regression, Random Forests, and
Histogram-Based Gradient Boosting Classifier. It was found out that the Histogram-Based Gradient Boosting Classifier
was the best model that gave me the lowest rate of false negatives. 
