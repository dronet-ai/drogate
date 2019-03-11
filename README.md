## DroGate : Lightweight Real-Time Drone Perception System

**Authors:** [Zeryab Moussaoui](https://fr.linkedin.com/in/zeryab-moussaoui-9a728029), [Yacine Ben Ameur]( https://www.linkedin.com/in/yacine-ben-ameur-b15aa0165) , [Houssem Meghnouj](https://www.facebook.com/azumachi.ken)

**11 Mars 2019**: Submit the code according to Alpha-Pilot deadline.

The aim of this code is to complete the selection of the Lockheed Martin's Drone Race "Alpha Pilot" (https://www.herox.com/alphapilot/77-test-2) but can be used for another applications by using Transfer Learning. 

The Alpha Pilot qualification evaluates team's skills in both Computer Vision and Machine Learning, by predicting gate locations on images :

![](https://i.ibb.co/rM0yK6H/gate-location.png)

# Architecture

DroGate is built on the efficient ResNet-based architecture. The convolution stage of the architecture consists of a fast ResNet-8 with 3 residual blocks, followed by dropout and ReLU non-linearity.
The extracted features are then processed by two separates multilayer perceptrons to predict gate locations and their confidence score :

![](https://i.ibb.co/0mFMVc4/network.png)

# Requirements

* Python (recommanded : 3.5)
* Tensorflow (recommanded : 1.12.0)
* OpenCV (recommanded : 4.0.0)
* Seaborn (recommanded : 0.9.0)

And also some librairies : numpy, python-wget, zipfile, json.

# Training

To (re) train your own Drogate, just follow instructions of [Drogate_Training](Training_Drogate.ipynb) notebook.

# Related Publications

Incoming !

