---
title: "GI Disease Classifier"
excerpt: "A deep learning-powered web application that classifies gastrointestinal diseases from endoscopic images with 98% accuracy."
header:
  image: AppUI.png
  teaser: AppUI.png
categories:
  - Projects
tags:
  - Deep Learning
  - Medical AI
  - Computer Vision
  - Streamlit
toc: true
toc_sticky: true
---

## Project Overview

The Gastrointestinal Diseases Classifier is a web-based application that leverages deep learning to assist medical professionals in identifying three common GI tract conditions from endoscopic images. Using a fine-tuned InceptionResNetV2 model, it achieves 98% accuracy in classifying Esophagitis, Polyps, and Ulcerative Colitis.

{% include video id="gidiseaseclassifier.streamlit.app" provider="iframe" %}

[Try the live demo](https://gidiseaseclassifier.streamlit.app/){: .btn .btn--primary .btn--large}

## Features

- **High-Accuracy Classification**: Achieves 98% accuracy on unseen endoscopic images
- **Real-time Analysis**: Instant classification results with confidence scores
- **User-friendly Interface**: Simple drag-and-drop or file upload functionality
- **Multi-class Detection**: Identifies three distinct GI conditions:
  - Esophagitis
  - Polyps
  - Ulcerative Colitis
- **Confidence Scoring**: Visual probability distribution across all possible conditions

## Technical Architecture

### Model Details
- Base Architecture: InceptionResNetV2
- Input Size: 299x299 pixels
- Output Classes: 3
- Framework: TensorFlow
- Deployment: Streamlit Cloud

### Preprocessing Pipeline
1. Image Resizing (299x299)
2. RGB Format Conversion
3. NumPy Array Transformation
4. TensorFlow Tensor Conversion

### Technology Stack
- **Frontend**: Streamlit
- **Backend**: Python
- **Deep Learning**: TensorFlow
- **Image Processing**: Pillow
- **Data Handling**: NumPy
- **Model Storage**: Google Drive with gdown

## Performance Metrics

The model demonstrates robust performance across all three classes:
- Overall Accuracy: 98%
- Real-time Processing: < 2 seconds per image
- Supported Image Formats: JPG, JPEG, PNG
``

## Use Cases

1. **Clinical Decision Support**: Assists medical professionals in quick preliminary diagnosis
2. **Educational Tool**: Helps medical students learn to identify GI conditions
3. **Research Applications**: Useful for large-scale analysis of endoscopic images

## Links
[GitHub Repository](https://github.com/byahmedali/GIDiseaseClassifier){: .btn .btn--info}
[Live Demo](https://gidiseaseclassifier.streamlit.app/){: .btn .btn--success}