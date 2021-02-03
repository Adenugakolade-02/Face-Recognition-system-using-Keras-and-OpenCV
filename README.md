# Face-Recognition-system-using-Keras-and-OpenCV
This project was built to test and showcase my understanding of deep learning in computer vision
This project was built using Keras, and OpenCV. The dataset consists of a Train set of 305 pictures of me, my sister (Damola) and my mother (mummy Kay) and a test set of 73 pictures.

The process involves:
1. Collection of 378 images and cropped out the head of each image. 
2. Created a train set containing 305 images and test set containing 73 images.
3. Fed the train set into the InceptionResNetV2 model and used the imagenet weights.
4. The model was trained using 100 epochs.
5. Achieved an average accuracy of 0.6 on test and 0.9 on the train set. Which is quite impressive.
6. The real-time prediction was done using frontal faceCascade.xml(haarcascade) and OpenCV. FrontalfaceCascade is used to detect faces in  the video, predicted the images and used OpenCV to display the prediction and accuracy.
This project was built to test and showcase my understanding of deep learning in computer vision
