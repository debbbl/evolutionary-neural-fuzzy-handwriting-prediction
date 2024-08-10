# Evolutionary-Neural-Fuzzy-Handwriting-Prediction

## Overview
This project was developed as part of the **WIX3001 Soft Computing course** during my second year at the **University of Malaya, Malaysia**. The project integrates three advanced soft computing techniques: Fuzzy Logic, Neural Networks, and Evolutionary Computing to predict handwriting authorship with high accuracy.

## Problem Statement
Handwriting recognition is a challenging task due to the inherent variability in human writing. This project aims to improve the reliability and efficiency of handwriting author prediction by leveraging the strengths of fuzzy logic, neural networks, and evolutionary algorithms.

## Methodology
### Data Preprocessing
- **Image Conversion**: Convert colored images to grayscale.
- **Image Segmentation**: Crop larger images into 28x28 pixel segments.
- **Image Inversion**: Invert the colors for better feature extraction.
- **Normalization**: Normalize and resize images for consistency.
- **Labeling**: Assign labels to images corresponding to their respective authors.

### Model 1: Fuzzy Logic and Neural Network
- **Fuzzy Logic System**: Extract features like stroke thickness, number of strokes, line straightness, and loop size.
- **Neural Network**: Train using the extracted features. The architecture includes multiple Dense layers with ReLU activation and Dropout for regularization.
- **Evolutionary Computing**: Optimize the neural network's hyperparameters using a genetic algorithm.

### Model 2: Enhanced Fuzzy Logic and Neural Network
- **Fuzzy Logic System**: Refine the feature extraction using intensity-based membership functions.
- **Neural Network**: Similar to Model 1 but with enhancements based on the optimized fuzzy logic features.
- **Evolutionary Computing**: Further optimization of hyperparameters using evolutionary strategies.

## Results
- **Model 1**: Achieved significant accuracy in distinguishing handwriting authors post-optimization.
- **Model 2**: Improved accuracy and robustness with refined feature extraction and neural network optimization.

## Discussion and Conclusion
- **Comparison**: Model 2 outperformed Model 1 in terms of accuracy and robustness.
- **Conclusion**: The combination of fuzzy logic, neural networks, and evolutionary computing provides a powerful approach to handwriting prediction.

## Contributors
- **Tan Shun Qi**
- **Carmen Lam Kah Man**
- **Lee Zia Qian**
- **Dernice Lee Tian Yi**
- **Lim Shi Ting**

## Supervisor
- **Dr. Liew Wei Shiung**

## Course
This project was completed as part of the **WIX3001 Soft Computing course** in Year 2 at the **University of Malaya, Malaysia**.

## License
This project is licensed under the MIT License.
