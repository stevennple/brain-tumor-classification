# Brain Tumor Classification

A deep learning-based application for automated brain tumor classification using MRI scans. This project utilizes pre-trained Xception and Custom CNN models to classify brain tumors into four categories: Glioma, Meningioma, Pituitary, and No Tumor. The application includes advanced visualization features such as saliency maps to enhance interpretability.

## Project Objectives
- Develop an accurate and reliable brain tumor classification system
- Compare performance between transfer learning and custom CNN approaches
- Create an accessible and user-friendly interface for medical professionals
- Implement explainable AI techniques for model interpretation

## Technical Implementation

### Data Processing Pipeline
1. **Data Collection & Preprocessing**
   - Dataset: Brain MRI scans with four distinct categories
   - Image preprocessing: Standardization and augmentation techniques
   - Data split: Training (70%), Validation (15%), Testing (15%)

2. **Model Architecture**
   - **Pre-trained Xception Model**
     - Transfer learning implementation
     - Fine-tuning strategies
     - Modified classification head for our specific use case
   
   - **Custom CNN Architecture**
     - Specialized layers for medical image processing
     - Optimization techniques used
     - Dropout and regularization strategies

### Key Features
- **Multi-Class Tumor Classification:** Accurate classification of brain MRI scans into four categories
- **Dual Model Support:** Utilizes both pre-trained Xception and Custom CNN architectures
- **Interactive Web Interface:** User-friendly Streamlit application for easy interaction
- **Saliency Map Visualization:** Helps understand model decision-making process
- **AI-Powered Explanations:** Detailed explanations for model predictions
- **Real-time Processing:** Quick and efficient image processing and classification

## Model Performance
- Classification accuracy metrics
- Confusion matrix analysis
- Cross-validation results
- Performance comparison between models

## Tech Stack
- **Deep Learning Framework:** TensorFlow, Keras
- **Data Processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Image Processing:** OpenCV
- **Web Interface:** Streamlit
- **Explainable AI:** Google Generative AI

## Setup and Installation

### Prerequisites
- Python 3.x
- pip package manager

### Installation Steps
1. Clone the repository:
```bash
git clone https://github.com/stevennple/brain-tumor-classification.git
cd brain-tumor-classification
```
2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Running the application:
```bash
streamlit run app.py
```
Upload an MRI scan through the web interface
View the classification results, saliency maps, and explanations

## Model Architecture
The project implements two different models:
1. **Pre-trained Xception Model:** Transfer learning approach using the Xception architecture
2. **Custom CNN:** Specialized convolutional neural network designed for brain tumor classification

## Dataset Details
The model is trained on a comprehensive dataset of brain MRI scans including:
- Glioma tumor
- Meningioma tumor
- Pituitary tumor
- No tumor (control cases)

## Results Visualization
- Real-time classification results
- Saliency maps highlighting regions of interest
- Confidence scores for predictions
- AI-generated explanations for model decisions
