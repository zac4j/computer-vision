# Computer Vision Processing in Machine Learning

This repository stores the Jupyter Notebooks of the Kaggle Computer Vision related competitions I participated in before.

The competitions are:

## Image Detection

### [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/learn-ai-bbc)

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/dazhengzhu/histopathologic-cancer-detection) | [Notebook](https://github.com/zac4j/computer-vision/blob/main/histopathologic-cancer-detection.ipynb)

### Description

In this competition, you must create an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans. The data for this competition is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset (the original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates).

### Model Performance

|       |     Model Name     | Accuracy |   Score  |
|-------|:------------------:|:--------:|:--------:|
| Train | CNN                | 0.8343   |          |
|       | EfficientNet       | 0.9226   |          |
| Test  | EfficientNet       |          | 0.8483   |

## Image Generation

### [I’m Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started/data)

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)]([https://www.kaggle.com/code/dazhengzhu/histopathologic-cancer-detection](https://www.kaggle.com/code/dazhengzhu/monet-imagen)) | [Notebook](https://github.com/zac4j/computer-vision/blob/main/monet-imagen.ipynb)

### Description

A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

Your task is to build a GAN that generates 7,000 to 10,000 Monet-style images.

### Model Performance

|       |     Model Name     | Accuracy |   Score  |
|-------|:------------------:|:--------:|:--------:|
| Train | CycleGAN           |          |          |
| Test  | CycleGAN           |          | 82.30509 |
