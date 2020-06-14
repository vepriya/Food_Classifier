# Food_Classifier
### This repository the contains source code a of food classifier based on the deep learning with fine tunning of a pretrained model which will classify the category of food.
# Dataset
### The dataset consists of 16,000 images belonging to 11 major food categories:
Bread (1724 images)\
Dairy product (721 images)\
Dessert (2,500 images)\
Egg (1,005 images)\
Fried food (1,461 images)\
Meat (2,206 images)\
Noodles/pasta (734 images)\
Rice (472 images)\
Seafood (1,505 images)\
Soup (2,500 images)\
Vegetable/fruit (1,172 images)

organised the dataset according to the following manner to utlize the keras ImageDatagenerator for data augumentation.images are stored in the directory with their corresponding class/label name\
evaluation (3000 images)\
training (9800 images)\
validation (3200 images)

# Training
fine tuned a VGG16 model to build the classifier. remove the head of model, build a new fully connected head and place it on top of the original architecture of VGG16. trained the model on food dataset. 
To train the model run the file train.py

# Prediction
to predict the result on the new image pass the path of image in commmnad line while running the predict.py\
 example:- python predict.py --image C:\Users\PC\Desktop\Seafood/8_186.jpg



