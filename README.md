# **Data Mining**  

**Purpose**  
The repository consists of selected assignments which were handed in for the "_Data Mining_"-course at the University of Konstanz in winter term 2019/20 by Marius Groen. Its purpose is to provide a small insight into my current skills in the area of data mining as well as data preparation, problem handling, and basic visualisations.  

**Author**  
Marius M. Groen  

**Tasks are given by**  
Department of Computer and Information Science  
Dr Johannes Fuchs, University of Konstanz  

**Disclaimer**  
Only partial practical applications from the course are shown in here. Even though the course is not limited to the following materials, the attached Notebooks provide a glimpse of the most central use-cases.  


***


### **Summary of Content**  

- Principal Component Analysis  
- Decision Trees  
- Pruning of Decision Trees  
- Naive Bayes  
- k-nearest Neighbors  
- Evaluation of Classifiers  
- (Feed-Forward) Neural Networks and Perceptrons  
- k-Means Clustering  
- k-Medoids Clustering  
- Expectation-Maximization  
- Linkage-Based Clustering  
- DBSCAN  
- Cluster Compactness Measurements  
- Cluster Quality Evaluation  


***


### **Assignment 01**  

In the first presented assignment, _Principal Component Analysis_ (PCA) was introduced. In this, a random two-dimensional dataset was created to calculate the principal component which could then the used to reduce the number of dimensions. The transformation of the data has shown that the first principle component covers over 90\% of the data variance, therefore being a good choice if one were to reduce dimensions.  

Following, a method for _Linear Interpolation_ was implemented which can be used to impute missing values.  

In the end, _Decision Trees_ were introduced by not only completing the classification task by hand but also performing classification with the famous iris-dataset using sklearn's implementation of the Decision Tree.  


***


### **Assignment 02**  

In the second presented assignment, _Decision Trees_ have been further deepened by introducing the options of pre- and postpruning in the classification of diabetes.  

In addition to that, _Naive Bayes_ has been used to not only calculate a ham/spam-classification by hand but also classify hand-written numbers in the example dataset of sklearn.  


***


### **Assignment 03**  

In the third presented assignment, the basics of _Feed-Forward Neural Networks_ are given as an example to work on. In this, the output values for each neuron after a single iteration had to be calculated by hand.  

This is followed by the individual implementation of a _Perceptron_. This should take on the learning rate as well as the number of iterations as input parameters. This should then be tested on AND, OR, XAND, and XOR gates. Furthermore, sklearn's perceptron was used to once again classify flowers in the famous iris-dataset. This classification should then be visualized featuring the decision boundaries.  


***


### **Assignment 04**  

In the fourth presented assignment, tensorflow and keras have been used to build a small neural network for recognizing hand-written numbers from keras' mnist dataset. In this task, _One-Hot Encoding_ was introduced as well as different activation functions and the optimizers _Stochastic Gradient Descent_ (SGD) and _ADAM_.  


***


### **Assignment 05**  

In the fifth presented assignment, classifiers were evaluated using not only _Accuracy_ on test- and training-data but also _Precision_, _Recall_, and the _F1-Score_. For this, three of sklearn's implemented classifiers were used: Naive Bayes, Decision Trees, and k-nearest Neighbors. Before initializing the classifiers, data preprocessing was necessary. In order to generate the measurements of quality that have been mentioned above, it was necessary to construct a method for calculating _Confusion Matrix_. The overall results then showed that each classifier had its strengths and weaknesses. Therefore, the choice of model heavily depends on the task's goal.  


***


### **Assignment 06**  

In the sixth presented assignment, _Clustering_ of data using _k-Means_, _k-Medoids_, and _Expectation Maximization_ has been introduced. Whereas k-Means was performed by hand, the PAM-implementation of pyclustering has been used. On the example of partitioning around medoids cluster compactness measurements have been taught. For example, the calculating of total distances had to be implemented. Therefore, the optimal value for k could be found.  


***


### **Assignment 07**  

In the seventh presented assignment, the search for the optimal k was further continued. Introducing the _Silhouette Coefficient_ within a clustering task using k-Means led to an estimation of uncertainty within clustering tasks.  

After that, _Linkade Based Clustering_  was applied by using _single_- as well as _complete_-linkage manually on a small example-dataset. In this, _Dendrograms_ have been introduced as well. This chapter was completed by the _DBSCAN_-algorithm and another manual clustering task.  
