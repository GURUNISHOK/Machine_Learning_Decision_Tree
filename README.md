# Machine_Learning_Decision_Tree
The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. 
These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are 
more of a result of ecological processes rather than forest management practices. Each observation is a 30m x 30m patch. 
You are asked to predict an integer classification for the forest coverage type. 
The seven types are:
1 - Spruce/Fir
2 - Lodgepole Pine 
3 - Ponderosa Pine
4 - Cottonwood/Willow
5 - Aspen
6 - Douglas-fir 
7 - Krummholz


This repository is working on a csv file (dataset.csv) which is mainly on the training purpose.
For better training purposes, The dataset was splitted into a 80-20% train-test dataset with the k-fold cross validation in order 
to build our model. This assignment we will experiment with the adaboost classification algorithm using a base learner like
logistic regression. We will not use an ensemble learner here. 

I have divided the program into various tasks, which starts by running the adaboost algorithm on the given dataset 
with different number of rounds (say from 1-100). For each of those values i.e, the number of rounds the training accuracy 
and test accuracy are being computed. After we run the base learner on the given datasets and we record the training and test accuracy.
Then the curves are being plotted between the training and test accuracy of adaboosting and the base learning classifier on the y- axis 
and x- axis respectively. There are some interesting things that we found when adaboost for 1 round or 2 round or more. This built 
adaboost model will be used to predict the cover_type for every row in the judge set which has about 565892 observations.


