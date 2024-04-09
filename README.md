# Sign-Language-Detection-project
#steps for mediapipemodel
1- install all packages required in requirment.txt
2- Import the required libraries.

3- Get the dataset
The dataset for gesture recognition in model maker requires the following format: <dataset_path>/<label_name>/<img_name>.*. In addition, one of the label names (label_names) must be none. The none label represents any gesture that isn't classified as one of the other gestures.
- In case of arabic data set
  you need to install kaggel, upload the kaggle.json api then download the dataset to a notebook unzip it, and use it
- in case of our data set,
   you need to get it from google drive folder unzip it, and use it
4-Load the dataset
Load the dataset located at dataset_path by using the Dataset.from_folder method.

5-Train the gesture recognizer by using the create method and passing in the training data, validation data, model options, and hyperparameters.
6-Evaluate the model performance after training the model, evaluate it on a test dataset and print the loss and accuracy metrics.
7-Export to Tensorflow Lite Model

#steps for the second model
1- install all packages required in requirment.txt
2- Import the required libraries.
3- Get the dataset
The dataset for gesture recognition in model maker requires the following format: <dataset_path>/<label_name>/<img_name>.*. In addition, one of the label names (label_names) must be none. The none label represents any gesture that isn't classified as one of the other gestures.
- In case of arabic data set
  you need to install kaggel, upload the kaggle.json api then download the dataset to a notebook unzip it, and use it
- in case of our data set,
   you need to get it from google drive folder unzip it, and use it

4-Load the data set using flow_from_directory method 
5- Model architecture 
6- compile the model
7- train the model 
8- get the gson file and h5 file 
9- code of deployment the model
