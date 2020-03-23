# Mortgage_Default
Predicting mortgage default or payoff for a pool of residential mortgages backing RMBS

Data taken from Credit Risk Analytics

Several models were run with varying degress of success:
-logistic
-knn
-adaboost/gdboost
-random forest
-bayes

 








Model Results:

Logistic and Gradient Boost performed the best

GridSearch and Cross Validation were used to refine the models





Uses of the model:

The model can be used to predict if an individual loan will default or not

Can look at predicted defaults to take action prior to default

Can be used on a large, more general scale as an economic indicator 

Level of predicted defaults can be compared to current and past trends to see how defaults relate to economic strength

Since the loans are used to back RMBS instruments, the level of defaults can be used to indicate market movements

The models and their results can be useful to borrowers, RMBS issuers, investors, CDS sellers, and banks








Improvement and Future Work:

-more model types, parameter refinement

-predicting when the defaults will occur, either by calendar date or age of loan

-quantify RMBS losses

-fit models to different mortgage pools, possibly based on riskiness level of the pool

-compare defaults at different points in time
