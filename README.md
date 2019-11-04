# Face-Filter
A Face-Filtering Machine Learning model using OpenCV and Keras.

- OpenCV HAAR casade model is used for detecting face from webcam.
- Keras is used for training and building a model for detecting points in the face and placing sunglass using detected points.
  

After cloning the repo :

- Download dataset (training.csv, test.csv) [ here..](https://www.kaggle.com/c/facial-keypoints-detection/data)

- create a directory called 'data' and place the downloaded files.

- run 'python model_builder.py'

- run 'python shades.py'