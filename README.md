# Dog-Behavior-Recognition

- The project involved developing the model using Convolutional Neural Network that detects the behaviour of a dog from the image provided.  Was having a labelled a dataset of 2000 Dog images based on various features like jaw, tongue, posture, sitting, standing, dog’s eyes and ears etc.
- Trained 3 models using CNN to determine a dog's activity and behaviour based on the features and then combined their outputs to predict the result.


Image Classification, one of the techniques belonging to object recognition can be used in analysing objects appearing in an image.

With the combination of results of three CNNs trained on custom images , the project presents an application of image classification to analyze the behaviour of a dog whether it is calm, angry, playful, curious or want to grab your attention and the activity it is doing, be it sleeping, running or sitting.

The MODEL1 is the first CNN trained on the classes of angry and sleeping images of dog. The MODEL2 is the second CNN trained on the classes of running and sitting images of dog. The MODEL3 is the third CNN trained on the classes of open and closed mouth images of dog.

The results after training the three models can show how a proposed architecture of CNN performs on different classes.

The first step is to create a custom dataset and transform it to feed into the input layer. For the three CNNs, downloaded around 350 images from google belonging to each class and then used generic data augmentation techniques to increase the training dataset three times. Later, converted all the images to grayscale and a fixed size of 100x100 which sharpened all of them.
![Screenshot (299)](https://user-images.githubusercontent.com/55136275/139580489-856c9844-81d2-4408-a4d4-f5020b3265d2.png)

The following is the architecture of the CNN created, the information of the various layers and the activation function used:
![Screenshot (300)](https://user-images.githubusercontent.com/55136275/139580519-316a4784-8d4e-4098-840b-e544fa68bc94.png)

We have trained three models which have given varying accuracy and this way we were able to observe and comment on how CNNs perform on different datasets.

Later we combined the output of all models and predicted the behaviour and activity done by the dog in the input image.


