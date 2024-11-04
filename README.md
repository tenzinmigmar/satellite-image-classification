# Multi-Label Rainforest Satellite Imagery Classification

Multi-label image classifier for satellite images based on atmospheric conditions using the VGG-16, AlexNet, InceptionV3 convolutional neural network architectures and Transfer Learning. Classifiers for all architectures achieved 93%+ training accuracy and 90%+ validation accuracy.

![](https://github.com/tenzinmigmar/satellite-image-classification/blob/main/banner.png)

## Overview
This project classifies various satellite imagery of the Amazon rainforest.

The challenge that was presented is to create a model that label these images based on atmospheric conditios and land usage with the over arching goal of tracking the human carbon foot-print on the world's largest rainforest.

## Features
- About the Dataset
- Understanding the dataset
- Computer Vision
  Conv Net architectures
  VGG-19
  AlexNet
  Inceptionv3
- Transfer Learning
- Amazon Satellite ML Classification model
- Data Visualization + Exploration
- Preprocessing
- Model
- Side note about Performance iv. Conclusion

## Project Structure
```
.
├── understanding-the-amazon-from-space-w-mlc.ipynb.ipynb
└── README.md
```

## Installation
```bash
# clone repository
git clone https://github.com/yourusername/satellite-image-classification.git

# install required packages
pip install -r requirements.txt
```

## Dependencies
- Python 3.7+
- tensorflow/keras
- cv2
- os
- sklearn
- numpy
- matplotlib

## Contributing
Feel free to open issues and pull requests for any improvements.

## License
MIT License

## Acknowledgments
- Dataset sourced from Kaggle: [Amazon Satellite Image Dataset](https://www.kaggle.com/datasets/prosperchuks/amazonsatelliteimages/data)
