

## 🍽️ Food Image Classification Using Transfer Learning

📌 Project Overview

This project focuses on classifying food images into different food categories using Deep Learning and Transfer Learning.

A pretrained CNN model is used to extract visual features from food images and classify them into the appropriate food category.

🎯 Objective

Preprocess food images

Apply image augmentation

Use a pretrained CNN model

Perform feature extraction and fine-tuning

Classify food images into their respective categories

Evaluate the trained model


🍴 Food Classes

The dataset contains 34 food categories:

Baked Potato

Crispy Chicken

Donut

Fries

Hot Dog

Sandwich

Taco

Taquito

Apple Pie

Burger

Butter Naan

Chai

Chapati

Cheesecake

Chicken Curry

Chole Bhature

Dal Makhani

Dhokla

Fried Rice

Ice Cream

Idli

Jalebi

Kaathi Rolls

Kadai Paneer

Kulfi

Masala Dosa

Momos

Omelette

Paani Puri

Pakode

Pav Bhaji

Pizza

Samosa

Sushi


🔄 Project Workflow

Food Images
     ↓
Image Preprocessing
     ↓
Data Augmentation
     ↓
Train / Validation / Test
     ↓
Pretrained CNN
     ↓
Feature Extraction
     ↓
Fine-Tuning
     ↓
Model Evaluation
     ↓
Food Category Prediction

🧠 Transfer Learning

A pretrained CNN model is used instead of training the complete network from scratch.

Feature Extraction

Pretrained layers are initially frozen and used to extract useful image features.

Fine-Tuning

Selected pretrained layers are then unfrozen and trained with a low learning rate to adapt the model to the food dataset.

🛠️ Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

PIL / OpenCV

Jupyter Notebook / Google Colab


🤖 Model

Model: Pretrained CNN using Transfer Learning

Architecture: Add the exact model you use here, for example MobileNetV2, ResNet50, or EfficientNet.

📊 Model Evaluation

The model is evaluated using:

Accuracy


📦 Dataset

The complete dataset is not included in this GitHub repository because of its large size.

The project notebook contains the code required to load and process the dataset.

👩‍💻 Author

Divya K
BTech Graduate | AI Engineer Aspirant

⭐ Skills Demonstrated

Deep Learning • Computer Vision • CNN • Transfer Learning • Fine-Tuning • Image Classification
