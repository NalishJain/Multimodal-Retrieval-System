# Multimodal Retrieval System

This repository contains the implementation of a Multimodal Retrieval System that utilizes both text and images as input data. The system is designed to perform various tasks including image and text feature extraction, retrieval based on similarity measures, and combined retrieval.

## Tasks Overview

### Image Feature Extraction:
- Utilizes basic image pre-processing techniques and a pre-trained Convolutional Neural Network (CNN) architecture (e.g., ResNet, VGG16) to extract relevant features from images.
- Extracted features are normalized for further processing.

### Text Feature Extraction:
- Implements text pre-processing techniques such as lower-casing, tokenization, stop word removal, stemming, and lemmatization.
- Calculates Term Frequency-Inverse Document Frequency (TF-IDF, scratch implementation) scores for textual reviews.

### Image and Text Retrieval:
- Finds the most similar images and reviews based on extracted features and TF-IDF scores respectively.
- Utilizes cosine similarity for similarity measurement.

### Combined Retrieval (Text and Image):
- Generates a composite similarity score by averaging the scores from image and text retrieval.
- Ranks the pairs based on the composite similarity score.

### Results and Analysis:
- Presents top-ranked (image, review) pairs along with cosine similarity scores.
- Analyzes and compares the performance of image and text retrieval techniques.
- Discusses challenges faced and potential improvements in the retrieval process.
