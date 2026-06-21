# MachineLearning-Project
Transfer Learning with MobileNetV2 for Flower Image Classification
Project Overview
This repository contains the code and tutorial materials for an individual machine learning tutorial on transfer learning in deep learning. The tutorial explains how a pretrained Convolutional Neural Network, MobileNetV2, can be reused as a feature extractor for a new image classification task.
The tutorial uses a flower image classification example with five classes:
Daisy
Dandelion
Roses
Sunflowers
Tulips
The main focus is not to build a production-level classifier, but to clearly demonstrate how transfer learning works and why pretrained CNNs are useful when data or training time is limited.
Tutorial Topic
Title: Transfer Learning in Deep Learning: Using MobileNetV2 to Classify Flower Images with Less Training Data
The tutorial compares two approaches:
1.A small CNN trained from scratch
2.A MobileNetV2 transfer learning model with a frozen pretrained base
This comparison helps explain how MobileNetV2 can reuse visual features learned from a large image dataset and adapt them to a smaller flower classification task.
Repository Contents│
├── README.md
├── LICENSE
├── requirements.txt
├── transfer_learning_mobilenetv2.ipynb
├── tutorial.pdf
│
└── figures/
    ├── figure_1_cnn_feature_learning.png
    ├── figure_2_sample_flower_images.png
    ├── figure_3_data_augmentation.png
    ├── figure_4_validation_accuracy_comparison.png
    └── figure_5_prediction_examples.png
Dataset
The notebook uses the flower image dataset provided through TensorFlow/Keras. The dataset contains images from five flower categories. Images are resized to 128 × 128 pixels in the notebook so that the demonstration can run quickly.
How to Run the Notebook
1.Clone or download this repository.
2.Open the Jupyter notebook:
Lakshmi_code.ipynb
1.Install the required packages:
pip install -r requirements.txt
1.Run the notebook cells from top to bottom.
The notebook will:
Load the flower image dataset
Show sample flower images
Demonstrate data augmentation
Train a small CNN from scratch
Train a MobileNetV2 transfer learning model
Compare validation accuracy
Display prediction examples
Save figures used in the tutorial
Main Python Libraries
The notebook uses:
TensorFlow
Keras
NumPy
Matplotlib
pathlib
os
Tutorial Figures
The tutorial includes the following figures:
Figure 1: CNN feature learning process
Figure 2: Example flower images
Figure 3: Data augmentation example
Figure 4: Validation accuracy comparison
Figure 5: Prediction examples from the MobileNetV2 model
All figures are either created in the notebook or designed by the author for explanation.
Accessibility
Accessibility steps included in this work:
Figures include captions
Alt text is provided for each figure
Plots use clear labels and legends
Prediction examples include written class names
The notebook contains comments explaining each major step
The tutorial uses clear section headings and sub-headings
Licence
This repository is shared under the MIT Licence. This means the code can be reused and adapted, provided that the licence terms are followed.
