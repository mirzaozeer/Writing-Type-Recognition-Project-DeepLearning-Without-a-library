![109996-machine-learning-wallpaper](https://user-images.githubusercontent.com/88277713/159684094-4ba9411a-dcb8-4ebc-8170-a06251659bcc.jpg)

CONTENT

[0. Deep Learning ?](https://github.com/Dodger22/Deep-Learning#what-is-deep-learning-)

[1. Writing Type Recognition Project](https://github.com/Dodger22/Deep-Learning#1-writing-type-recognition-project)

- [1.1. Object](https://github.com/Dodger22/Deep-Learning/new/main?readme=1#11-object)
- [1.2. Summary](https://github.com/Dodger22/Deep-Learning/new/main?readme=1#12-summary)
# What is Deep Learning ?

Deep learning (also known as deep structured learning) is part of a broader family of machine learning methods based on artificial neural networks with representation learning. Learning can be supervised, semi-supervised or unsupervised.

Deep-learning architectures such as deep neural networks, deep belief networks, deep reinforcement learning, recurrent neural networks and convolutional neural networks have been applied to fields including computer vision, speech recognition, natural language processing, machine translation, bioinformatics, drug design, medical image analysis, climate science, material inspection and board game programs, where they have produced results comparable to and in some cases surpassing human expert performance.

Artificial neural networks (ANNs) were inspired by information processing and distributed communication nodes in biological systems. ANNs have various differences from biological brains. Specifically, artificial neural networks tend to be static and symbolic, while the biological brain of most living organisms is dynamic (plastic) and analogue.

The adjective "deep" in deep learning refers to the use of multiple layers in the network. Early work showed that a linear perceptron cannot be a universal classifier, but that a network with a nonpolynomial activation function with one hidden layer of unbounded width can. Deep learning is a modern variation which is concerned with an unbounded number of layers of bounded size, which permits practical application and optimized implementation, while retaining theoretical universality under mild conditions. In deep learning the layers are also permitted to be heterogeneous and to deviate widely from biologically informed connectionist models, for the sake of efficiency, trainability and understandability, whence the "structured" part. 

[For more information](https://en.wikipedia.org/wiki/Deep_learning)

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
