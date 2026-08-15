# AI-Based Wafer Defect Inspection

## Problem Statement

Manual wafer inspection is time-consuming and prone to errors. This project aims to develop an AI-based system that detects and classifies wafer defects from SEM images and provides suitable corrective-action recommendations.

## Objective

- Automatically inspect SEM wafer images using AI.
- Detect and classify different wafer defects.
- Provide prediction confidence for each result.
- Visualize important defect regions using Grad-CAM.
- Recommend suitable corrective actions.

## Proposed Methodology

SEM Wafer Image
↓
Image Preprocessing
↓
CNN Model
↓
Defect Classification
↓
Grad-CAM Visualization
↓
Corrective Action Recommendation

## Defect Classes

The prototype considers four classes:

- Particle
- Contamination
- Edge-Chip
- Normal

## Technologies Used

- Python
- TensorFlow / Keras
- CNN
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn
- Google Colab

## Results

The developed CNN model achieved a validation accuracy of **97.05%** on the selected dataset.

The system provides:

- Defect classification
- Confidence score
- Confusion matrix
- Grad-CAM-based defect visualization
- Corrective-action recommendation

## Corrective Action

Based on the predicted defect, the system provides a recommended action.

For example:

Contamination → Wafer cleaning and investigation of contamination source.

Edge-Chip → Check wafer handling and edge-processing conditions.

## Dataset

The project uses the Carinthia SEM Defect Dataset for wafer defect inspection.

## Future Scope

- Integration with a microscope or camera for real-time inspection.
- Support for additional wafer defect categories.
- Deployment on edge devices or FPGA-based hardware.
- Integration with automated semiconductor manufacturing systems.
