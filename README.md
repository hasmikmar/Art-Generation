## Art Generation Project
# Overview

Welcome to the Art Generation Project! This project aims to explore the fascinating intersection of art and technology by leveraging GAN to generate unique and creative pieces of art. 
Whether you are an artist, a developer, or just someone interested in the creative possibilities of AI, this project provides an exciting opportunity to delve into the world of generative art.

## Usage: DCGAN

This project utilizes a DCGAN architecture for generating realistic and high-quality images. Below are the steps to train and use the DCGAN model:

## Dataset

To train and enhance the generative models, this project uses a specific dataset. You can download the dataset from the following link:

[Art Generation Dataset](https://www.kaggle.com/datasets/ipythonx/wikiart-gangogh-creating-art-gan/data)
Project dataset is taken from Kaggle .
I selected some files from this dataset because I wanted to get some interesting artistic pictures.Found 69573 files belonging to 11 classes.

- abstract': 14999,
- 'animal-painting': 1798,
- 'cityscape': 6598,
- 'figurative': 4500,
- 'flower-painting': 1800,
- 'genre-painting': 14997,
- 'landscape': 15000,
- 'mythological-painting': 2099
- 'marina': 1800,
- 'still-life': 2996,’
- 'symbolic-painting': 2999


## Preprocessing

The applied transformation will:

- Resize images to 64x64x3
- Normalize the images to [-1, 1]
- Convert images to tensors

