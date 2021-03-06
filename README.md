# American-Sign-Language-Recognition
Real time American Sign Language Recognition

![amer_sign2](https://user-images.githubusercontent.com/34737471/55292500-52acb580-5409-11e9-9a78-7cdc0d8da8b6.png)

## Files in this repository
preprocessing_and_training.ipynb contains the preporcessing and model and the real_time.ipynb is for real time Real time American Sign Language Recognition the third file is the trained file obtained from training the model on Gpu 

### Requirements
  Python3</br>
  Tensorflow</br>
  Keras</br>
  opencv</br>
  Matplotlib</br>
  Cuda 9.0</br>

### sign2text
In this project I have used the kaggle American Language Recognition dataset.The model takes live video from the webcam and predicts the alphabet based on the hand gesture made by the user using a Convolutional Neural Network  . There a total of 24 classes in the dataset. 


### Real Time Prediction using webcam
The user has to put his hand inside the green box which is the region of interest and make the gesture the model predicts the alphabet  made by the user 

### Neural Network
CONV2D->RELU->MAXPOOLING->CONV2D->RELU->MAXPOOLING->DROPOUT->CONV2D->RELU->MAXPOOLING->DROPOUT->FLATTEN->DENSE->DROPOUT-> DENSE->SOFTMAX


### Training Accuracy = 99.64% 
### Test Accuracy     = 97.02%

### Results
![1](https://user-images.githubusercontent.com/34737471/64022970-f20adb80-cb54-11e9-8343-01b2b6a540a0.PNG)

![2](https://user-images.githubusercontent.com/34737471/64023090-326a5980-cb55-11e9-8eda-e44398928fbf.PNG)
![3](https://user-images.githubusercontent.com/34737471/64023173-5af25380-cb55-11e9-8f99-40afee9a9656.PNG)

![download](https://user-images.githubusercontent.com/34737471/55292483-1c6f3600-5409-11e9-9bea-b5420129243c.png)

The trained model can be downloaded from this link [model](https://drive.google.com/open?id=1K-Nx2T7xTPAbsJ7DGE_rLhpHNshuHbRo)
## References
Dataset link https://www.kaggle.com/datamunge/sign-language-mnist
