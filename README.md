# CSCI316-Individual-Assignment-2

**Task 1**

Data set: Customer Churn Dataset
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

Objective
The objective of this task is to implement a Random Forest classifier based on a Decision Tree model which
you implemented in Task 2 of Individual Assignment 1. (Note. If you have implemented multiple DT models,
you can choose any one of them as the base model. The DT model which you use must be from Task 2 of
Individual Assignment 1.)

Task requirements
1) Clearly state which method you use for this Random Forest classifier.
2) Compare the performance of this Random Forest classifier and the performance of DT models which
you have implemented.

**Task 2**

Data set: MAGIC Gamma Telescope Dataset
(Source: https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope)

The data are Monte-Carlo generated to simulate registration of high energy gamma particles in a groundbased
atmospheric Cherenkov gamma telescope using the imaging technique. The dataset contains 19,020
records. 

Objective
Develop an Artificial Neural Network (ANN) in TensorFlow/Keras to predict the class.

Attribute information:
1. fLength: continuous # major axis of ellipse [mm]
2. fWidth: continuous # minor axis of ellipse [mm]
3. fSize: continuous # 10-log of sum of content of all pixels [in #phot]
4. fConc: continuous # ratio of sum of two highest pixels over fSize [ratio]
5. fConc1: continuous # ratio of highest pixel over fSize [ratio]
6. fAsym: continuous # distance from highest pixel to center, projected onto major axis [mm]
7. fM3Long: continuous # 3rd root of third moment along major axis [mm]
8. fM3Trans: continuous # 3rd root of third moment along minor axis [mm]
9. fAlpha: continuous # angle of major axis with vector to origin [deg]
10. fDist: continuous # distance from origin to center of ellipse [mm]
11. class: g,h # gamma (signal), hadron (background)

g = gamma (signal): 12332

h = hadron (background): 6688


Requirements
1) You can (but not must) use Scikit-Learn or other Python libraries to pre-process and visualise the data
set. However, the ANN must be implemented with the Keras API in TensorFlow.
2) You can use any ANN architecture (incl. feedforward, CNN, etc.) which has at least two hidden layers.
3) The training process includes a hyperparameter fine-tunning step. Define a grid including at least three
hyperparameters: (a) the number of hidden layers, (b) the number neurons in each layer, and (c) the
regularization parameter for L1 and L2. Each hyperparameter has at least two candidate values. All
other hyperparameters (e.g., activation functions and learning rates) are up to you.
4) Use 2/3 data for training and 1/3 for test. Report the loss values for training and test.
5) Present clear and accurate explanation of your ANN architecture and results.
