# 1. Writing Type Recognition Project-  Without a library
[Project Code](https://github.com/Dodger22/Deep-Learning/blob/main/Writing_Type_Recognition.ipynb)

<img width="580" alt="sasasasasa" src="https://user-images.githubusercontent.com/88277713/159684619-783e03f9-0025-4eb9-9c2a-e546fde1cacf.PNG">


### 1.1. Object

My aim in this study is to create a libraryless neural network that predicts handwriting or printout with printout data and handwritten data, and learn the structure of the neural network.

### 1.2. Summary

The printout data in the model is the data from the OCR model. Handwriting data was taken from different sources. Model,  well predicts all outputs from the OCR model, but has difficulties in estimating a self-cropped picture. There may be a decrease in accuracy due to overfitting or related to the image quality of the pictures I tried.

- The input is a (256 ,64, 3) image which is flattened to a vector of size (49152,1)

- Train Data : 12000   - Accuracy : 0.983083
- Test Data : 5000 - Accuracy : 0.97880


 Confusion Matrix
- [2459, 41]
- [65,  2435]
