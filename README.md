Rice Leaf Disease Classification

 Project Overview

This project focuses on detecting and classifying common rice leaf diseases using Deep Learning (CNN). The goal is to build an efficient model to identify three major rice diseases:


Bacterial Leaf Blight

Brown Spot

Leaf Smut

The dataset consists of labeled rice leaf images, and the model is trained using Convolutional Neural Networks (CNNs). Techniques like data augmentation and hyperparameter tuning are applied for better accuracy.


📂 Dataset Access

Due to GitHub file size limitations, the dataset is hosted on Google Drive.

🔗 Download Dataset Here : https://drive.google.com/drive/folders/11JnXpF3THabW-pibgUmU57ubnBCaj_x_?usp=sharing


🔍 Tasks & Methodology

Task 1: Data Analysis & Preprocessing

Load dataset & explore sample images

Identify class distribution & perform data augmentation


Task 2: Model Development

Implement a CNN-based classification model

Train on rice leaf disease categories

Optimize performance with hyperparameter tuning


Task 3: Model Evaluation

Analyze accuracy, precision, recall, and F1-score

Compare model results and choose the best version


💡 Model Details

Model Type: Convolutional Neural Network (CNN)

Optimizer: Adam

Loss Function: Categorical Crossentropy

Performance Metric: Accuracy


📈 Results & Findings

Best Model Accuracy: 83%

Data augmentation improved generalization and reduced overfitting

Future improvements include transfer learning (ResNet, VGG16) and deployment


🏆 Conclusion

This project successfully classifies rice leaf diseases using deep learning. Future improvements may involve:

Training on a larger, more diverse dataset

Using pretrained models (ResNet, VGG) for better performance

Deploying the model via Flask or Streamlit API
