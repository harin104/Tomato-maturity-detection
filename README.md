****Machine Learning Pipeline for Tomato Maturity Detection****


The goal of this project is to train a machine learning model for sketch classification for tomato maturity detection. We divided this dataset into training (70%), validation (15%), and test (15%) sets .

Dataset
To reproduce the results of this work, make sure to modify the paths to the folders in the validation.py (lines 66, 130, 99) and main.py (line 67) modules. We have added comments on these different lines. The experiment.ipynb notebook calls all the other modules to train all the models. We have also saved the weights of all trained models, which you can download using the following link:

****Trained models****
Since we don't have enough resources, we trained all these models on Google Colab (GPU A100). Each of these models, except for the CNN trained from scratch, takes approximately 4 to 5 hours to train (maximum number of epochs set to 50 + early stopping strategies).
