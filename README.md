# CA-3
 **A brief description of the purpose of the program and what it is doing**

This program uses a dataset obtained from the Census Bureau to build decision tree classifier models. The dataset represents salaries of people together with seven demographic variables and a total of 48,842 instances. There are two target classes within the dataset – “>50k” and “<=50k” – which are labelled as 1 and 0 respectively. Before building decision tree classifier models, a data quality analysis is performed to analyze the distribution of every attribute, display the descriptive statistics of each column, create a data quality report and to perform the needed transformation to be able to apply to decision tree algorithm. Once the data quality analysis process is done, the program uses the “DecisionTreeClassifier” algorithm from scikit learn to build decision tree classifier model. The performance of the model is evaluated based on the confusion matrix along with the accuracy, precision, recall, and F1 Score of the model. From there, four hyperparameters – split criteria, minimum sample leaf, maximum feature, and maximum depth – are manually changed to tune decision tree performance and decide on the best tree based on accuracy. The performance of the best decision tree is then evaluated, and a visualization of this tree is provided. Finally, the program concludes by answering 7 questions related to analyzing and interpreting the output of the decision tree.

**The Needed libraries, modules, and classes**

There are a few libraries, modules, and classes that need to be imported to be able to run the code:

* The Numpy library needs to be imported to allow mathematical and scientific computations in Python.
* The Pandas library is needed for data manipulation, especially during the data quality analysis part.
* Matplotlib and seaborn libraries are also imported and are used for visualizing the distribution of each column during data quality analysis.
* The "LabelEncoder" class from the scikit-learn library is imported to encode categorical variables into numerical values so they can be used in the Decision Tree Classifier algorithm.
* The "DecisionTreeClassifier" algorithm is imported from the scikit-learn library. The module is used to build decision tree classifier models.
*	The confusion matrix function is imported from the scikit-learn libray’s metrics module to derive the confusion matrix of the decision tree, and thus evaluate its performance.
*	Sklearn.metrics: This module is also part of the sklearn (scikit-learn) library that provides metrics to assess the performance of machine learning algorithms. In this case the “accuracy_score”, “precision_score”, “recall_score”,  and “f1_score” functions are imported from this module in order to evaluate the performance of the decision tree.
*	To visualize the decision tree, the “export_graphviz function” from skicit-learn library is imported. The graphviz and the pydotplus libraries are also imported. Finally, to be able to display the decision tree, the Image function from Ipython display library is imported.

**How to install and run the code along with datasets to be able to run the program successfully**

To be able to install and run the code successfully, the dataset must be read as a csv file into the notebook and all the needed libraries and modules need to be installed/imported. Each block of code must also be run individually and in a sequential order (one after another). 

**Acknowledgement:**
The path used to access the data was provided by Prof. Arin Brahma (GitHub username: ArinB) using the link "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true". 

