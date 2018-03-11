# gender

Slide for presentation: https://docs.google.com/presentation/d/1AZf7D9uWLrMevYMrb4MioxuOBn_tKjE5MMFB-yTozgg/edit#slide=id.p

Feature:

1: Face detection: detect the face in a photo.

2: Face recognition/classification: classify the gender of the detected face.

Design Overview

1: Face detection: The OpenCV(Open Source Computer Vision) module would be used to detect the face.

2: Face recognition: PCA(Principal Component Analysis) would be used to reduce the dimension. KNN(K-Nearest-Neighbors), SVM(Support Vector Machines) and Logistic Regression would be used to do the gender classification.

3: Parameterization: k-fold cross-validation approach would be applied to avoid over-fitting scenario.

4:Model assessment: AUROC (area under ROC curve) will be used to evaluate the accuracy of results and the performance of algorithms.

Verification

Train/Test data: data will be divided into the train dataset and the test dataset. The train dataset would be used to develop the algorithm and the test dataset would be used to evaluate the performance of the algorithm.
