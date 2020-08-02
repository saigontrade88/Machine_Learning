# Machine_Learning
A collection of Machine Learning Study

0. Thesis

1. Neural Networks Code Assignment (Fall 2019 USF Data Mining)

Overview: a skeleton code, mnistfashionmod19.py, was provided to classify each example into its correct class among 10 classes. Modify the code so that the performance is improved above a given boundary. Explain your changes and its impact to the model.

Despcrition: (Ref: Dr.Lawrence Hall, Department of Computer Science and Engineering, University of South Florida). 

- Make a minimum of 2 changes to parameters to the file mnistfashionmod19.py in the files for the class. 
- Indicate what happened to performance and why you think this happened.  Adding more than 2 is fine if the analysis is good.  No analysis (just better accuracy does not provide a better grade). 
- Indicate if  it is a deep neural network before and after your modification.  Upload your changed code with comments AND your name in comments.  

Dataset description: Fashion-MNIST consists of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. (Source: online)

2. Build an auto encoder assignment using Keras/Tensorflow (Spring 2020 USF Machine Learning) 

Overview: Autoencoder is a neural network model which is used to reproducing/replicating the original input information using a new set of features, much smaller in size comparing to the original feature set. It is up to the user to determine the size of the new set of features. I believe that the optimal size is found after multiple experiments.

Description: 

- Build an autoencoder (look at Keras - keras.io) to have 1 hidden layer (you figure out how many units) and to recreate the examples in the following table.  

- Provide comments we would need to understand anything non-standard and comments in general." (Ref: Dr.Lawrence Hall, Department of Computer Science and Engineering, University of South Florida).

Dataset: 4 examples, 4 features, and the last column is the label.

1	0	0	0
0	1	0	0
0	0	1	0
0	0	0	1

3. Extract features from Autoencoder using Keras/Tensorflow (Spring 2020 USF Machine Learning) 

Overview: This is a follow up assignment from 2.

Description: "From the autoencoder that you built previously (4 inputs and 4 outputs), I want you to extract the features from the  hidden layer." (Ref: Dr.Lawrence Hall, Department of Computer Science and Engineering, University of South Florida).

4. Build a CNN using Keras/Tensorflow (Final project, Spring 2020 USF Machine Learning) on Gaivi's GPU, https://www.csee.usf.edu/gaivi/ 

Overview: Given the skeleton code, cifar52020class.py, by doing the requirements, I understand that one of the disadvantage of CNN is of a large number of parameters to be adjusted so execution time together with cloud renting cost is a consideration when training a complicated model. 

Description:

- Make some change(s) to the code to improve performance and show over at least two runs averaged. You must explain what you changed, provide the results and explain why you believe it improved performance.

- Build the most accurate convolution only model you can by removing the fully connected hidden layer. 

Data description: The CIFAR-10 dataset consists of 60,000 32x32 colour images in 10 classes, with 6000 images per class. There are 50,000 training images and 10,000 test images. (Source: https://www.cs.toronto.edu/~kriz/cifar.html). However, in this assignment, only part of CIFAR-10 is used for education purpose. The assignment dataset consists of 50,000 32x32 color training images, labeled over 5 animal classes except frog, and 9,999 test images.

The classes are:

0 : airplane
1 : automobile
2 : bird
3 : cat
4 : deer
5 : dog
6 : frog
7 : horse
8 : ship
9 : truck

(Ref: Dr.Lawrence Hall, Department of Computer Science and Engineering, University of South Florida).

5. Coursera's Machine Learning (completed, Summer and Fall 2019 on Coursera, virtually instructed by Dr.Andrew Ng, https://www.linkedin.com/in/andrewyng/)

Please refer to this Github link.

6. Deep Learning Specialization(ongoing, Spring 20 on Coursera, virtually instructed by Dr.Andrew Ng)

Website: https://www.coursera.org/specializations/deep-learning#courses

- Course 1: Neural Networks and Deep Learning (completed). Please refer to this link
- Course 2: Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization (ongoing, completed week 1 out of 3). Please refer to this link
- Course 3: Structuring Machine Learning Projects (not started it yet)
- Course 4: Convolutional Neural Networks (ongoing, completed week 1, and 2 out of 4). Please refer to this link
- Course 5: Sequence Models (not started it yet)
