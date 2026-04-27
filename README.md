# CNN-Based Image Classification for Waste Material Recognition

**Authour**: Nora Keavney
**Student Number**: G00415845

## Overview

This project explores the use of Convolutional Neural Networks (CNNs) and transfer learning for multi-class image classification of waste materials. The goal is to accurately classify images into categories such as cardboard, glass, plastic, metal, and others, supporting automated waste sorting applications.

A structured machine learning pipeline was implemented, including data preprocessing, model development, evaluation, and real-world testing.

---

## Purpose

The project aims to:

* Investigate the effectiveness of CNNs for image classification
* Compare models trained from scratch with transfer learning approaches
* Evaluate the impact of preprocessing decisions (e.g. image size, grayscale, augmentation)
* Analyse model performance using both standard metrics and real-world test images

---

## Features

* Baseline CNN implementation
* Model improvements (dropout, augmentation, architecture tuning)
* Image size and grayscale experiments
* Transfer learning using MobileNetV2
* Performance tracking (accuracy, overfitting gap)
* Confusion matrix and classification report analysis
* Real-world image testing
* Additional grayscale validation on real-world inputs

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/norakeavney/ML-Assignment-G00415845-2026.git
cd ML-Assignment-G00415845-2026
```

### 2. Install dependencies

```bash
pip install tensorflow matplotlib numpy pillow scikit-learn
```

### 3. Run the notebook

Open the main notebook:

```bash
jupyter notebook main_analysisG00415845.ipynb
```

Run cells sequentially to reproduce experiments and results.

---

## Project Structure

```
├── main_analysisG00415845.ipynb   # Main notebook (experiments + results)
├── images/                        # Sample real-world test images
├── logs/                          # Experiment logs (if included)
└── README.md                      # Project documentation
```

---

## Results Summary

* Best model: MobileNetV2 (transfer learning)
* Validation Accuracy: ~91.69%
* Test Accuracy: ~91.26%
* Key limitation: confusion between visually similar classes (e.g. plastic vs glass)

---

## Key Insights

* Transfer learning significantly outperforms CNNs trained from scratch
* Colour information is important for classification performance
* Smaller image sizes can improve efficiency without sacrificing accuracy
* Real-world performance is lower due to increased variability and noise

---

---

## 📄 Notes

This project was completed as part of a Machine Learning assignment. All experiments, model design decisions, and analysis were carried out independently.
