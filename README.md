# IoT-Enhanced Machine Learning Framework for Brain Tumor Detection (IOTEML)

## Overview

IOTEML is an intelligent healthcare framework that combines the Internet of Things (IoT), Machine Learning (ML), and Deep Learning (DL) for automated brain tumor detection using MRI images. The system enables real-time medical image acquisition, preprocessing, feature extraction, and classification through a cloud-edge architecture.

The framework leverages IoT-enabled imaging devices, edge computing, federated learning, and hybrid feature fusion techniques to improve diagnostic accuracy while reducing processing latency.

## Key Features

- Real-time MRI data acquisition using IoT infrastructure
- Edge-based image preprocessing
- Brain tumor detection using Deep Learning
- Hybrid feature fusion (CNN + GLCM + LBP)
- Federated learning for privacy-preserving model updates
- Cloud-edge distributed computing architecture
- Reduced latency and improved scalability
- Multi-class brain tumor classification

## System Architecture

The proposed framework consists of four layers:

1. **IoT Data Acquisition Layer**
   - MRI scanners and imaging sensors collect patient data.
   - Secure transmission using MQTT/HTTP protocols.

2. **Preprocessing Layer**
   - Noise reduction
   - Image normalization
   - Skull stripping
   - Edge-device processing

3. **Feature Extraction Layer**
   - Deep features using ResNet50
   - Texture features using:
     - GLCM (Gray-Level Co-occurrence Matrix)
     - LBP (Local Binary Pattern)

4. **Classification Layer**
   - Hybrid Ensemble Model
   - Random Forest + Softmax Classifier
   - Federated Learning Integration

## Dataset

The framework is evaluated using publicly available MRI datasets:

- BraTS 2020 Dataset
- Kaggle Brain MRI Dataset

### Classes

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- Healthy Brain

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- NiBabel
- MQTT Protocol
- Edge Computing
- Federated Learning

## Methodology

1. MRI image acquisition through IoT-enabled devices
2. Edge-level preprocessing
3. Deep feature extraction using ResNet50
4. Texture feature extraction using GLCM and LBP
5. Feature fusion
6. Hybrid classification
7. Cloud-based analytics and monitoring
8. Federated model updates

## Results

| Metric | Score |
|----------|----------|
| Accuracy | 98.4% |
| Precision | 97.5% |
| Recall | 98.2% |
| F1-Score | 97.9% |

### Additional Improvements

- 28% reduction in processing latency
- Improved tumor boundary detection
- Enhanced privacy through federated learning
- Better scalability for remote healthcare applications

## Project Structure

```text
IOTEML/
│
├── dataset/
├── preprocessing/
├── feature_extraction/
├── models/
├── federated_learning/
├── edge_computing/
├── notebooks/
├── results/
├── app.py
├── requirements.txt
└── README.md
