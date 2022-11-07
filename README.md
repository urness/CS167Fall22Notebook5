# Notebook #5

For this notebook, you are going to demonstrate how to use the scikit-learn library to perform machine learning experiments for Random Forest, Principal Component Analysis, Support Vector Machine, Perceptron,  and Stochastic Gradient Descent.


## The Data :bar_chart: 
You will use the Wisconsin Breast Cancer Dataset (breast-cancer-wisconsin-data.csv) that we have used in the past (available in the Datasets section of the Blackboard website. The dataset is derived from the one here:  http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

The goal for this machine learning exercise is to use the scikit-Learn library implementations to make predictions if a medical scan indicates that a tumor is malignant (M -- Bad news) or benign (B -- Good news).

As the Support Vector Classifier, Perceptron, and Stochastic Gradient Descent are sensitive to feature scaling, it is highly recommended that you normalize the data prior to utilizing the algorithms. The starter code provided loads the data and normalizes it for you. (**No** cleaning of the data is required of this project.)

## The Exercises: 💪
This notebook assignment asks you to implement and test the following algorithms:
Random Forest, Support Vector Classifier, Perceptron, and Stochastic Gradient Descent.

As all of these algorithms utilize random numbers (e.g. establishing random initial values for weights), I strongly recommend establishing the algorithm with random_state = 0 as an initial parameter so that each execution of your algorithm has consistent results. 

First, run the basic scikit-learn algorithm with the default parameters and establish the baseline metric (accuracy and confusion matrix). Next, tune at least one of the parameters in each algorithm so that it makes some difference (hopefully positive) in your results.
1.  **Random Forest**: <br>
    a. Random Forest Classifier Default <br>
    b. Random Forest Classifier Tuned <br>
2.  **Support Vector Machine**: <br>
    a. SVC Default <br>
    b. SVC Tuned <br>
3.  **Perceptron:**<br>
    a. Perceptron Default<br>
    b. Perceptron Tuned<br>
4.  **Stochastic Gradient Descent**:<br>
    a. SGD Default<br>
    b. SGD Tuned<br>

5. Take your model that performed the best from the above models, and run a **Principal Component Analysis** on it to reduce the dimensionality of the dataset and try running this model again. 

6. Use a markdown cell to answer the following questions: <br>
  a. Which model performed the best? Why do you think this model performed the best?<br>
  b. What effect did the principal component analysis have on the accuracy of your best model? Why do you think this is the case?<br>

Lastly, as always, use a Markup cell to put your name at the top of the file. 

## Rubric :ballot_box_with_check:

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #            | Points Awarded | Notes |
| --------------------- | -------------------------- | ----- |
| 1: Random Forest Default and Tuned |        /1|    |
| 2: SVC Default and Tuned           |        /1|    |
| 3: Perceptron Default and Tuned    |        /1|    |
| 4: SGD Default and Tuned           |        /1|    |
| 5: PCA                             |        /1|    |
| 6: Conclusions                     |        /1|    |
| <b>Total                           |        /6| </b>   |
