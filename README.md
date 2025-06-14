# Lung-Disease-Classifier
## Overview
The Lung Disease Classifier is an AI-powered web application that analyzes chest X-ray images to identify potential lung conditions using deep learning. The application classifies uploaded X-ray images into four categories:\
**Covid-19, Normal, Pneumonia, and Tuberculosis**.

## Features
🩻 Upload and analyze chest X-ray images through an intuitive interface\
🔍 Real-time classification using a fine-tuned VGG19 model\
📊 Confidence scoring for each prediction\
💡 Personalized health recommendations based on detected conditions\
📈 Interactive visualization of prediction confidence\

## Dataset Structure
The model was trained on a comprehensive lung disease dataset with the following structure:\
```
Lung Disease Dataset/
├── train/
│   ├── Covid/
│   ├── Normal/
│   ├── Pneumonia/
│   └── Tuberculosis/
├── val/
│   ├── Covid/
│   ├── Normal/
│   ├── Pneumonia/
│   └── Tuberculosis/
└── test/
    ├── Covid/
    ├── Normal/
    ├── Pneumonia/
    └── Tuberculosis/
```
## Setup
**Clone the repository**\
```git clone https://github.com/yourusername/lung-disease-classifier.git```\
```cd lung-disease-classifier```

**Install required dependencies**\
```pip install -r requirements.txt```
## Usage
**Start the application**\
```streamlit run app.py```\
1.Open your web browser and navigate to the provided URL\
2.Upload a chest X-ray image using the file uploader\
3.Review the classification results and follow the recommendations
## Technology Stack
**Streamlit:** Web application framework\
**TensorFlow/Keras:** Deep learning framework\
**VGG19:** Pre-trained CNN architecture (fine-tuned)\
**PIL:** Image processing\
**NumPy:** Numerical operations
## Medical Disclaimer
This application is intended for educational and demonstration purposes only. The predictions should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers for any medical concerns.

## Future Enhancements
Explainable AI features to highlight areas of concern in X-rays\
Support for additional lung conditions\
Mobile application development\
Integration with medical record systems\
## License
This project is licensed under the MIT License - see the LICENSE file for details.
