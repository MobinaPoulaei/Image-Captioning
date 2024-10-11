## Image Captioning with Word2Vec and GloVe
This repository demonstrates the process of image captioning using two popular word embedding techniques, **Word2Vec** and **GloVe**, and evaluates their performances. The project leverages deep learning techniques and large image-caption datasets to generate meaningful captions for images.

## Overview
Image captioning is a challenging task that involves understanding both image and text data. The goal is to generate descriptive sentences for given images. This project uses the **Flickr8k** dataset, which contains 8,000 images along with five captions per image, and implements two embedding methods for textual data.

## Key Features
- **Image Feature Extraction**: The project utilizes Xception and InceptionV3 models (pre-trained on ImageNet) to extract meaningful features from images.
- **Textual Feature Processing**: Word embeddings are generated using both Word2Vec and GloVe, which are then used to map image features to descriptive captions.
- **Deep Learning Model**: A neural network model combining image features and text sequences is built using TensorFlow/Keras to generate captions for images.
