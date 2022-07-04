# cnn-image-classification-of-any-object-using-images-from-web
this a cnn model for image classififacation using images downloaded from the internet.
how it works-
1.first the training images are downloaded from the internet using bing image downloader.(you have to specify the name of the object to be downloaded)
2.these images are then saved to dataset dir and this dir contains all the classes that needs to be identified by the neural net.
3.then the sequential model which contains all convolution networks,dense layers ,etc is applied to classify the objects.
4.after training on epochs,our model is trained with some accuracy and we can now predict the objects using this neural net.
(note-
1.here,training data and validation data is same but you can split the image data into train and validation using split folders library or by any other means.
2.the accuracy of my model ranges between 40-100% (when the training and validation data was same)depending on the data it has collected from the internet.so always recheck the images it has collected,as this can decrease the accuracy score of the model.
3.you can also add or decrease the number of convolution networks or play with different activation function as per your need .)
