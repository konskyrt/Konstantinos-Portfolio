# Konstantinos Portfolio

# [Project 1: Automatic Parametrization of Civil 3D Objects](https://github.com/konskyrt/Automatic-Property-Insertion-C3D)

In this project I created a Plugin for Autodesk Civil 3D to insert automatically from an Excel list to Civil 3D Object Parameters.

The parameters are created using the Property Set function in Civil 3D.
![image](https://user-images.githubusercontent.com/46296774/170711569-c9b92fc5-5791-4375-876c-b31c48fa15ee.png)


# [Project 2: Machine Learning for a solar power plant](https://github.com/konskyrt/Machine-learning-for-a-solar-power-plant)

This is the final project during my 3 month bootcamp studies at Propulsion Academy Zurich. It was a collaboartion with Nispera AG Zurich.

Created a tool that estimates electrical power output efficiency.
We formulated a physical model and tried to see how well the real world data can adapt to it. Correctly identified several patterns that drop panel efficiency, either due to Physical phenomena and Technical aspects of the solar panels. 
The model can identify the trend of panel efficiency over time and detect in which level the panels need cleaning.

![](https://github.com/konskyrt/Konstantinos-Portfolio/blob/main/images/Capture10%20(2).PNG)

![](https://github.com/konskyrt/Konstantinos-Portfolio/blob/main/images/Capture11%20(2).PNG)


# [Project 3: Real estate price prediction and analysis site](https://github.com/konskyrt/Predicting-Home-Prices)

This data science project series is about building a real estate price prediction website. First, I built a model using sklearn and linear regression using Melbourne home prices dataset from kaggle.com. Second step would be to write a python flask server that uses the saved model to serve http requests. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price


# [Project 4: Concrete Crack detection](https://github.com/konskyrt/Concrete-Crack-Detection)

This repository contains the code for crack detection in concrete surfaces. It is a PyTorch implementation of the paper by Young-Jin Cha and Wooram Choi - "Deep Learning-Based Crack Damage Detection Using Convolutional Neural Networks"

The model acheived 98% accuracy on the validation set. A few results are shown below

![](https://github.com/konskyrt/Konstantinos-Portfolio/blob/main/images/Capture.PNG)

![](https://github.com/konskyrt/Konstantinos-Portfolio/blob/main/images/Capture2.PNG)

Dependencies required:

PyTorch, OpenCV, Dataset -The data set can be downloaded from this link: https://data.mendeley.com/datasets/5y9wdsg2zt/2

The dataset file creates the training dataset class to be fed into the Convolutional Neural Network. This class automatically determines the number of classes by the number of folders in 'in_dir' (number of folders=number of classes). Next goal of the project is to segment the cracks into more categories.

