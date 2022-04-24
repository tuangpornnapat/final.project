# final.project
This project is the classification of normal lung and COVID-19 pneumonia in chest x-ray images by using a dataset from Kaggle. This dataset contains 2 files, which are test and train. And in test and training files, it contains 3 folders, which are normal, pneumonia, and COVID-19 x-ray images. I used Google Colab for coding this project.
After importing the file into Google Colab, I installed a module that is used for designing CNNs, such as tensorflow, keras, matplotlib, etc. And I resized the images to (224,224) and classified them into 3 classes. Next, I created a CNN layer to train the model and used transfer learning, which is ResNet50 and VGG16, to improve the accuracy of the model. After using ResNet50, the test accuracy is 94.25%. While adding VGG16 into the model, the test accuracy increased to 95.57%. As a result, I randomly selected an image from the test file and let the model predict the answer. The result was that before I used ResNet50 and VGG16, the test accuracy was around 70% and it predicted the wrong answer when I used a COVID-19 x-ray image, but the predicted answer was normal. After adding ResNet50 and VGG16 into the model, it can predict the answer correctly.
