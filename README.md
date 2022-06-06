# finding_donors
This is my attempt at the  Udacity's Introduction to Machine Learning with TensorFlow Nanodegree Program project for supervised learning.

The goal of this project is to construct a model that accurately predicts whether an individual makes more than $50,000. 
This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.

### Models
To this end, I employed the following supervised algorithms:
- K-Nearest Neighbors (KNeighbors)
- Adaboost, and
- Logistic Regression
<br>
 to accurately model individuals' income using data collected from the 1994 U.S. Census. 
 
 #### Best model
 The Best model is Adaboost because it has the highiest F-scores (74%) on the testing set when 100% of data is used in training. Although it takes longer than others to train, it is still has fast training time of 6 seconds when trained on 100% of the data. It also makes prediction very fast compared to KNN. Another reason to choose Adaboost is because it is easily explainable, since by default, it makes use of Decision trees that are very intuitive and easy to explain.
 
 ### Feature importance
 The imporatant features turn out to be:
 - number of work hours per week
 - capital gain
 - level of education
 - age, and
 - marital status

 
 
