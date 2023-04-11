# BigData-Pyspark
Multi-Class Image Classification Using Pyspark

The given BigData project leverages pyspark to perform Multi-Class Image Classification
We have used a Bird Image Dataset from Kaggle using Bird-510 species Image Classification.
Data set of 515 bird species. 82724 training images, 2575 test images(5 images per species) and 2575 validation images(5 images per species).

The model uses Logistic Regression and Random Forest Classifier to achieve an accuracy within mid 90% range

The significant contribution achieved here is a method to handle data stored in file directory structure where the directory name indicates the class label
It also implements how to extract, process and transform features from images and use them to train models.

The notebook was trained on google colab with spark alloted 12gb of memory to be able to process the images.
