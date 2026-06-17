![Signal Processing](https://img.shields.io/badge/Domain-EMG_Signal_Processing-blue?style=for-the-badge&logo=mathworks&logoColor=white)
![Feature Engineering](https://img.shields.io/badge/Features-RMS_&_SSC-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Algorithms](https://img.shields.io/badge/Models-KNN_&_RandomForest-red?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=github&logoColor=white)

# EMG-Based Hand Gesture Recognition

This project, developed for the **Sensors and Measurement Systems** course at **Sharif University of Technology** (Fall 2025), focuses on the end-to-end implementation of a Machine Learning pipeline to classify hand gestures based on Surface Electromyography (EMG) signals.

## 📌 Project Overview
The primary goal was to process raw EMG signals, extract meaningful features, and employ various classification algorithms to recognize specific hand movements. The project covers the entire lifecycle of biological signal processing, from preprocessing to model evaluation.

## 🛠️ Key Features
- **Signal Preprocessing:** Implementation of Butterworth filters (`filtfilt`, `butter`) in MATLAB to clean raw EMG data and remove noise/artifacts.
- **Feature Extraction:** Calculating statistical and time-domain features such as **RMS** (Root Mean Square) and **SSC** (Slope Sign Change) to create a robust input vector.
- **Classification Models:** Implementing and comparing performance across multiple algorithms:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest (TreeBagger)**
- **Pipeline Analysis:** Investigating the "Curse of Dimensionality" and optimizing feature standardization (z-score) to improve classification accuracy.

## 📁 Repository Structure
- `/Data`: Contains the `Data_Shariftabar_Nouri.mat` dataset.
- `/Scripts`: MATLAB source code for signal filtering, feature extraction, and model training.
- `/Report`: The final technical report in PDF format (`document.pdf`).

## 🚀 Technologies & Tools
- **Language:** MATLAB
- **Toolboxes:** - Statistics and Machine Learning Toolbox (`fitcknn`, `TreeBagger`)
  - Signal Processing Toolbox
- **Visualization:** Spectral analysis, time-domain filtering plots, and confusion matrices.

## 📋 Methodology Highlights
1. **Preprocessing:** Applying band-pass filtering to isolate relevant muscle activity frequencies.
2. **Feature Engineering:** Transforming raw time-series data into a structured feature set to enhance gesture separability.
3. **Model Training:** Training models and conducting performance comparisons, identifying Random Forest as the superior classifier for this dataset.

## 👤 Team
**Vahid Hamzeh**, **Mahyar Khosropanah**, **Armin Khosrovani**
- Course: Sensors and Measurement Systems
- Instructor: Dr. Mehran Jahed
- Sharif University of Technology
