# Signature-Forgery-Detection-using-CNN

In this signature forgery detection model, the system is trained using a dataset from kaggle that contains images of both genuine and forged versions of the same signature. A CNN model that has 2 convolutional layers, 2 dense layers is created using keras .The model is built with a sparse categorical crossentropy loss function and is trained over five iterations. The model finally gives the probability of any given sample in a mixed dataset of being forged and genuine. The accuracy value is also returned.
