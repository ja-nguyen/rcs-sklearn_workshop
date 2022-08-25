# Northwestern Research Computing Services - Machine Learning with Scikit-learn Workshop

## General Information
This workshop will cover the basics of Scikit-learn, the most popular Python package for predictive modeling and machine learning. Over three days, we will experiment with both supervised and unsupervised machine learning models, including linear/logistic regression, decision tree and clustering.

Prerequisites: basic Python knowledge at the level of the Python Fundamentals bootcamp; basic statistical knowledge is also recommended.

## Preworkshop Setup
Please have Anaconda installed as we will use Jupyter Notebook/Lab. 

It is also a good practice to create a new environment to avoid any issue with dependencies. Make sure to launch Jupyter Notebook/Lab from this environment. To create a new environment named sklearn_workshop, from your terminal:

```console
conda create -n sklearn_workshop python=3.7 pandas scipy matplotlib seaborn scikit-learn=0.24
```

It's fine to ignore this if you already have the packages above and you don't have any issue importing them in a Jupyter Notebook. There may be issues if your Python version is 3.10, which I think is the newest at this time.  

If you plan to work on Google Colab, please ignore this part.

## Accessing Files
### Downloading this entire directory
Click on the green Code button and choose Download ZIP. Unzip the folder. Change to sklearn_workshop in the drop down menu next to "Applications on"  and launch Jupyter Notebook/Lab and navigate to the folder you downloaded. Start with [placeholder].

### Links to the notebooks on Google Colab:
#### Day 1:

Preprocessing
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day1_1_Preprocessing.ipynb

Supervised learning - Linear Regression
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day1_2_LinearRegression.ipynb

Cross validation
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day1_3_CrossValidation.ipynb

#### Day 2:

Decision tree
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day2_1_DecisionTree.ipynb

Cross validation
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day2_2_CrossValidation.ipynb

#### Day 3:
K-means clustering
https://colab.research.google.com/github/ja-nguyen/rcs-sklearn_workshop/blob/main/Day3_1_KMeans.ipynb

## Cited Works
scikit-learn Tutorials

wikipedia

machinelearningmastery.com

https://neptune.ai/blog/k-means-clustering#:~:text=K%2Dmeans%20is%20a%20centroid,of%20groups%20in%20the%20dataset

https://neptune.ai/blog/clustering-algorithms
