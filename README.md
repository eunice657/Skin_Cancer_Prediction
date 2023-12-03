# Skin_Cancer_Prediction
This model is built of the Kaggle Dataset containing approximately 4,0000 images of malignant and beningn moles.This is the link to the dataset;https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign 
The project first starts by importing the necessary libraries such as Keras and Tensorflow. The data is then loaded into the notebook. The images are then turned into numpy arrays using their RGB vlaues. The images are already in the Standard form ( 224*224) therefore there's no need to reshape them.
Labels for the y-values are then created and the data is combined and split into training and testing sets. The labels are onehot encoded and the X data is normalised

Using the matplotlib library, images in the train dataset are displayed.

#Training
Our model is trained using the Resnet 50 pre trained model provided by Tensorflow which has been trained using Imagenet. The Resnet model is fed the images and builds a build based of its previous knowledge. The model performs very well with an accuracy of approximately 95%. The model is then tested, trained ,saved and used for deployment.

#Deployment
Deployment was done using Flask

https://drive.google.com/drive/folders/1WwW2bAa2H22R52m634GoYPNHNGGU8-Tk
The link above contains the datasets used in the training of the model, the saved model and the deployment model.
