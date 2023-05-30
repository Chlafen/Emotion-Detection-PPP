# Emotion-Detection-Udong-Deep-Learning/Comuter-Vision
The project aims to develop a deep learning model using CNNs to accurately classify facial expressions into seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
The FER-2013 dataset will be used for training.

Realised by: Bouchnak Med Amine, Besrour Ines and Kaabachi Imen.

##PART 1: Data Preprocessing
We will be batching our dataset as it is very large and it would be inefficent to dump it all at once into memory. We will also be applying data augmentation to the dataset to further diversify the input data, we will use techniques such as... rotation, shifting, and flipping. This can improve the performance of our model.
Loading and preprocessing the dataset: The dataset consists of 48x48 pixel grayscale images of faces.

##Performing data augmentation

##Making the model:
Now that we have our train and test data ready, we will create a CNN model to train on our dataset.

Since we are not capable of coming up with a model from scratch, we found this interesting paper https://www.hindawi.com/journals/wcmc/2020/6677907/#EEq3 that proposes a CNN model for our purposes

##Training the model on our dataset
We will provide the model with our training data and validation data. We also export the model so we can later come back to it.

##Using the model
This section will first take detected faces, normalize them, feed them as a batch to our Emotion Detection model, and finally spit out the results.
The script should output each face's most probable emotion alongside other emotions' percentages
