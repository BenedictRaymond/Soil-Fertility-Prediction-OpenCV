# Soil Fertility Prediction

This project aims to predict soil fertility levels using a machine learning approach. It combines synthetic image generation, feature extraction, and model training to analyze soil characteristics and provide predictions. The solution can be applied to aid agricultural practices by offering an efficient method to assess soil quality.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Future Work](#future-work)
- [License](#license)

## Overview

Soil fertility is a critical factor in agriculture, directly influencing crop yield and sustainability. This project simulates soil image data, extracts meaningful features, and leverages machine learning models to predict fertility levels. It serves as a proof-of-concept for how technology can assist in agricultural decision-making.

## Features

- **Synthetic Soil Image Generation**: Creates realistic soil images with varying fertility levels.
- **Feature Extraction**: Utilizes color and texture analysis for soil characterization.
- **Machine Learning Models**: Implements models like Random Forest, Gradient Boosting, SVR, and more for fertility prediction.
- **Performance Evaluation**: Assesses model accuracy using metrics like Mean Squared Error (MSE) and R².

## Dataset

### Synthetic Dataset Generation
- Images are generated to simulate different soil fertility levels, ranging from low to high.
- Texture and color variations are introduced to mimic real-world soil properties.
- Images are organized by fertility levels into separate directories.


## Methodology

1. **Image Generation**:
   - Created synthetic soil images using OpenCV.
   - Applied color and texture variations based on fertility levels.

2. **Feature Extraction**:
   - Extracted color features using average pixel values.
   - Extracted texture features using Gabor filters.

3. **Model Training**:
   - Trained models using extracted features to predict fertility levels.
   - Compared various algorithms for performance optimization.

4. **Evaluation**:
   - Evaluated predictions using metrics such as Mean Squared Error (MSE) and R² Score.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Machine Learning: `scikit-learn`
  - Image Processing: `OpenCV`
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`
  - Model Persistence: `joblib`

## Future Work
- Enhance synthetic dataset to include real-world soil images.
- Integrate deep learning models like CNNs for improved feature extraction.
- Build a web or mobile application for real-time soil fertility assessment.

## License
- This project is licensed under the MIT License.
