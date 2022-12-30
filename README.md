# Predicting and Mapping Danish House Prices

## Introduction


Predicting house prices is not only important to individual buyers and sellers, but also
for the establishment of real estate policies. Furthermore, house prices are an important
factor in determining the general state of the economy. There are many use cases for
unbiased models to predict house prices. The literature has established house characteristics like lot size or age and location features as the set of important price determinants.
This study obtains these information for the current danish housing market and builds a
prediction model using a lasso regression approach. The machine learning approach allows us to ask which set of features is most important to predict house prices in Denmark.
How accurately can the asking price for a house be determined only by considering it’s
characteristics? For the analysis we focus on currently listed prices of available properties on boligsiden.dk. We evaluate the predictive accuracy using the Root Means Square
Error (RMSE) and find that the location of houses in our dataset are the most important
set of attributes determining price. We further visualise spatial price differences in a
heatmap obtained from OpenStreetMaps (OSM).
The paper continues in the following structure. We first present previous studies
that shaped a trend towards machine learning methods. Second, we describe how we
obtained the dataset and present geographical visualisations. Third, we introduce our
theoretical framework and present our results. We end by discussing our results and
approach and concluding.
