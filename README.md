# Leaves-Diseases-Detection-Using-Tensorflow-Lite


To find out whether the leaf is diseased or healthy, certain steps must be followed. i.e., Preprocessing, Feature extraction, Training of classifier and Classification. Preprocessing of image, is bringing all the images size to a reduced uniform size. Then comes extracting features of a preprocessed image which is done with the help of Convnets. 

Collected of Dataset: Dataset is being collected from Kaggle and it is divided into 2 main folders i.e., train and test folders which consists of bacterial blight, Green Mite, Brown Streak, Mosaic and Healthy. The Dataset is splitted into training and testing set with the ratio of 80/20 respectively.

Preprocessing and Training the model (CNN): The database is Preprocessed such as Image reshaping, resizing. Similar processing is also done on the test image [8] provides the description about the number of pixels available in the given color ranges
•	The train database is used to train the model (CNN) so that it can identify the test image and the disease it has. CNN has different layers that are Dense, Dropout, Activation, Flatten, Convolution2D, MaxPooling2D. 
•	After the model is trained successfully, the software can identify the disease if the plant species is contained in the database. 
•	After successful training and preprocessing, comparison of the test image and trained model takes place to predict the disease and saving the model in .h5 format

•	Using TensorflowAPI, saved model had been deployed into it and importing all necessary libraries,  you can access those files while making APK.
