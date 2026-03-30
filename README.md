# Rice-leaf-detection-cnn
## Problem statement
Task 1:-Prepare a complete data analysis report on the given data.
Task 2:-Create a model which can classify the three major attacking diseases of
rice plants like leaf blast, bacterial blight and brown spot.
Task3:- Analyze various techniques like Data Augmentation, etc and create a
report on that.

## Dataset
->Source-Kaggle
->Link-https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1001-RiceLeaf.zip
->Classes:Bacterial Blight | Brown spot | Leaf Smut
->Total images:120

## Overview
->Rice crops are highly vulnerable to diseases like Bacterial Blight, Brown Spot, and Leaf Smut, which cause significant yield loss if not detected early. This project presents an automated disease detection system built using Convolutional Neural Networks (CNN) to classify rice leaf images into their respective disease categories with high accuracy.
->The model was trained on a labeled dataset of rice leaf images, using techniques like image augmentation, normalization, and dropout regularization to improve generalization. The architecture leverages convolutional and pooling layers to extract spatial features from leaf images, followed by dense layers for classification.
This solution demonstrates the practical application of deep learning in precision agriculture, enabling farmers and agronomists to identify crop diseases faster and more accurately than traditional visual inspection methods. Built using Python, TensorFlow/Keras, and OpenCV, the project highlights the power of computer vision in solving real-world agricultural challenges.

## Tech stack
->Python, TensorFlow/Keras
->OpenCV, NumPy, Matplotlib
->Google Colab

## Results
->Achieved 95.7% of validation accuracy

## How to run
->Clone the repo
->pip install -r requirements.txt
->Run notebook in Jupyter/Colab
