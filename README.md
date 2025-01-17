# Brain Tumor Classification

A deep learning-based application for automated brain tumor classification using MRI scans. This project utilizes pre-trained Xception and Custom CNN models to classify brain tumors into four categories: Glioma, Meningioma, Pituitary, and No Tumor. The application includes advanced visualization features such as saliency maps to enhance interpretability.

## Features
- **Multi-Class Tumor Classification:** Accurate classification of brain MRI scans into four categories
- **Dual Model Support:** Utilizes both pre-trained Xception and Custom CNN architectures
- **Interactive Web Interface:** User-friendly Streamlit application for easy interaction
- **Saliency Map Visualization:** Helps understand model decision-making process
- **AI-Powered Explanations:** Detailed explanations for model predictions
- **Real-time Processing:** Quick and efficient image processing and classification

## Getting Started

### Prerequisites
- Python 3.x
- pip package manager

## Installation
1. Clone the repository:
```bash
git clone https://github.com/stevennple/brain-tumor-classification.git
cd brain-tumor-classification
```
2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Dependencies
- streamlit
- tensorflow
- keras
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- plotly
- opencv-python
- google-generativeai
- python-dotenv
- Pillow
- pyngrok

## Usage
1. Start the Streamlit application:
```bash
streamlit run app.py
```
Upload an MRI scan through the web interface
View the classification results, saliency maps, and explanations

## Model Architecture
The project implements two different models:

1. **Pre-trained Xception Model:** Transfer learning approach using the Xception architecture
2. **Custom CNN:** Specialized convolutional neural network designed for brain tumor classification

## Dataset
The model is trained on brain MRI scans containing four classes:

- Glioma tumor
- Meningioma tumor
- Pituitary tumor
- No tumor

## Results Visualization
- Real-time classification results
- Saliency maps highlighting regions of interest
- Confidence scores for predictions
- AI-generated explanations for model decisions

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python, TensorFlow, Keras
- **Data Processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Image Processing:** OpenCV
- **AI Explanations:** Google Generative AI
