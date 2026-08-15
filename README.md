# diagnyx-ai-breast-cancer-xai
Explainable AI prototype for breast cancer screening using EfficientNetB0 and Grad-CAM.
Explainable AI prototype for breast cancer screening using EfficientNetB0 and Grad-CAM.
# Diagnyx AI

## Explainable AI for Breast Cancer Screening

Diagnyx AI is an AI-assisted breast cancer screening prototype that analyzes mammogram images and provides an AI prediction together with a Grad-CAM visual explanation.

### Features

- Mammogram image analysis
- EfficientNetB0 deep learning model
- Benign/Malignant classification
- Grad-CAM visual explanation
- Interactive Gradio interface
- Patient-level dataset splitting

### Technology

Python, TensorFlow, Keras, EfficientNetB0, Grad-CAM, OpenCV, Pandas, NumPy and Gradio.

### Dataset

## How It Works

```text
Mammogram Image
       ↓
Image Preprocessing
       ↓
EfficientNetB0
       ↓
AI Classification
       ↓
Benign / Malignant Prediction
       ↓
Grad-CAM Explainability
       ↓
Highlighted Region
       ↓
AI-Assisted Clinical Review
## Demo

### Grad-CAM Explainability

The system provides an AI-assisted prediction together with a Grad-CAM visualization highlighting the image regions that influenced the model's prediction.

![Diagnyx AI Grad-CAM Result](gradcamresult.png)

The prototype uses the CBIS-DDSM mammography dataset. The dataset itself is not included in this repository.

### Disclaimer

This is a research/hackathon prototype and is not a medical diagnostic system. AI predictions should not replace professional clinical assessment.
