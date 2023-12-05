# Skin_Cancer_Prediction
The actual models used are Cancer_Prediction and Skin_Cancer_Prediction1. However, for the testing and deployment, Cancer_Prediction was used.
This model is built of the Kaggle Dataset containing approximately 4,0000 images of malignant and beningn moles.This is the link to the dataset;https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign 
The project first starts by importing the necessary libraries such as Keras and Tensorflow. The data is then loaded into the notebook. The images are then turned into numpy arrays using their RGB vlaues. The images are already in the Standard form ( 224*224) therefore there's no need to reshape them.
Labels for the y-values are then created and the data is combined and split into training and testing sets. The labels are onehot encoded and the X data is normalised

Using the matplotlib library, images in the train dataset are displayed.

#Training
There are two different kinds of models trained, the first uses the Resnet50 model to extract the features and train another model using those features. The next model uses Resnet (without its pretrained weights) to train the model. The latter model performs best and is tested on a particular image to see if it can predict accurately and it did.



#Deployment
Deployment was done using Streamlit

https://drive.google.com/drive/folders/1WwW2bAa2H22R52m634GoYPNHNGGU8-Tk
The link above contains the saved model and the deployment model.
