The CA03 is about Decision Tree Algorithm
There are a totle of 8 steps in this python notebook including:
1. Data Source and Contents
2. Data Quality Analysis (DQA)
3. Build Decision Tree Classifier Models
4. Evaluate Decision Tree Performance
5. Tune Decision Tree Performance
6. Visualize Your Best Decision Tree using GraphViz
7. Conclusion
8. Prediction using your “trained” Decision Tree Model

In Data Source and Contents, we could get to know our data by importing it into our python notbook, checking info and size.

In Data Quality Analysis (DQA), I defined missing values, otliers, and duplicates. Also, we could take a closer look of each values inside each columns better so we may drop the unusful cloumn for a better data quality in the later test performance

In Build Decision Tree Classifier Models, I first used one hot encoding to transform the dataset, and split it into the test and train data so we can build a basic decision tree model.

In Evaluate Decision Tree Performance I ran a few tests based on confusion matrix, accurcy score, precision score, recall score, and F1 score. The classification report was provided at the end.

In Tune Decision Tree Performance, I mainly used four important parameters including split criteria, minimum sample leaf, maximum features, and maximum depth to define the best model. At each run time we choose the best parameter with the highest accuracy score for building the next model, and finally the best model was found on the 5th run with the best values of parameters plugged in.

In Visualize Your Best Decision Tree using GraphViz, since I found the best model, the decision tree could be built based on it, setting up with the best values and the tree was created perfectly.

In the conclution and Prediction using your “trained” Decision Tree Model, there were 8 question being answered based on the coding experience, following the progress, the answers can be found based on the output, please see Xi_Chen_6070_CA03 for more details.
