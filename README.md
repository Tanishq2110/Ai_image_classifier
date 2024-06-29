# AI Image Classifier

AI Image Classifier is a machine learning model that can effectively classify Real and AI Generated Images.

# Table of Contents
- [Brief Overview](#brief-overview)
- [Installation](#installation)
- [Data Sources](#data-sources)
- [Model](#model)

# Brief Overview
[(Back to top)](#table-of-contents)

This project involved building a machine learning model that can classify real and AI generated images. The first step was to create a dataset comprising of AI-generated and real images.
- CIFAKE: Real and AI-Generated Synthetic Images 

These images were preprocessed and features were extracted. Then, a Convolutional Nueral Network based Classifier model was constructed and trained on the dataset containing around 1,00,000 images.

# Data Sources
[(Back to top)](#table-of-contents)

The dataset comprised of Real and AI Generated Images.
- CIFAKE: Real and AI-Generated Synthetic Images ( [Link](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images) )
- Train Set: 100000
- Test Set: 20000

# Model
[(Back to top)](#table-of-contents)

The CNN model was built similar to `VGG16` and was trained on the train dataset. The model has a `Convolutional` Layer, `MaxPooling` Layer and a `Dropout` Layer repeated four times with increasing sizes of filters of the Convolutional Layer i.e. 32, 64, 128, and 256. It has 3 dense layers. The activation for all the layers is `relu` except for the last layer, which has activation `sigmoid`. 

> The model architecture is uploaded.


