# Gender Prediction
After completing the A-Z Machine Learning Course by Kirill Eremenko in Udemy, I tried to work a small project to predict the gender of a person based on a picture provided.

The dataset was downloaded from Kaggle and consisted of approx 2800 training examples and 500 test examples of pictures of man and woman. I used tf.keras.models.Sequential() and implemented a CNN model with three hidden layers and 'relu' activation function. The model was compiled with 'adam' optimizer and with 25 epochs, the accuracy came out to be 83.48 %.

The video of the prediction can be watched in my linkedin profile.
### Dataset Link : https://www.kaggle.com/playlist/men-women-classification
### Linkedin Post : https://www.linkedin.com/posts/prachurya-nath-5a26b5189_machinelearning-deeplearning-udemy-activity-6695224856201502720-hecw

# New Update
I applied a transfer model named Inception V3 upon the same dataset. I learnt it on the Course 2, Convolutional Neural Networks in Tensflow of the Tensorflow Specialisation in Coursera. Here, data augmentation and dropout process is also applied getting a validation accuracy slightly better which can be seen in the following plots
![Accuracy](https://github.com/prachuryanath/Gender-Prediction/blob/master/transfer.png)
![Loss](https://github.com/prachuryanath/Gender-Prediction/blob/master/transfer2.png)
