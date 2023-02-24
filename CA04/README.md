The CA04 Ensemble Models contains the test of 4 important classifier models including the Random Forest, AdaBoost, Gradient Boost, and XGB. Using the 4 models to find the best Accuracy and AUC scores by graphing the changes and differences of Accuracy and AUC scores at each n_estimaor within the range from 50 to 500.
The Python Notebook contains 5 sections and 2 main questions answered at the end of section 5.
The first section is Data Source and Contents, this section has the data information, importing, cleanning, and transforming techniques provided.
The section section Finding Optimal Value of a key Ensemble Method Hyper-parameter contains the test models Accuracy Vs. max depth and AUC Vs. max depth.
The third section I built the Random forest model based on both the accuracy and AUC scores within the range of n_estimator from 50 to 500 to find the optimal value.
The fourth section has the similar process but with different classifier other than Random Forest. AdaBoost, Gradient Boost, and XGB classifier models were provided in this section with the same n_estimator range as above.
In section five, since there are a total of 8 model, 2 for each classifier on accuracy and AUC are created, the table could be created by using dictionary function to record the best Accuracy and AUC scores for each classifier models.
The last section are the two questions answere based on the observation about the 8 classifier models and if there are optimal values spotted.
