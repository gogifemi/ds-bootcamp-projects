# Cannabis Plant Disease Detection

## Overview

This project is the first phase of a larger initiative to create a free-of-charge cannabis plant tracking app for growers. The focus of this phase is on **Cannabis Plant Disease Detection**, where a machine learning model is trained to identify diseases from leaf images. The ultimate goal is to provide a reliable and user-friendly tool for growers to monitor and improve plant health.

---

## Phase 1: Disease Detection

### Key Features
- **Convolutional Neural Network (CNN)**: A custom-trained deep learning model to classify cannabis plant leaf images into disease categories, including healthy plants.
- **Streamlit Web Application**: Provides a simple interface where users can upload leaf images and receive predictions for potential diseases.

### Current Status
- The disease detection model is functional and provides predictions with acceptable accuracy for a prototype.
- The **Streamlit application** is not live but the previously it displayed the predicted labels for uploaded images along with confidence scores.

---

## Immediate Next Steps

The next steps focus on **optimising the current model** to improve its performance before moving on to the second phase of the project:

1. **Dataset Expansion**:
   - Collect more high-quality images for both existing and new disease classes.
   - Apply advanced data augmentation techniques to enhance the dataset.

2. **Model Optimisation**:
   - Fine-tune hyperparameters to improve accuracy, recall, and robustness.
   - Experiment with transfer learning using pretrained architectures (e.g., VGG16, ResNet).

3. **Evaluation and Testing**:
   - Validate the model on a more diverse set of images.
   - Incorporate additional performance metrics for deeper analysis (e.g., class-wise recall).

---

## Project Structure

- **`model/`**: Contains the trained CNN model.
- **`streamlit.py`**: Streamlit application script (not live).
- **`notebooks/`**: Jupyter notebooks used for EDA, data augmentation, model training, and experimentation.
- **`README.md`**: Project documentation (this file).    

---

## Problem Statement

Cannabis growers often face challenges in diagnosing plant diseases, leading to reduced yield or plant loss. A reliable and accessible solution can empower growers to detect and address issues early. However, developing such a solution requires careful handling of:
1. Limited datasets for cannabis plants.
2. The need for an easy-to-use tool for growers without technical expertise.
3. Scalability to include other features like growth tracking and strain-specific guidance.

---

## Future Roadmap

### Phase 2: Plant Growth Prediction
- Develop a predictive model for cannabis plant growth based on strain, growing conditions, and other input parameters.
- Incorporate a guide for **beginner growers**, covering:
  - Optimal pH levels, nutrients, and light cycles.
  - Strain-specific cultivation tips.

### Long-Term Vision: Free Cannabis Plant Tracking App
- Integrate disease detection and growth prediction features.
- Build a user-friendly interface for tracking plant health, growth stages, and progress.
- Provide educational resources for growers of all levels.

---

## Project Challenges

### Current Limitations
- **Dataset**: Limited publicly available datasets for cannabis plants. Synthetic data generation or expanded data collection is needed.
- **Model**: Although the current model is functional, additional improvements in accuracy and robustness are planned.