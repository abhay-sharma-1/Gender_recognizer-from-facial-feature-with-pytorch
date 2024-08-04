# Gender_recognizer-from-facial-feature-with-pytorch
## overview
This repository contains a gender classification model developed using PyTorch with the ResNet18 architecture. The model classifies facial images into two categories: male and female. Leveraging the powerful feature extraction capabilities of the pretrained ResNet18 model, this implementation provides an effective solution for gender classification tasks.
### Model Architecture 
We use the ResNet18 model, known for its residual learning framework, which helps in training deeper networks by addressing the vanishing gradient problem. The pretrained ResNet18 model from the torchvision library has been fine-tuned for binary classification by modifying its final fully connected layer to output two classes.
## [Dataset](https://www.kaggle.com/datasets/ashwingupta3012/male-and-female-faces-dataset)
Using Dataset from Kaggle which is Male and Female Faces dataset . The dataset contains 2.7k pictures of Male and Female faces respectively, covering multiple ethnicities and age groups (12-13% of data belongs to old people in both datasets).
## [Notebook]()
