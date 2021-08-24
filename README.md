# YPDL-Identify Handwritten Digits using Convolutional Neural Network (CNN) with TensorFlow

## About the workshop

Recognizing handwritten numbers is a piece of cake for humans, but it’s a non-trivial task for machines. Currently, however, with the advancement of machine learning, people have made machines more capable of performing this task.

In this second workshop of the Your Path to Deep Learning series, we will use MNIST Dataset to build two Neural Networks capable to perform handwritten digits classification. The first Network is a simple Multi-layer Perceptron (MLP) and the second one is a Convolutional Neural Network (CNN). We will show you the step-by-step guide to create a simple handwritten digit recognizer in Watson Studio with TensorFlow.

### 🎓 What will you learn?

Create a project in Watson Studio and use Jupyter Notebook in the project.
Create a simple Multi-layer perceptron (Neural Network), to perform classification tasks.
Create a Deep Learning Neural Network and apply on MNIST.


## Workshop Resources

Login/Sign Up for IBM Cloud: https://ibm.biz/YourPathToDeepLearning

Hands-On Guide: 

Slides: 

Workshop Replay: https://www.crowdcast.io/e/ypdl-2

## Workshop Tutorial

### Step 1. Sign-up/Login to IBM Cloud

If you are an existing user please login to IBM Cloud using this link: https://ibm.biz/YourPathToDeepLearning

And if you are not, don't worry! We have got you covered! There are 3 steps to create your account on IBM Cloud: 
1. Put your email and password. 
2. You get a verification link with the registered email to verify your account. 
3. Fill the personal information fields. 
** Please make sure you select the country you are in when asked at any step of the registration process.

![IBMCloud](https://user-images.githubusercontent.com/15332386/120156441-0769d980-c203-11eb-8cb3-29f4a8d5616a.png)

### Step 2. Create Watson Studio service 

![gif 1](https://github.com/Anam-Mahmood/Unlock-the-Power-of-Machine-Learning-in-Virtual-Assistants-to-automate-Loan-Applications/blob/main/images/gif%201.gif?raw=true)

1.	Login to your IBM Cloud account: https://ibm.biz/YourPathToDeepLearning
 
2.	Within your IBM Cloud account, click on the top search bar to search for cloud services and offerings. Type in “Watson Studio” and then click on Watson Studio under “Catalog Results”.

3.	This takes you to the Watson Studio service page. Select a region, “Lite” plan (Free) and give your service a unique name. Click on “Create” and this creates a Watson Studio instance for you.

4.	Once the service instance is ready, you will be redirected to the Watson Studio page. Click on the “Get Started” button to launch Watson Studio in a new tab. This might take few minutes to set up the service.

5.	Under the heading “work with data” you will find a link that says, “Create a project”. Click on “Create a project”. Next, click on “Create an empty project”.


![gif 2](https://github.com/Anam-Mahmood/YPDL-Identify-Handwritten-Digits-using-CNN-with-TensorFlow/blob/main/images/ypdl%20gif.gif?raw=true)

6.	On the new project page, give your project a name. You will also need to associate an IBM Cloud Object Storage instance to store the data set.

7.	Under “Select Storage Service”, click on the “Add” button. This takes you to the IBM Cloud Object Store service page. Leave the service on the “Lite” tier and then click the “Create” button at the bottom of the page. You are prompted to name the service and choose the resource group. Once you give a name, click “Create”.

8.	Once the instance is created, you’re taken back to the project page. Click on “refresh” and you should see your newly created Cloud Object Storage instance under Storage.

9.	Click the “Create” button at the bottom right of the page to create your project.
