![109996-machine-learning-wallpaper](https://user-images.githubusercontent.com/88277713/159684094-4ba9411a-dcb8-4ebc-8170-a06251659bcc.jpg)

CONTENT

[0. What is Computer Vision ?](https://github.com/Dodger22/Computer-Vision-Processing#what-is-computer-vision-)

[1. Writing Type Recognition Project](https://github.com/Dodger22/Deep-Learning#1-writing-type-recognition-project)

- [1.1. Object](https://github.com/Dodger22/Deep-Learning#11-object)
- [1.2. Summary](https://github.com/Dodger22/Deep-Learning#12-summary)
# What is Computer Vision ?

Computer vision is an interdisciplinary scientific field that deals with how computers can gain high-level understanding from digital images or videos. From the perspective of engineering, it seeks to understand and automate tasks that the human visual system can do.

Computer vision tasks include methods for acquiring, processing, analyzing and understanding digital images, and extraction of high-dimensional data from the real world in order to produce numerical or symbolic information, e.g. in the forms of decisions. Understanding in this context means the transformation of visual images (the input of the retina) into descriptions of the world that make sense to thought processes and can elicit appropriate action. This image understanding can be seen as the disentangling of symbolic information from image data using models constructed with the aid of geometry, physics, statistics, and learning theory.

[For more information](https://en.wikipedia.org/wiki/Computer_vision)

# 1. Writing Type Recognition Project
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
