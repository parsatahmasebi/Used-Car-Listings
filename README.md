# Used-Car-Listings
The goal of this Analysis was to find the features which both buyer and seller should consider before buying a used car.


Buying a used car online is easier than it has ever been. In 2019, there were almost 41 million used cars sold in the United States, compared to only 17 million new car sales.  Additionally, the coronavirus pandemic has made the used car market surge to levels it hasn’t seen in over 50 years (See Appendix I).  Used cars are often more affordable of an investment than purchasing a brand-new vehicle from the dealership, which partially explains why there is consistently a larger volume of used cars purchased per year than new cars; other reasons include purchasing “project” cars, purchasing rare cars that are hard to find, and purchasing older vehicles that are not made anymore. With such a large and growing demand for used cars, our team sought to analyze what features of a used car tend to increase its resale price.

We used car listings on Craigslist in order to build our predictive models and draw conclusions about important features that increase a car’s resale value. The data we used contained a car’s list price (the dependent variable), the car manufacturer, the model year, the odometer reading, and other information about the car. We decided to predict the dollar amount of a used car listing by building a linear regression model, as well as classify a used car as one of the “very low”, “low”, “mid-high”, and “high” priced using Naïve Bayes and Random Forest models.

As a result of the analysis, two of our models performed quite well, with the linear regression showing a strong correlation with the predictors and the random forest giving a decent overall accuracy. However, Naïve Bayes did not perform as well. We used the information gain method to select the most important features and  build our machine learning models, but this ended up reducing the overall accuracies.

