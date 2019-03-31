# American-Sign-Language-Recognition
Real time American Sign Language Recognition

![amer_sign2](https://user-images.githubusercontent.com/34737471/55292500-52acb580-5409-11e9-9a78-7cdc0d8da8b6.png)


### Requirements
  Python3
  Tensorflow
  Keras
  opencv
  Matplotlib

### sign2text
In this project I have used the kaggle American Language Recognition dataset.It takes live video from the webcam and predicts the alphabet 


### Neural Network
CONV2D->RELU->MAXPOOLING->CONV2D->RELU->MAXPOOLING->DROPOUT->CONV2D->RELU->MAXPOOLING->DROPOUT->FLATTEN->DENSE->DROPOUT-> DENSE->SOFTMAX

#### Optimizer - Adam

### Training Accuracy = 99.64% 
### Test Accuracy     = 97.02%



![download](https://user-images.githubusercontent.com/34737471/55292483-1c6f3600-5409-11e9-9bea-b5420129243c.png)


# Real Time Prediction using webcam-real-time.ipynb 
 The user has to put his hand inside the green box which is the region of interest and make the gesture the model predicts the alphabet which is made by the user 

Dataset link https://www.kaggle.com/datamunge/sign-language-mnist
