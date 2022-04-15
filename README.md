# **Fish Eating Classification**

by Naufal Syawali "Wallskiy"
A Notebook for coding test entry to company eFishery, the purpose is to classifying fish is they got eating process or not, 

## Getting Started with the notebook
All you need to do just running all the cell from **google colab**, for futher detailed explanation of each step, you can see in jupter notebook file.

## Problem Definition 

In this challenge case, we got datasets about fish movements by index X, Y, Z, in that moment, that will lead the fish into eating session. Meanwhile, fish which got eat the feed will be label as 1, and the other which not have eat labelled as 0

## Literature Review

Mohd Razman in his paper entitled "Hunger classification of Lates calcarifer by means of an automated feeder and image processing" said about before or after feeding fish has many significant features, it has been reported that the area where the fish roams could provide cue on the state of hunger, as the hungrier fish is, the larger the area that it tends to cover either in a group or individually. Also in his paper, machine learning algorithm is demonstrated, it has show that K-NN has effectiveness in classifying fish hunger, and Principal Component Analysis employed to extracting features also reduce the computational time.

## Proposed Methods

In this case, the author aims to make a Fish Eating Classification model using machine learning approach, KNN will be employed for the classification not only show the effectiveness and low computational time, KNN also prove has good performance in the previous literature about fish classification. In purpose searching the best model performance author will be adding Random Forest for comparing to the KNN. Meanwhile, PCA will be used for feature extraction from each dataset. **There is 3 scenarios that been implemented**, the goals is also to see which greatest scenarios and model for this dataset. Futher explanation of each scenario will explain in each scenario section code (you can see the header on the content list).

### Scenario 1
In Scenario one, the author will propose to implement feature extraction (PCA) and modeling for each dataset, in short, all dataset will be tested separately.

### Scenario 2
in Scenario 2, simply has the similarity to scenario 1 for the feature extraction using the PCA, but after each dataset has passed the PCA process, the result of each PCA of the dataset will be gathered as one dataframe, so for the modeling process, the author will use that dataframe after gather from all PCA process.

### Scenario 3
in Scenario 3. All the dataset will be concatenated in the first place, so there will be only one dataframe, from the feature extraction using PCA until modeling process done.
