#blood-prediction
#AZUREGALLERYLINK: 
#BLOOD DONATION PREDICTION:https://gallery.cortanaintelligence.com/Experiment/Blood-Donation-Prediction-6
              blood donar prediction is a machine learning model uses liner regression on predicting the blood donation

#PROJECT DESCRIPTION:
               Application By solving this problem the blood donation camps can get 40% more blood donorsSourcerer Code RequirementThe example code is in Python (version 3.6.6 
               or higher will work).Dependencies import pandas import numpy import seaborn import matplotlib import Counter import sklearn Description Use Python to explore                      data related to blood donors and we want to predict whether or not a donor will give blood the next time when the blood donation will be organised.
               This process will be done  The code should run w/o errors. Appropriate use of data structures/types loops/conditional statements Packages functions coding                          practices (i.e. Docstrings, comments, variable names & general readability) Analysis Pose questions about the data Inspect the structure of the original data                      (very important) Clean the data Answer questions about the data using descriptive statistics Visualize the data (using plt and seaborn) Perform additional                         exploratory analysis Consider where data analysis can be applied to other fields. Feature Engineering Using domain knowledge of the data to create features                         that make machine learning algorithms work. Machine Learning Use of Random Forest, Extra Trees, Gradient Boosting, SVC classifiers. File Descriptions ./data/                        contains the various datasets. ./Blood Donation Prediction.ipynb is a Jupyter notebook containing the work I have done. References & Citations
              Data provided by kaggle 

#AZURE USED:
            Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the     evaluated model.

#BLOOD DONATION PREDICTION MACHINE LERANING MODEL:

![Screenshot (24)](https://user-images.githubusercontent.com/100461900/155834252-5f9f788d-948c-48cc-9885-e206eefc894e.png)

#DETAILED DESCRIPTION:
The above was the detail description of blood donation prediction Dataset was randomly partitioned into training set and testing set using a 80/20 train/test partition. Models are trained [3] using various algorithms using the entire training set, as well as trained on each cluster generated within the training set. Each model was trained once using what is referred to as a validation-set approach where there is one training set and one test set.Once models are trained, the [5] test (i.e. holdout) data is fed into each trained model to measure [6] model performance. These measures allow us to gauge the generalizability of the remaining subset of data not used in the study, and provides us a feel to the degree of how overfit any models with respect to the training data. Azure Machine Learning makes The statistical performance measures we obtained were overall accuracy, frequency, specificity,Monitary,time and class under the bar graph. The overall accuracy measures how well you classify donors versus non-donors (TP+TN/TOTAL)

#BLOOD DONATION PREDICTION:https://gallery.cortanaintelligence.com/Experiment/Blood-Donation-Prediction-6
