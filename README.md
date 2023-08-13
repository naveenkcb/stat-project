# stat-project

This project was created as part of final data project in my STAT 420 coursework.

Introduction
From an outsider’s perspective, the Airbnb platform has revolutionized the renting of rooms much as Uber has revolutionized ridesharing. Airbnb allows users of the platform to monetize property that they would not be able to otherwise. In order to determine if renting out a room is a good business case or worth the owner’s time, it would be helpful to have an estimate of how much income the room would generate. Our proposal is to develop a model, trained on the London Weekend Airbnb data, that could predict the room rental income based on predictors known to the person putting the room up for rent. The data is available on Kaggle at https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities, and from the original authors, Gyódi, Kristóf and Nawaro, Łukasz at https://zenodo.org/record/4446043#.Y9Y9ENJBwUE.

In this model, the below steps were taken
- Exploratory data analysis
  -   covert discrete numeric variables to factors
  -   determine outliers
  -   remove outliers
  -   plot historgram and box plots
- Model building & selection
  -   Additive model, interaction model, log transformations
  -   AIC and BIC selection
  -   Determine final model
  -   test and train split to find overfit
  -   Cross validated RMSE, better R2 for explanation
- Conclusion & Report
  -    write up and explain why the chosen model is the best model for predicting the airbnb prices
  -    also explore any additional limitations and improvements to the dataset parameters or models which can improve the model
    

# Technologies
R
