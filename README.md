# Real-time-Hand-Gesture-Recognition

<b>Gesture recognition is an active research field in Human-Computer Interaction technology. It has many applications in virtual environment control and sign language translation, robot control, or music creation. In this machine learning project on Hand Gesture Recognition, we are going to make a real-time Hand Gesture Recognizer using the MediaPipe framework and Tensorflow in OpenCV and Python.
# MediaPipe:-
<b>MediaPipe is a customizable machine learning solutions framework developed by Google. It is an open-source and cross-platform framework, and it is very lightweight. MediaPipe comes with some pre-trained ML solutions such as face detection, pose estimation, hand recognition, object detection, etc.
# Tensorflow?
<b>TensorFlow is an open-source library for machine learning and deep learning developed by the Google brains team. It can be used across a range of tasks but has a particular focus on deep neural networks.

# Neural Networks 
<b>Neural Networks are also known as artificial neural networks. It is a subset of machine learning and the heart of deep learning algorithms. The concept of Neural networks is inspired by the human brain. It mimics the way that biological neurons send signals to one another. Neural networks are composed of node layers, containing an input layer, one or more hidden layers, and an output layer.
![image](https://user-images.githubusercontent.com/48796009/227787532-a28ecc90-eaf9-4df1-ad78-0a46d2528cfa.png)


<b>We’ll first use MediaPipe to recognize the hand and the hand key points. MediaPipe returns a total of 21 key points for each detected hand.

![image](https://user-images.githubusercontent.com/48796009/227787541-df9f06b5-3a32-425d-af60-d47da6e13708.png)

<b>These key points will be fed into a pre-trained gesture recognizer network to recognize the hand pose.

# Prerequisites for this project:

1. Python – 3.x (we used Python 3.8.8 in this project)

2. OpenCV – 4.5

 * Run “pip install opencv-python” to install OpenCV.

3. MediaPipe – 0.8.5

 * Run “pip install mediapipe” to install MediaPipe.
4. Tensorflow – 2.5.0

 * Run “pip install tensorflow” to install the tensorflow module.
5. Numpy – 1.19.3

# Step 1 – Import necessary packages:

To build this Hand Gesture Recognition project, we’ll need four packages. So first import these.








