# plant-disease-detection-efficientnet
A deep learning-based project for classifying 15 plant diseases using EfficientNetB0 and transfer learning, with a Gradio web interface for real-time predictions.
# Plant Disease Detection using EfficientNetB0

This project detects 15 different plant diseases from leaf images using transfer learning with EfficientNetB0. It includes a multi-stage training pipeline and a Gradio-based web interface for real-time use.

## Features

- Image preprocessing and augmentation
- Class imbalance handling using class weights
- Transfer learning with EfficientNetB0
- Multi-stage training (head-only, partial, full)
- Gradio interface for predictions

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas, NumPy
- Matplotlib
- Gradio

## How to Run

```bash
python gradio_app.py
