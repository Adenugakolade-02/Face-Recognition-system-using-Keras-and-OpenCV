# Face-Recognition-system-using-Keras-and-OpenCV
This project was built to test and showcase my understanding of deep learning in computer vision
This project was built using Keras, and OpenCV. The dataset consists of a Train set of 305 pictures of me, my sister (Damola) and my mother (mummy Kay) and a test set of 73 pictures.

The process involves:
1. Collection of 378 images and cropping out the head of each image. 
2. I Created a train set containing 305 images and test set containing 73 images.
3. I Fed the train set into the InceptionResNetV2 model and used the imagenet weights.
4. I trained a model using 100 epochs.
5. I Achieved an average accuracy of 0.6 on test and 0.9 on the train set.
6. The real-time prediction was done using haarcascade_frontalface_default.xml and OpenCV. 
7. I used frontalface haarcascade to dectect images in my camera frame
8. Used OpenCV to: 
# a. Open and capture images from my camera frame, 
# b. Resize and change the colour frame of the image gotten from haarcascade_frontalface_default.xml
# c. Draw a rectangle around the image detected from my camera and display the prediction gotten from my model with its accuracy.
