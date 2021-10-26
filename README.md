# Ensemble-techniques-ML
 Ensemble methods is a machine learning technique that combines several base models in order to produce one optimal predictive model. </br >
 <h1>Types of Ensemble Methods</h1 > </br >
1. BAGGing, or Bootstrap AGGregating. BAGGing gets its name because it combines Bootstrapping and Aggregation to form one ensemble model. Given a sample of data, multiple bootstrapped subsamples are pulled. A Decision Tree is formed on each of the bootstrapped subsamples. After each subsample Decision Tree has been formed, an algorithm is used to aggregate over the Decision Trees to form the most efficient predictor. The image below will help explain: </br >
![image](https://user-images.githubusercontent.com/67821036/138849236-e12e1b0b-4a9d-4a9c-898d-831aec300608.png)

2.Random Forest Models. Random Forest Models can be thought of as BAGGing, with a slight tweak. When deciding where to split and how to make decisions, BAGGed Decision Trees have the full disposal of features to choose from. Therefore, although the bootstrapped samples may be slightly different, the data is largely going to break off at the same features throughout each model.
