# Simpons Character Classifier

##  Description
This project creates a model which can detect a few characters from the reputated tv series The Simpons.
The characters include:
* krusty the clown
* charles montgomery burns
* ned flanders
* homer simpson
* milhouse van_houten
* principal skinner
* chief wiggum
* moe szyslak
* lisa simpson
* marge simpson
* sideshow bob
* abraham grampa simpson
* bart simpson

The model achieved an accuracy of 97.5% and was then able to successfully identify characters from the list based on users input.


##  Requirements
* Opencv
* Pandas
* Numpy 
* Opendatasets
* Matplotlib
* Random
* OS
* Tensorflow/Keras

##  Bugs and Fixes
In kaggle the dataset had around 40+ characters but the didnt have consistent images of all the characters, the popular characters had around 800 - 2000 (characters with more 700 images were used in this project) while the rest had less than 400. Therefore to avoid the skewed dataset problem, only characters with more 800 images were used
