# **Fish Eating Classification**

by Naufal Syawali "Wallskiy"
A Notebook for coding test entry to company eFishery, the purpose is to classifying fish is they got eating process or not, 

### Problem Definition 

In this challenge case, we got datasets about fish movements by index X, Y, Z, in that moment, that will lead the fish into eating session. Meanwhile, fish which got eat the feed will be label as 1, and the other which not have eat labelled as 0

### Literature Review

Mohd Razman in his paper entitled "Hunger classification of Lates calcarifer by means of an automated feeder and image processing" said about before or after feeding fish has many significant features, it has been reported that the area where the fish roams could provide cue on the state of hunger, as the hungrier fish is, the larger the area that it tends to cover either in a group or individually. Also in his paper, machine learning algorithm is demonstrated, it has show that K-NN has effectiveness in classifying fish hunger, and Principal Component Analysis employed to extracting features also reduce the computational time.

### Proposed Methods

In this case, the author aims to make a Fish Eating Classification model using machine learning approach, KNN will be employed for the classification not only show the effectiveness and low computational time, KNN also prove has good performance in the previous literature about fish classification. In purpose searching the best model performance author will be adding Random Forest for comparing to the KNN. Meanwhile, PCA will be used for feature extraction from each dataset. **There is 3 scenarios that been implemented**, the goals is also to see which greatest scenarios and model for this dataset. Futher explanation of each scenario will explain in each scenario section code (you can see the header on the content list).

#### Scenario 1
In Scenario one, the author will propose to implement feature extraction (PCA) and modeling for each dataset, in short, all dataset will be tested separately.

<p align="center">
![Visual Example PCA Result in Scenario 1 using Plotly 3D](https://github.com/nsyawali12/fish-eating-classification/blob/10ac2808774f4795b260171fdfd251ba966643af/figure/visualize_pca_scene1.PNG)
</p>

#### Scenario 2
in Scenario 2, simply has the similarity to scenario 1 for the feature extraction using the PCA, but after each dataset has passed the PCA process, the result of each PCA of the dataset will be gathered as one dataframe, so for the modeling process, the author will use that dataframe after gather from all PCA process.

#### Scenario 3
in Scenario 3. All the dataset will be concatenated in the first place, so there will be only one dataframe, from the feature extraction using PCA until modeling process done.

### Conclusion

In this Challenge, From all the Scenarios that have been implemented, so far Random Forest Model 5 from Scenario 1 is the greatest model, with 95% accuracy. However, unlike any other scenario, scenario 1 has the consistency of testing, the accuracy shows increasing, starting from model result using data 1 until data 5, both KNN and Random Forest.

From the other scenarios which have concatenated data, each data has a good and clean quality, after combining the data, the new dataframe will be got saturated, so the performance is lower than scenario 1. In the lesson that the author learns, Random Forest has the ability to make the machine learning model for fish-eating classification. 

In further research, the author will try using Deep learning and adding some preprocess algorithm such reducting outlier, to know there is a possibility of increasing the performance of this dataset.

## Getting Started with the notebook
All you need to do just running all the cell from **google colab**, for futher detailed explanation of each step, you can see in jupter notebook file.
