# pneumonia_xray_detection_transferLearning

In this project  a powerful CNN model was built to detect the potential presence of pneumonia in human X-Ray Images.
The dataset used for this project can be found below.
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

First a model was developed from scratch. Keras Tuner was used in hyper parameter tuning. This model didn't show promising results.So, through the concept of transfer learning the vgg16 architecture was used to develop a better model.
Quick guide to the vgg16 architecture -> https://neurohive.io/en/popular-networks/vgg16/

MODEL 1(From scratch):
<img width="1200" alt="Screenshot 2022-05-21 at 8 23 35 AM" src="https://user-images.githubusercontent.com/52528480/169685533-24b66a1f-fe44-4318-9c28-99c83846e32e.png">
