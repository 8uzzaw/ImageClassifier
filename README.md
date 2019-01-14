# ImageClassifier

## Description 

Developed two models to perform the binary classification task on a set of images of bees. Specifically, training the models to distinguish between the honey bee (Apis) and the bumble bee (Bombus) solely relying on their images/appearance.
 
One model uses the Scikit learn machine learning library to classify the images. The images were split into training and testing data using the train_test_split method. Later after all the preprocessing and before training the model PCA or Principal Component Analysis was done to reduce the number of features in the arrays.

The other model makes use of Convolution, a concept of Deep Learning. The model was trained using Keras with multiple Conv2D (convolution in 2 dimensions), Max Pool 2D, Dropout and Dense (fully connected) layers.
