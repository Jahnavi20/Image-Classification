# Image Classification
## Introduction
The aim of this project is to help identify whether a specific flower is toxic or not. Aconitum, also known as wolfsbane, is the first flower on the list of lethal flowers. Most deadly flowers are believed to be beautiful. However, not all beautiful flowers are toxic. Unfortunately, people may be more likely to smell or touch a flower when it looks appealing, resulting in exposure to toxins, such as in the case of aconitum. To achive this we aew using a Convolutional Neural Network (CNN) to classify images of flowers as toxic or non-toxic.
## Methodology
1. **Data Collection**: The first step is to collect data for the model. Using the Bing Image Downloader, we downloaded 200 images of Aconitum and 200 images of roses. These images were then resized to 1./255.
2. **Data Preparation**: Next, we divided the data into three sets, a training set, a validation test and a test set. The training set was used to train the CNN, while the validation set was used to improve the performance of the model and test set was used to evaluate the performance of the model. We also created labels for each image, specifying whether it is toxic or non-toxic.
3. **Model Building**: We built a CNN model using Keras, which is a high-level neural networks API. The model was built using MaxPooling, Dense, and Flatten layers. The model was compiled using binary cross-entropy as the loss function and Adam as the optimizer. We also specified accuracy as the metric to evaluate the performance of the model.
4. **Model Training**: The model was then trained using the training set. We set the number of epochs to 50, batch size to 10 and, the steps per epoch to 12. We used the validation set to evaluate the model's performance after each epoch.
5. **Model Evaluation**: After training, we evaluated the performance of the model using the test set. We calculated the accuracy, loss, confusion matrix, support, precision, recall, and F1-score to determine the model's performance.
## Model Architecture
  ![image](https://user-images.githubusercontent.com/48169929/226818748-72bc7f78-aa19-4329-8ceb-0ee35542b0a6.png)
## Model Evaluation
### Validation Set
  ![image](https://user-images.githubusercontent.com/48169929/226819192-49377ccc-20dd-4486-9bb9-bfd1fca85695.png)
### Test Set
  ![image](https://user-images.githubusercontent.com/48169929/226819276-04085b82-1f77-403f-beee-50819730ec01.png)



