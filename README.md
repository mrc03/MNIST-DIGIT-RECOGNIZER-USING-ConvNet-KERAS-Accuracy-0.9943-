/*

    Author:: Raj Mehrotra
    Date:: 17-08-2018
    
*/

The MNIST DIGIT RECOGNIZER  COMPETITION ON KAGGLE. 

The training dataset consists of 42000 rows each of 784 pixel values thus representing 28 x 28 sized 42000 images of different digits from 0 to 9 . The test set contains 28000 images of again 28*28 pixel values.

I have trained Convolutional Neural Networks written in Keras on the model and predicted on the 28000 images of the test dataset. Also achieved 99.43% accuracy on Kaggle with 20 epochs . I have also used ImageDataGenerator to augment the training set and avoid overfitting problem .
