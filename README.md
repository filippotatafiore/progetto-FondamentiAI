# progetto-FondamentiAI

Building upon the previous tasks of data preparation, cleaning, and exploratory analysis, this project develops and tests different machine learning algorithms.
These algorithms are aimed at predicting specific outcomes based on the dataset.

**These algorithms from scratch and may use machine learning frameworks only for verifying the quality of your results.**


### Algorithms to Implement:
* **Linear Regression** *to predict the Weight of individuals based on the available attributes.*
* **Decision Trees** *for Binary Classification: To classify individuals into two categories of obesity levels (NObesity attribute) based on the available attributes.*
* **Logistic Regression** *to classify individuals into two categories of obesity levels (NObesity attribute).*
* **K-Nearest Neighbors (KNN)** *to classify individuals into two categories of obesity levels (NObesity attribute).*
* **Neural Network** *to perform regression in order to predict the Weight of individuals based on available attributes.*

The model should be flexible and allow for a variable number of layers and a variable number of neurons for each layer. These two are hyperparameters of the NN as well as the other "more traditional" hyperparameters.

### Data Preparation:

Categorical attributes defined as strings must be encoded before being used as input to the algorithms. You may choose an appropriate encoding method.
For regression problems, predict the attribute Weight.
For classification, predict the attribute NObesity. Binarize the NObesity attribute such that categories below and including "Overweight" are encoded as 0, and the rest are encoded as 1.


### Implementation Guidelines:

The implementation must not use any external machine learning frameworks except for verifying the results. For example, use scikit-learn to double check your results but not to fit thye model.
External frameworks can be used to do everything except build the model. For instance, you can use Pandas to manage dataframes, or you can use scikit-learn to evaluate the performance of your algorithms.
For each algorithm, tune the hyperparameters. While exhaustive search is not present, the process of hyperparameter tuning and how it can be extended to explore more options is clearly indicated.

### Critical Analysis:

Conclusion: a critical analysis section. This includes observations drawn from the experiments with the implemented algorithms. Also the performance, strengths, and weaknesses of each algorithm based on the results are discussed.

### Hyperparameter Tuning:

The process of tuning hyperparameters is clearly documented for each algorithm. There is a discussion on the impact of different hyperparameters on the algorithm's performance and how further tuning could potentially improve the results.
