# Product_Classification_Cosine_Evaluation

Here we are trying to solve a problem which is basically related to Product Category Classication

### We can try to solve this problem with different ways as we have smaller set of data and even textual data is not that much
* Content Engine is a optimum way around if we have good amount of textual description.
* Topic Modelling is also a explicit solution for such type problem as topic handling may give us better range of topics from Textual data and thus we may be able to define the textual semantic's in better way.

### Data Preparation plays a vitals role for this type of data set
We have two colunms which are as follows:-
* G/L  - Product ID
* Text - Product description

### Data Modeling and Preprocessing
* Use of TFIDF is important because IDF is playing a important role is this type of experiment.
* We are taking specific range of training set from the complete data which are having more number of same product ID's.
* We are taking specific range of testing set from the complete data which are rest then training set.

### Models which we are using for this type of experimental analysis
We are using below models for training and testing for prediction:-
* SVC (Support Vector Classifier)
* Mutinomial NB
* Gaussian NB
* Random Forest Classifier

## Future scope
* Fuzzy logic implementation will be helpful because pattern  extraction is helpful.
* Better textual data collection
