# pneumonia_xray_detection_transferLearning

In this project  a powerful CNN model was built to detect the potential presence of pneumonia in human X-Ray Images.
The dataset used for this project can be found below.
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
The CNN model performs a binary classification as 'NORMAL' or 'PNEUMONIA'.

First a model was developed from scratch. Keras Tuner was used in hyper parameter tuning. This model didn't show promising results.So, through the concept of transfer learning the vgg16 architecture was used to develop a better model.
Quick guide to the vgg16 architecture -> https://neurohive.io/en/popular-networks/vgg16/

MODEL 1(From scratch):
<img width="1200" alt="Screenshot 2022-05-21 at 8 23 35 AM" src="https://user-images.githubusercontent.com/52528480/169685533-24b66a1f-fe44-4318-9c28-99c83846e32e.png">
<img width="474" alt="Screenshot 2022-05-22 at 1 59 05 PM" src="https://user-images.githubusercontent.com/52528480/169685862-298bf2d1-004e-4143-90df-626f61ed2785.png">


MODEL 2(VGG16):
<img width="1187" alt="Screenshot 2022-05-20 at 2 55 17 AM" src="https://user-images.githubusercontent.com/52528480/169685803-1e36757c-afb3-484d-9926-3ec8d9d7724a.png">
<img width="575" alt="Screenshot 2022-05-22 at 1 58 20 PM" src="https://user-images.githubusercontent.com/52528480/169685832-a8ee1919-974e-4fc2-ac07-00dc5e10c678.png">

The best results were obtained with the vgg16 architecture with 3 epochs.
