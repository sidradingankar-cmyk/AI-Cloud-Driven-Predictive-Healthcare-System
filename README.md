# Cloud-Driven Predictive Healthcare System

## Student Project

**Student Name:** Sidra Dingankar  
**Roll Number:** 5024118  
**Department:** Information Technology (IT)

---

## 1. Project Overview

This project is an academic implementation based on the research paper:

**"Cloud-Driven Predictive Healthcare System using CNN, HierbaNetV1, and LSTM for Chest X-ray and Patient Data Analysis"**

The proposed research system uses deep learning and cloud computing to analyze chest X-ray images together with sequential patient health information.

The research architecture combines:

- Convolutional Neural Network (CNN)
- HierbaNetV1
- Long Short-Term Memory (LSTM)
- Feature fusion
- Binary disease prediction
- Cloud-based storage and dashboard

The prototype implemented in this repository focuses on the **CNN-based chest X-ray classification component** of the proposed system.

### Prototype Scope

The implemented prototype classifies chest X-ray images into:

- NORMAL
- PNEUMONIA

The complete research architecture described in the paper additionally includes HierbaNetV1, LSTM-based patient-record analysis, multimodal feature fusion, cloud storage, and dashboard visualization.

---

# 2. Problem Statement

Healthcare systems generate large amounts of medical imaging and patient information. Traditional analysis can be time-consuming and may make it difficult to combine different types of medical data.

The research paper proposes a cloud-driven predictive healthcare framework that combines chest X-ray analysis with sequential patient data.

The proposed system aims to:

- Extract spatial features from chest X-ray images.
- Extract multi-scale image information using HierbaNetV1.
- Analyze temporal patient information using LSTM.
- Fuse image and temporal features.
- Generate disease prediction scores.
- Provide scalable cloud-based processing and visualization.

---

# 3. Objectives

The objectives of this implementation are:

1. Process chest X-ray images using deep learning.
2. Preprocess images into a standard input format.
3. Develop a CNN-based binary image classification model.
4. Train the model using chest X-ray data.
5. Evaluate the model using classification metrics.
6. Generate predictions for individual X-ray images.
7. Demonstrate how the CNN component can contribute to the larger proposed healthcare system.

---

# 4. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow | Deep learning framework |
| Keras | CNN model development |
| NumPy | Numerical processing |
| Matplotlib | Data visualization |
| Scikit-learn | Model evaluation |
| Pillow | Image processing |
| Google Colab | Development and execution environment |
| Kaggle | Dataset source |
| GitHub | Version control and project documentation |

---

# 5. Dataset

The research paper uses the NIH Chest X-ray14 dataset containing:

- 112,120 frontal-view chest X-ray images
- 30,805 distinct patients
- 14 thoracic disease classes
- Patient metadata such as age, gender and view position

The paper states that the images were resized to 224 × 224 pixels for model training.

### Prototype Dataset

The prototype implementation uses the Chest X-Ray Pneumonia dataset for binary classification:

- NORMAL
- PNEUMONIA

Images are resized to:

```text
224 × 224 pixels

## Reference Paper

The implementation in this repository is based on the following research paper:

**Vallu, V. R., Pulakhandam, W., Chaluvadi, A., & Hemnath, R. (2024).**

**Cloud-Driven Predictive Healthcare System using CNN, HierbaNetV1, and LSTM for Chest X-ray and Patient Data Analysis.**

*International Journal of Multidisciplinary and Current Research, Volume 12, July/August 2024.*

**DOI:** https://doi.org/10.14741/ijmcr/v.12.4.6

### Paper Details

- Authors: Visrutatma Rao Vallu, Winner Pulakhandam, Archana Chaluvadi, R. Hemnath
- Journal: International Journal of Multidisciplinary and Current Research
- Volume: 12
- Issue: July/August 2024
- Received: 25 July 2024
- Accepted: 9 August 2024
- Available online: 11 August 2024

### Relation to This Implementation

The research paper proposes an integrated healthcare system using CNN, HierbaNetV1, LSTM, feature fusion, and cloud-based healthcare infrastructure.

This GitHub project implements the **CNN-based chest X-ray classification component** as an academic prototype. HierbaNetV1, LSTM-based patient-record analysis, feature fusion, and the complete cloud dashboard are proposed as future extensions.

> **Note:** The performance values reported in the research paper are not presented as the results of this prototype.
